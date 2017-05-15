# maven-repo
My Maven Repository

## To Install To Maven Repository
`
mvn install:install-file -DgroupId=[group-id] -DartifactId=[artifact-id] -Dversion=[version] -Dpackaging=[packaging-format]-Dfile=[path-to-file] -DlocalRepositoryPath=[path-to-the-cloned-repository]
`

## In my case this will be
`
mvn install:install-file -DgroupId=com.rajendarreddyj -DartifactId=test -Dversion=1.0 -Dpackaging=jar -Dfile=/apps/sourceCode/git/rajendarreddyj/test.jar -DlocalRepositoryPath=/apps/sourceCode/git/rajendarreddyj/maven-repo
`
