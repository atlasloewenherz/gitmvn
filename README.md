********************
    GIT & MAVEN MULTIMODULE PROJECT
********************
skipp the staging area part while commiting :
git commit -a -m 'comments here'

git init
   mvn archetype:create -DgroupId=com.wordstobytes.mvn -DartifactId=mavenizedgit -DarchetypeArtifactId=maven-archetype-site-simple   

>>> cd mavenizedgit   

   mvn archetype:create -DgroupId=com.wordstobytes.mvn -DartifactId=libmodule
   mvn archetype:generate -DgroupId=com.wordstobytes.mvn -DartifactId=webapp -DarchetypeArtifactId=maven-archetype-webapp
   git add 'files and or directories resulting from above commands'   

   git remote add origin https://github.com/atlasloewenherz/gitmvn.git

