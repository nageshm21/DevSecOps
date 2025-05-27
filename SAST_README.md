SAST (Static Application Security Testing) and its tools:

SAST Summary

•	Definition: SAST involves analyzing the source code of a software application to detect security vulnerabilities. It is done during development, before deployment.

•	Purpose:    
    *	Detect known vulnerabilities and weaknesses in the code
    *	Identify risky code patterns, such as code that's hard to maintain or understand

•	How It Works:
    *	Scans the source code for specific patterns or vulnerabilities
    *	Helps identify and fix issues early, improving the application’s overall security

SAST Tools 

* Commercial SAST tools are Checkmarx, Microfocus Fortify Source Code Analysis, Microfocus Fortify On Demand, Veracode, SonarQube, SonarCloud. All these tools can be integrated in CI/CD platforms.
 * Some SAST Commercial IDE plugins are provided by Checkmarx, Veracode, Microfocus organizations
 * Free or Open source SAST tools are SonarQube, SonarCloud, Snyk
 * Some SAST Free or OpenSource IDE plugins - SonarLint, Snyk

Implementing Fortify On Demand

* Login to URL : https://my.opentext.com/home
* Creating a account using your personal e-mail account.
* Access the Fortify application using this URL: https://home.saas.microfocus.com/myaccount/#/myProducts
* We are using the EasyBuggy vulnerable application. Here is the repo link: https://github.com/nageshm21/easybuggy-vulnerable-application
