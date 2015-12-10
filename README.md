Spring4 + Hibernate4 + Gradle
=============================
Configurations
- Spring 4.1.7.RELEASE (XML Configurations)
- Hibernate 4.3.10.Final (JPA Annotation Configuration)
- Tiles 3.0.5
- Gradle Build
- CoffeeScript

Build
-----

#1 clone repository
> git clone git@github.com:slothink/quickstart-sai02.git

#2 database
> gradle makeCreateDatabaseUserSql

출력된 sql 로 mysql 에 database 및 사용자 계정 생성한다

#3 Start Server
> gradle appStart
