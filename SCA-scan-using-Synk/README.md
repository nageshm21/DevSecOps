SCA (Software Composition Analysis) AND ITS TOOLS 

SCA (Software Composition Analysis) :
•	SBOM (Software Bill of Materials): A list of all software components (including their versions) used in an application. It includes both vendor-supplied and third-party components.
        o	Purpose: To provide a complete inventory for security and compliance purposes.
        o	SBOMs are a key part of SCA.

•	What is SCA?
Software Composition Analysis (SCA) is the process of identifying and analysing third-party libraries, frameworks, and other components in a software application.

•	Goals of SCA:
    o	Detect security vulnerabilities
    o	Find licensing issues
    o	Uncover other risks from third-party use

•	How It Works:
    o	Analyses the source code to detect third-party components.
    o	Evaluates these components for vulnerabilities and compliance issues.
    o	Helps identify and resolve issues before deployment or to assess existing applications.

•	Why SCA is Important:
    o	Ensures applications are secure and industry-compliant.
    o	Crucial for large teams or applications with many third-party dependencies.
    
SCA Tools: 

* Commercial SCA tools are Synk, Veracode SCA, BlackDuck. All these tools can be integrated in CI/CD platforms
* Free/Open source SCA tools are OWASP Dependency check, Veracode

Implementing Fortify On Demand

* Login to URL : https://snyk.io/ 
* Creating a account using your personal e-mail account or your personal GitHub account or Azur AD or Docker ID.
* We are using the EasyBuggy vulnerable application. Here is the repo link: https://github.com/nageshm21/easybuggy-vulnerable-application