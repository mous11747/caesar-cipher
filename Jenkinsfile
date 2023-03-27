pipeline {
   agent any
   environment {
      GITHUB_TOKEN = credentials('github-token')
   }
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
                sh 'tag=$(git describe --tags)'
                sh 'message="$(git for-each-ref refs/tags/$tag --format=\'%(contents)\')"'
                sh 'name=$(echo "$message" | head -n1)'
                sh 'description=$(echo "$message" | tail -n +3)'
                sh 'release=$(curl -XPOST -H "Authorization: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" --data '{"tag_name":'"\"$tag\"',"target_commitish":"main","name":"Release Initial","body":"First release of caesar-cipher","draft":false,"prerelease":false}' https://api.github.com/repos/mous11747/caesar-cipher/releases)'
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
