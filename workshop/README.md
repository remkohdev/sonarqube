
## SonarQube

SonarQube is an open source, static code analysis tool to detect bugs, vulnerabilities, and code smells in your code. SonarQube can automate security scans against your source code to improve the quality of your code and perform a threat analysis. 

To use the sonarqube maven plugin, specify the maven goal "sonar:sonar" to connect to the sonarqube api.

SonarQube's security rules originate from:

* CWE Database - Common Weakness Enumeration (CWE™) is a formal list or dictionary of common software weaknesses that can occur in software's architecture, design, code or implementation that can lead to exploitable security vulnerabilities.
* SANS Top 25 - The SANS Top 25 list is a collection of the 25-most dangerous errors listed in the CWE, compiled by the SANS organization.
* OWASP Top 10 - The OWASP Top 10 is a list of broad categories of weaknesses, each can map to many individual rules.

### About this workshop

The introductory page of the workshop is broken down into the following sections:

- [SonarQube](#sonarqube)
  - [About this workshop](#about-this-workshop)
- [Agenda](#agenda)
- [Compatibility](#compatibility)
- [Technology Used](#technology-used)
- [Credits](#credits)

## Agenda

|   |   |
| - | - |
| [Lab 0: Pre-work](pre-work/README.md) | Install SonarQube |
| [Lab 1: Get Started with SonarQube](get-started-with-sonarqube/README.md) | Get Started with SonarQube, run a simple scan with scanner-cli on the NodeGoat project. |
| Lab 2: Run Sonar Scanner in Tekton Pipeline | TBD |
| Lab 3: Add OWASP Dependency Check to SonarQube | TBD |

## Compatibility

This workshop has been tested on the following platforms:

* **MacOS**: Catalina v10.15.6
* **Brave**: Version 1.12.114 Chromium: 84.0.4147.135 (Official Build) (64-bit)
* **SonarQube**: Community EditionVersion 8.4.1 (build 35646)
* **SonarScanner**: 4.4.0.2170
* **Java**: 11.0.3 AdoptOpenJDK (64-bit)

## Technology Used

* SonarQube is an automatic code review tool to detect bugs, vulnerabilities, and code smells in your code.

## Credits

* [Remko de Knikker](https://github.com/remkohdev)
