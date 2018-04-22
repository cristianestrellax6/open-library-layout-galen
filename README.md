# open-library-layout-galen
## Products: OpenLibrary
> ### Test Types: UI

#### Scope:
* SignUp Page
* Login Page

Galen Framework layout test
==========
Automated tests with Galen 2.3.6

Resources needed
==========
Recommended install:  
Install [NodeJS](https://nodejs.org/en/download/) (version => 6)  

[Sublime Text 2](https://download.sublimetext.com/Sublime%20Text%202.0.2.dmg)  
With: [Syntax Highlighter for Galen Framework v2+](https://github.com/davidrv87/syntax-sublime-galen2)  
OR  
[VS Code](https://go.microsoft.com/fwlink/?LinkID=620882)   
With: Galen Syntax Support for VSCode's Extension.

The default configuration is in FireFox but:
    If you want test in Chrome, make sure to have the latest Chromedriver or install:
    webdriver-manager via npm (npm install -g webdriver-manager)

Install Galen:  

    npm install -g galenframework-cli@2.3.6

Environment
==========
Clone GitHub repository and install dependencies:

Run the tests locally
==========
By command line:

    For Tablet: galen test my.test --htmlreport ../reports --filter "*Tablet*"
    For Desktop:  galen test my.test --htmlreport ../reports --filter "*Desktop*"
    All:  galen test my.test --htmlreport ../reports

Reports
=======
To see the report just open the report.html inside ./reports

    CMD: "open reports/report.html"

