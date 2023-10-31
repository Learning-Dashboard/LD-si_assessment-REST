# LD-si_assessment-rest [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
Wrapper to provide the LD-si_assessment library functionality as RESTful services.

## Main Functionality
This component wraps [LD-si_assessment](https://github.com/Learning-Dashboard/LD-si_assessment) library in order to access it as a RESTful service.

## Technologies
| Property | Description |
| -------------------- | ----------------------|
| Type of component    | RESTful Service       |
| Build                | .war                  |
| Programming language | Java                  |
| Frameworks           | Spring Boot, Gradle   |
| External libraries   | LD-si_assessment      |

## How to build
This is a Gradle project. You can use any IDE that supports Gradle to build it, or alternatively you can use the command line using the Gradle wrapper with the command *__gradlew__* if you don't have Gradle installed on your machine or with the command *__gradle__* if you do, followed by the task *__war__*.

```
# Example: using Gradle wrapper to build with dependencies
cd LD-si_assessment-rest
gradlew war
```
After the build is done the WAR file can be found at the __build/libs__ directory

## How to deploy

Prerequisites: 
* A web server, e.g. Tomcat
* Oracle Java JRE

Deployment steps:
1. Deploy LD-si_assessment-rest-X.Y.X.war in your Web Server

## Documentation
You can find the technical documentation of the RESTful API [here](https://learning-dashboard.github.io/LD-si_assessment-rest/).

## Licensing
This program is free software: you can redistribute it and/or modify 	it under the terms of the GNU General Public License as published by 	the Free Software Foundation, either version 3 of the License, or 	 (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

## Contact
For problems regarding this component, please open an issue in the [issues section](https://github.com/Learning-Dashboard/LD-si_assessment-rest/issues).
