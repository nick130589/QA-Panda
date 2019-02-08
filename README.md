# selenide-cucumber-allure-reports-java

[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=NXdCNkhNR090eXZ2K3dGd3NMV012SEJwVTZJa21WRnJRbGJuT1A1b2NzTT0tLTNMWTRmSW8zbGpjNUFEd29ZQUZwQ3c9PQ==--3fc08c598fcdba2229dff66e3d941b61807e4dc0WHM0005970)](https://www.browserstack.com/automate/public-build/NXdCNkhNR090eXZ2K3dGd3NMV012SEJwVTZJa21WRnJRbGJuT1A1b2NzTT0tLTNMWTRmSW8zbGpjNUFEd29ZQUZwQ3c9PQ==--3fc08c598fcdba2229dff66e3d941b61807e4dc0WHM0005970)

Automation Testing Using BrowserStack, Selenide API, Cucumber and Allure reports

Behavior Driven Development (BDD) approach to write automation test scripts.  
The framework is fully functional 'out of the box'. 


Getting Started
-------------
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
--------------  
[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Getting Started - Installing Git  
[Maven](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html) - Maven in 5 Minutes  

How to install this project
-------------
git clone https://github.com/Pavelya/selenide-cucumber-allure-reports-java  

Running the tests - command line mode
-------------------
cd to project path  

mvn clean install test -U -Denv=pp1 "-Dcucumber.options=--tags @google --plugin io.qameta.allure.cucumberjvm.AllureCucumberJvm"

Running the tests - from IDE  
-------------------
Run [src/test/java/com/qa/automation/BaseTest.java](src/test/java/com/qa/automation/BaseTest.java)  as maven test


Documentation
-------------
* [Pass external parameters to test](doc/working_with_parameters.md)
* [Use allure reports](doc/allure_reports.md)
* [Bug template](doc/bug_report.md)
* [Feature request template](doc/feature_request.md)

Built With
-------------
* [Browserstack](https://www.browserstack.com/) - Cloud web and mobile testing platform  
* [Selenium](http://www.seleniumhq.org/) - Portable framework for testing web applications
* [Selenide](http://selenide.org/) - Framework for test automation powered by Selenium WebDriver
* [Maven](https://maven.apache.org/) - Dependency Management
* [Cucumber](https://cucumber.io/) - Behavior Driven Development (BDD) library 
* [Allure reports](http://allure.qatools.ru/) - Framework designed to create test execution reports
* [Owner API](http://owner.aeonbits.org/) - Java properties management

Contributing
-------------
Please read [CONTRIBUTING.md](doc/CONTRIBUTING.md) for details of the process for submitting pull requests.

Versioning
-------------
[SemVer](http://semver.org/) is in use for versioning.  

Authors
-------------
**Pavel Yampolsky**  - Skype: pavel.yampolsky.willhill Email: 2pavelya@gmail.com

License
-------------
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Thanks  
-------------  
Huge kudos to wonderful software that allowed to create this project:

[![BrowserStack](https://www.browserstack.com/images/mail/browserstack-logo-footer.png)](https://www.browserstack.com)  
[![Selenide](https://selenide.org/images/selenide-logo-big.png)](https://selenide.org)  
[![Allure](https://avatars3.githubusercontent.com/u/5879127?s=200&v=4)](https://github.com/allure-framework/allure2)  
[![Cucumber](https://raw.githubusercontent.com/cucumber-ltd/brand/master/images/png/notm/cucumber-black/cucumber-black-128.png)](https://cucumber.io/)
[![Maven](https://maven.apache.org/images/maven-logo-black-on-white.png)](https://maven.apache.org/)