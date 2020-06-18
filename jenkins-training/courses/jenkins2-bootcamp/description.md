This is a comprehensive course designed to show how to setup and run a Jenkins CI server starting with continuous inspection (build, test and analysis) all the way through to continuous deployment. This course provides a strong foundation for implementing continuous inspection, continuous integration, continuous delivery, and even continuous deployment at your company or studio. In order to ikeep the course short and to-the-point, several decisions were made in order to provide a complete path from CI to CD.

The pipeline created in this course consists of the following:

Jenkins CI server installed and configured on Windows

Git as the source control system

Java as the main programming language of build projects

Maven as the build tool

Findbugs, PMD, and Checkstyle as the static code analysis tools

Tomcat as the deployment server

Setup Jenkins in AWS using Lightsail

Use EC2 Plugin for Auto-scaling

This set of tools provides a comprehensive, end-to-end implementation continuous deployment pipeline. Jenkins can be installed on many operating systems and supports a myriad of tools and technologies -- which means, this course provides tremendous value to those comfortable or interested in other operating systems and/or technologies.

Course Outline

Introduction provides an overview for the course, which leas to the Core Concepts for Jenkins. This provides a foundation for the remainder of the course.

Installation provides step-by-step instructions on how to setup Jenkins and all the related tools specifically on Windows. The same principles are applicable to other operating systems as well.

The Basics provides a first look at Jenkins at work with a very simple "freestyle" project. This allows us to learn the Jenkins interface and the key features it provides.

After that, we dive into Maven Projects specifically -- since Jenkins natively understand Maven and thus provides special features for Maven projects.

Jenkins can do so much more than simply building. In Test & Quality, we hook up a standard set of unit testing and quality analysis tools for Java projects. Then, we use that information to affect the build status based on established standards.

We also cover how to use Jenkins as an artifact repository which is used to store the build artifacts, like jars and wars, after successful builds. This is particularly useful when integrating Jenkins with other tools in a more comprehensive software delivery strategy.

Then, we bring everything together for Deployment to a running Tomcat server. Don't worry, I'll walk you through the complete setup and configuration to work seamlessly with Jenkins!

Finally, no course would be complete without talking about Security. In this final chapter, we setup Jenkins to allow users to login and only see their projects.

Course Features

Presentations provide audio/video training of conceptual ideas in each major area or introduction of new concepts.

Screencasts provide a video of the instructor's computer system with any actions, commands, or screens displayed and narrated. There are several hours of screencat video content -- it makes up the vast majority of the course. Any command line based screencast will include a command listing in the lecture downloads.
