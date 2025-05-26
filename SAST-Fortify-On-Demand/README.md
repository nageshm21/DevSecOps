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

