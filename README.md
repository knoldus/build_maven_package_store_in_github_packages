# build_maven_package_store_in_github_packages
## Build the maven package and store it into the github packages
## Prerequisite
1. java install on local 
2. maven install on local 
## Points we should know 
1. Add your github credentials in the pom.xml file 
2. First build the package by the maven command mvn build
3. Then publish the package by the commandd mvn deploy 
4. This will deploy the package into the github repo 
