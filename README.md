# College Connect
Emily Trinh
## Project Abstract
This open source project is an android mobile application tailored towards college students, hosted on Google’s Firebase platform. The application addresses the needs of college students and acts as a centralized platform where students can share notes, keep track of their attendance, collaborate with peers, and find the latest events around campus. This project aims to bring convenience and accessibility for college students, utilizing SQLite and Firebase to host it’s data in the back end and Material UI as the front end React framework. The open issues range from migrating an SQLite database to data encryption.

![UML](/College_Connect_UML.png)

## Project Relevance
This proposal aligns with the course goals because it includes database management, graphical user interface based front end design, as well as object oriented design. Because this is an open source project, it is test driven as every attempted solution needs to be tested before it can merge with the master branch, and the issues in this project include a wide range of topics which require on-the-fly coding, where we will have to think of the solution as we go. It is an entire full stack application that is already available on the play store, which means it offers a complete in-depth look at software development within the context of building and testing, version control, and project management. It is hosted as an open source project on github.

## Conceptual Design
As this is an open source project hosted on github, it details the open issues available for individuals to solve. Based on the description of these issues, I propose that the team contribute to the creation of the Project Collaboration feature, which is supposed to allow students to post school projects that they need help with. This issue utilizes the Android platform to generate a mobile page in which students can enter the details of their projects to a repository where other students can view, and contact them to offer help. The project information details will be stored on Firebase as the backend. In addressing this issue, the team will be able to build the front and back end of a mobile component on top of an already existing application. It will involve team code management, android development, front end user interface design, and database management, and exposure to software design patterns. 

## Background

<https://github.com/collegeconnect/CollegeConnect>

***Building***
- Ensure Intel VT-d, virtualization technology, is available on local machine to be able to run phone emulator 
  —  Disable Hyper-V before moving forward.
- Compile with Android Studio, Google’s android application platform.
- Fork and clone the original repo, then import to Android Studio environment.
- Add Firebase to the project to generate google-service.JSON file —  Create new project & register it, then download the json file and add it under src in android studio project directory
- Go to SDK Manager — > SDK tools — > make sure Intel HAXM Installer is installed, as well as SDK Manager — > SDK Platforms — > Android 10.0 for API 29

**Running**
- Has a main and a test case
- Need to add an AVD: virtual device to run the app (through Android Studio)
- Select "Run App" from the Run menu in Android Studio.
 

## Required Resources
- _Group members competencies_
  - Java 
  - SQLlite
  - React
- _Hardware and software resource required_
  - Android Studio
  - Firebase project — > connect to app

