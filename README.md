# SonarQube

### Sonarqube installation :
* Run :

> `docker-compose up`

* Configure the project in localhost 9000
* Credentials : admin, admin
* create new project > generate token (save this token for future configurations)

### Install Dotnet sonarqube (Mac OSx): 

`dotnet tool install --global dotnet-sonarscanner`

### Excecute Scanner:

`dotnet sonarscanner begin /d:sonar.login=<token> /k:<sonar project name>`

`dotnet build`

`dotnet sonarscanner end /d:sonar.login=<sonar project name>`

* review the results in http://localhost:9000




