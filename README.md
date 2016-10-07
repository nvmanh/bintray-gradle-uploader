# bintray-gradle-uploader

> gradle build bintrayUpload --info

or with the gradle wrapper in Unix

> ./gradlew build bintrayUpload --info

and the gradle wrapper in Windows

> gradlew.bat build bintrayUpload --info

### Add followings to your local.properties

        bintray.user=user_name
        bintray.apikey=api_key
        bintray.gpg.password=password
        bintray.oss.user=your_maven_central_user_name
        bintray.oss.password=your_maven_central_password