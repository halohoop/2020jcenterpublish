# 2020jcenterpublish

## To Publish Java Gradle Project
  1. edit your bintray username,groupId,artifactId,version,desc...etc.
  2. `./gradlew bintrayUpload -PapiKey=your_bintray_apikey`

## To Publish Android Gradle Project
  1. edit your bintray username,groupId,artifactId,version,desc...etc.
  2. get a aar first `./gradlew :yourLibraryProjectName:assembleRelease`
  3. `./gradlew :yourLibraryProjectName:bintrayUpload -PapiKey=your_bintray_apikey`
