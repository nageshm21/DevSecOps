SCA AND ITS TOOLS 

* SBOM stands for "Software Bill of Materials" is a list of all the software components and their versions that are included in a particular software application or system. The SBOM includes both the first-party components that were developed by the software vendor and the third-party components that were used to build the application. The purpose of an SBOM is to provide a complete and accurate inventory of all the components that make up a software application or system. SBOMs are an important part of software composition analysis (SCA) and are increasingly being used in the software development and maintenance process to ensure the security and compliance of applications. 
* Software Composition Analysis(SCA) scan is a process of identifying and analyzing the third-party libraries, frameworks, and other components that are used in a software application. The goal of SCA is to identify potential security vulnerabilities, licensing issues, and other risks associated with the use of third-party components in an application. 
* Software Composition Analysis(SCA) scan is a process of identifying and analyzing the third-party libraries, frameworks, and other components that are used in a software application. The goal of SCA is to identify potential security vulnerabilities, licensing issues, and other risks associated with the use of third-party components in an application.
* It involves analyzing the source code of an application to identify the third-party components that it uses, and then evaluating these components for security vulnerabilities, licensing issues, and other risks. The results of the SCA process can be used to identify and fix potential problems before the applicatiovis released, or to assess the security and compliance of an existing application. 
* SCA is an important aspect of software development and maintenance, as it helps to ensure that applications are secure and compliant with industry standards and regulations. It is especially important in large organizations where multiple developers may be working on different parts of the same application, or where applications are built using a variety of third-party components

SCA Tools: 

* Commercial SCA tools are Synk, Veracode SCA, BlackDuck. All these tools can be integrated in CI/CD platforms
* Free/Open source SCA tools are OWASP Dependency check, Veracode

Implementing Fortify On Demand

* Login to URL : https://snyk.io/ 
* Creating a account using your personal e-mail account or your personal GitHub account or Azur AD or Docker ID.
* We are using the EasyBuggy vulnerable application. Here is the repo link: https://github.com/nageshm21/easybuggy-vulnerable-application