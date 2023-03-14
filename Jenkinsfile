pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               sh './gradlew build'
           }
       }
       stage('Test') {
           steps {
               sh './gradlew test'
           }
       }
       stage('Release') {
            steps {
                sh 'token="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"'
                sh 'tag=$(git describe --tags)'
                sh 'message="$(git for-each-ref refs/tags/$tag --format=\'%(contents)\')"'
                sh 'name=$(echo "$message" | head -n1)'
                sh 'description=$(echo "$message" | tail -n +3)'
                sh 'release=$(curl -XPOST -H "Authorization:token $token" --data \'{"tag_name": "$tag", "target_commitish": "main", "name": "$name", "body": "$description", "draft": false, "prerelease": false}\' "https://api.github.com/repos/mous11747/caesar-cipher/releases)"'
            }
        }
       stage('Deploy') {
           steps {
               // Add deployment steps here
               echo 'Deploying....'
           }
       }
   }
}
