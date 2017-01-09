https://www.mulesoft.com/ty/dl/studio
from Gopal Erusu to All Participants:
    <proxy>
      <active>true</active>
      <protocol>http</protocol>
      <username>*****</username>
      <password>*****</password>
      <!-- <host>proxyconfig.bankofamerica.com</host> -->
      <!-- <host>proxyconfig.asia.bankofamerica.com</host> -->      
      <host>rrwebproxy.bankofamerica.com</host>
      <port>8080</port>
      <nonProxyHosts>*.bankofamerica.com|localhost</nonProxyHosts>
    </proxy>    
  </proxies>
from Gopal Erusu to All Participants:
# maven-project

This is my Maven project from MuleSoft's advanced development class

## How to run the project

1. Add the remote repository: `git remote add origin https://github.com/{yourGithubUser}/maven-project.git`

1. Enter the repo: `cd maven-project`

1. (Optional) Set your MULE_HOME env variable: `export MULE_HOME={locationOfMuleInstall}`

1. Package and deploy: `mvn install` 