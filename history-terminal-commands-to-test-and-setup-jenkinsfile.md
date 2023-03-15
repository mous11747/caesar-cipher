 1891  mkdir caesar-cipher && cd caesar-cipher
 1892  git clone https://github.com/mous11747/caesar-cipher.git
 1893  ls
 1894  cp caesar-cipher /home/atta
 1895  cp -r caesar-cipher /home/atta
 1896  cd -
 1897  ls
 1898  cd caesar-cipher
 1899  ls
 1900  ./gradlew build
 1901  ./gradlew build
 1902  readlink -f $(which java)
 1903  export JAVA_HOME="/usr/lib/jvm/java-11-oracle"
 1904  ./gradlew build
 1905  gedit Jenkinsfile
 1906  ls
 1907  gedit Jenkinsfile
 1908  gedit build.gradle
 1909  gedit Jenkinsfile
 1910  ls
 1911  mv Jenkinsfile /home/atta
 1912  ls
 1913  gedit Jenkinsfile
 1914  ls
 1915  git push origin main
 1916  $ ssh-keygen -t ed25519 -C mostafaali@web.de
 1917  $ ssh-keygen -t ed25519 -C "mostafaali@web.de"
 1918  ls -al ~/.ssh
 1919  gedit Jenkinsfile
 1920  gradle
 1921  gradle --versin
 1922  gradle --version
 1923  ls
 1924  cd bin
 1925  ls
 1926  cd ..
 1927  ./gradlew build
 1928  ls -laht
 1929  cd build/
 1930  ms
 1931  ls
 1932  cd libs/
 1933  ls
 1934  java -jar caesar-cipher.jar 
 1935  cd ..
 1936  ls
 1937  vim build.gradle 
 1938  ./gradlew build
 1939  java -jar build/libs/caesar-cipher.jar 
 1940  cd caesar-cipher/
 1941  git remote -v
 1942  git remote add origin git@github.com:mous11747/caesar-cipher.git
 1943  git remote -v
 1944  git push origin v.1
 1945  cat ~/.ssh/id_ed25519.pub 
 1946  git push origin v.1
 1947  cat Jenkinsfile 
 1948  tag=$(git describe --tags)
 1949  echo $tag
 1950  $tag
 1951  git describe --tags
 1952  git tag --help
 1953  git tag -l
 1954  git describe --all
 1955  git log
 1956  git log --pretty=oneline
 1957  git tag -a 1.2
 1958  git log --pretty=oneline
 1959  git push origin 1.2
 1960  git describe --all
 1961  git describe --tags
 1962  cat Jenkinsfile 
 1963  message="$(git for-each-ref refs/tags/$tag --format=\'%(contents)\')"
 1964  message=$(git for-each-ref refs/tags/$tag --format=%(contents))
 1965  git for-each-ref refs/tags/$tag
 1966  git for-each-ref refs/tags/$tag --format='%(contents)'
 1967  message=$(git for-each-ref refs/tags/$tag --format='%(contents)')
 1968  echo $message
 1969  history
 1970  jenkins
 1971  cat Jenkinsfile 
 1972  echo "$message" | head -n1
 1973  git log
 1974  cat Jenkinsfile 
 1975  echo "$message" | tail -n +3
 1976  curl -XPOST -H "Authorization:token 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" --data \'{"tag_name": "$tag", "target_commitish": "main", "name": "$name", "body": "$description", "draft": false, "prerelease": false}\' "https://api.github.com/repos/mous11747/caesar-cipher/releases")
 1977  curl -XPOST -H "Authorization:token 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" --data \'{"tag_name": "$tag", "target_commitish": "main", "name": "$name", "body": "$description", "draft": false, "prerelease": false}\' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1978  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": "$tag", "target_commitish": "main", "name": "$name", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1979  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": "$tag", "target_commitish": "main", "name": "test", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1980  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": "1.3", "target_commitish": "main", "name": "test", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1981  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": "1.4", "target_commitish": "main", "name": "test", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1982  git tag -l
 1983  git tag -a 1.5
 1984  $tag=(git tag -a 1.5)
 1985  $tag=$(git tag -a 1.5)
 1986  git tag --help
 1987  $tag=$(git tag -a 1.6 -m 'My Super 1.6 version')
 1988  $tag=$(git tag -a 1.6 -m "My Super 1.6 version")
 1989  $tag=$(git tag -a '1.6' -m "My Super 1.6 version")
 1990  $tag=$(git tag -a '1.7' -m "My Super 1.7 version")
 1991  echo $tag
 1992  $tag=$(git tag -a '1.8' -m 'My Super 1.8 version')
 1993  tag=$(git tag -a '1.8' -m 'My Super 1.8 version')
 1994  tag=$(git tag -a '1.9' -m 'My Super 1.9 version')
 1995  echo $tag
 1996  tag=$(git describe --tags)
 1997  echo $tag
 1998  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 1999  tag=$(git tag -a '2' -m 'My Super 2 version')
 2000  tag=$(git describe --tags)
 2001  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file build/libs/caesar-cipher.jar "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2002  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2003  git config --global http.version HTTP/1.1
 2004  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2005  git config --global http.postBuffer 157286400
 2006  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2007  git config --global http.version HTTP/1.1
 2008  git push 
 2009  git config --global http.version HTTP/2
 2010  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2011  git config --global http.postBuffer 524288000
 2012  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2013  git config --global http.version HTTP/1.1
 2014  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2015  git config --global http.postBuffer 157286400
 2016  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2017  git config --global http.version HTTP/1.1
 2018  git config --global http.postBuffer 157286400
 2019  git config --global http.version HTTP/1.1
 2020  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' --upload-file "build/libs/caesar-cipher.jar" "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2021  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2022* curl -XPOST -H "Authorization:token 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" --upload-file "build/libs/caesar-cipher.jar" --header "Content-Type: application/java-archive" "https://uploads.github.cooctect-stream 11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2023  curl -XPOST -H "Authorization:token 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" --data-binary "build/libs/caesar-cipher.jar" --header "Content-Type: application/octet-stream" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2024  curl -X POST -H "Authorization:token github_pt_11ARL2QNY0Vb50lRjPGyq1_TQoG0akl6qTByClQX5PO9tCVpPVAkO78AoAWLpFVqAfDUNE3HWOjH51jqnd" --data-binary "build/libs/caesar-cipher.jar" --header "Content-Type: application/octet-stream" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2025  curl -X POST -H "Authorization:token github_pt_11ARL2QNY0Vb50lRjPGyq1_TQoG0akl6qTBy
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" --header "Content-Type: application/octet-stream" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2026  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2027  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" --data-binary "build/libs/caesar-cipher.jar" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/2/assets?name=caesar-cipher.jar"
 2028  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" --data-binary "build/libs/caesar-cipher.jar" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/1.9/assets?name=caesar-cipher.jar"
 2029  git tag -a '2.1' -m 'My Super 2.1 version'
 2030  tag=$(git describe --tags)
 2031  echo $tag
 2032  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases"
 2033  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" --data-binary "build/libs/caesar-cipher.jar" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/95585303/assets?name=caesar-cipher.jar"
 2034  jq
 2035  git tag -a '2.2' -m 'My Super 2.2 version'
 2036  tag=$(git describe --tags)
 2037  id=$(curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r 'id')
 2038  echo $id
 2039  curl -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r 'id'
 2040  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r 'id'
 2041  git tag -a '2.3' -m 'My Super 2.3 version'
 2042  tag=$(git describe --tags)
 2043  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": '"\"$tag\""', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r 'id'
 2044  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": '2.2', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r '.id'
 2045  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": '2.3', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r 'id'
 2046  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": '2.4', "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq
 2047  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": "2.4", "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq
 2048  curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": "2.5", "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r '.id'
 2049  id=$(curl -s -XPOST -H "Authorization:token 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" --data '{"tag_name": "2.6", "target_commitish": "main", "name": "My Super Caesar cmdline tool", "body": "$description", "draft": false, "prerelease": false}' "https://api.github.com/repos/mous11747/caesar-cipher/releases" | jq -r '.id')
 2050  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" --data-binary "build/libs/caesar-cipher.jar" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/$id/assets?name=caesar-cipher.jar"
 2051  git describe
 2052  curl -X POST -H "Authorization:token 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" --header "Content-Type: application/octet-stream" --data-binary "build/libs/caesar-cipher.jar" "https://uploads.github.com/repos/mous11747/caesar-cipher/releases/$id/assets?name=caesar-cipher.jar"
 2053  git describe
 2054  history
 2055  history > jenkinsfile-cml-to-setup-releases-&-tags.txt 
