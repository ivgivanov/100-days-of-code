# 100 Days Of Code - Log

### Day 0: June 1, 2020

**Today's Progress:** Commited to the 100 days of code chellange and published blog article explaining my motivation

**Thoughts:** I already got great support form the community on twitter. Feels nice!

**Link to work:** [person blog post](https://ivgivanov.info/posts/100-days-of-code/)


### Day 1: June 2, 2020

**Today's Progress:** Learned how to build, package and run java application from command line and IDE

**Thoughts:** It's getting more and more clear how java actually works and what it depends on. It's always benefitial to understand the very basics before diving deep. 

**Link to work:** [First simple project with VSCode](https://github.com/ivgivanov/learningJava/tree/master/1.%20build%20and%20run%20simple%20app)


### Day 2: June 3, 2020

**Today's Progress:** Theoretical lesson, when and why to use Java

**Thoughts:** There is no single answer for all questinos, right? There were nice comparisons covered in the course against other languages as well as the general philosophy behind Java.

**Link to work:** N/A


### Day 3: June 4, 2020

**Today's Progress:** Exploring commonly used Java libraries

**Thoughts:** One particular statement during the course got my attention - no need to re-invent the wheel. There are a lot of high quality and open-source java libraries which can save you significant amount of time writing it from scratch.

**Link to work:** N/A


### Day 4: June 5, 2020

**Today's Progress:** Math operations

**Thoughts:** I got some clarification on how prefix and postifx increment/decrement operators work. Be very careful with narrowing converstions!

**Link to work:** [Math operations](https://github.com/ivgivanov/learningJava/tree/master/2.%20math%20operations/math-operations/src)


### Day 5: June 6, 2020

**Today's Progress:** Exploring vSphere object model

**Thoughts:** Created a small app that connects to a vCenter Server and retrieves very basic info. Used the knowledge from previous days to package it into executable .jar including the dependencies. Apperantly, this is called fat jar.

**Link to work:** [Exploring vSphere object model](https://github.com/ivgivanov/learningJava/tree/master/3.%20Exploring%20vSphere%20SDK/tin)


### Day 6: June 7, 2020

**Today's Progress:** Using vCenter PropertyCollector

**Thoughts:** The vCenter object model is quite complex. I was using the PropertyCollector to get specific (or all) properties for a given ManagedObject.

**Link to work:** [Using vCenter property collector](https://github.com/ivgivanov/learningJava/commit/fa5677e12f6a6795985cd98f8e73eaf55582cef6)


### Day 7: June 8, 2020

**Today's Progress:** Theoretical lesson, logical operators, loops and arrays

**Thoughts:** Refreshed my knowledge and use-cases of different loops. I really like the 'conditional assignment' syntax.

**Link to work:** N/A


### Day 8: June 9, 2020

**Today's Progress:** Classes and objects in Java

**Thoughts:** Every rules has exceptions. Everything in Java is objects, except primitives

**Link to work:** N/A


### Day 9: June 10, 2020

**Today's Progress:** Using vCenter AuthorizationManager to create a VC role with permissions

**Thoughts:** Everything starts with the VimPort! When calling methods found in the SDK documentation I need to use instance of VimPortType and pass as first arguemnt the object type I found the method from.

**Link to work:** [Using vCenter AuthorizationManager](https://github.com/ivgivanov/learningJava/commit/51945222b594cf0bfdbeaf8c82432578c0f0df7d)


### Day 10: June 11, 2020

**Today's Progress:** Using (and undersatding) access modifiers in Java

**Thoughts:** Now I better understand the usage of getters and setters.

**Link to work:** [Using access modifiers](https://github.com/ivgivanov/learningJava/commit/aea1a0cf2d27f8bd632c708f0a4f7e6b9f211008)


### Day 11: June 12, 2020

**Today's Progress:** Theory, constructors and method signatures

**Thoughts:** I learned the order of assigning values to properties during creation of instance of a class. Understood what makes up the method signature

**Link to work:** N/A


### Day 12: June 13, 2020

**Today's Progress:** Refactor vCenter role creation and add methods to get RoleID and update role

**Thoughts:** I may need to create a method for default configuration when using property collector. Already had to use it twice.

**Link to work:** [Get roleId and update role](https://github.com/ivgivanov/learningJava/commit/ee394d5406c7c553d33fa3dde1f2931bffa92a11)


### Day 13: June 14, 2020

**Today's Progress:** Added possibility to create "Permission" (i.e. assing a role to object)

**Thoughts:** Getting more and mroe comfortable with the vSphere object model. Still a lot to learn though

**Link to work:** [Assign a role](https://github.com/ivgivanov/learningJava/commit/d5d55e284a232ad57357fa5a6179cf96d437ea70)


### Day 14: June 15, 2020

**Today's Progress:** Theoretical lesson, class inheritance

**Thoughts:** Things are getting real! Added some examples of class inheritance and method overrides to my simple app

**Link to work:** [Class inheritance](https://github.com/ivgivanov/learningJava/commit/0dabb7658fc722f2e9d1108b287c665485354a23)


### Day 15: June 16, 2020

**Today's Progress:** Using vCenter property collector to list names of all VMs from specified starting point

**Thoughts:** The property collector is quite complex. Slowly things are starting to make sense, but I need more practice with it

**Link to work:** [List VM names with VC PropertyCollector](https://github.com/ivgivanov/learningJava/commit/3ba2adaf1daa5d09da5fd153d4a22d7dc65e381e)


### Day 16: June 17, 2020

**Today's Progress:** Practice with vCenter TraversalSpec to traverse the object model and retreive properties for different object types

**Thoughts:** Traversing the vCenter object model is difficult to understand, but slowly making progress

**Link to work:** [Build customer traversal for VMs and Datastores](https://github.com/ivgivanov/learningJava/commit/b47eed16b8ff7e5c788bd05571087387142f298b)


### Day 17: June 18, 2020

**Today's Progress:** Theory, data types. String, StringBuilder, Primitive Wrapper classes

**Thoughts:** Having a powerful dev workstation shouln't justify wasting a resources while programming. StringBuilder class helps keeping things efficient when composing strings

**Link to work:** N/A


### Day 18: June 19, 2020

**Today's Progress:** Theory, error handling and packages

**Thoughts:** I didn't know I can use try with only finally without any catch block. I see it totally makes sense to do so when adding a throws clause to the method.

**Link to work:** N/A


### Day 19: June 20, 2020

**Today's Progress:** Started small "weekend" project

**Thoughts:** I'm going to utilize what I've learnt so far about Java and interacting with vSphere SDK and do a small project over the weekend.

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/36a8969600450c9a8872bd2870a31352634b2e57)


### Day 20: June 21, 2020

**Today's Progress:** Finished the login part and added main view to my small project

**Thoughts:** I DO NOT want to be FronEnd developer.

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/1bdb149078f8b807f761d43e0df5f03f5abab44e)


### Day 21: June 22, 2020

**Today's Progress:** Theory, Java Interface

**Thoughts:** Adds one more level of abstraction. Some parts of the lesson I had to listen twice to get the concet. Need practice

**Link to work:** N/A


### Day 22: June 23, 2020

**Today's Progress:** Finished Java Fundamentals course

**Thoughts:** I think I have sufficient theoretical knowledge to spends the next few days as purely hands-on and refer to some chapters when needed

**Link to work:** N/A


### Day 23: June 24, 2020

**Today's Progress:** Retrieved all roles and cluster names. Put them in JList object on demand

**Thoughts:** Main difficulty now is to work with java swt

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/91b8cb831af3d2fe08ef0386a6079ddac02beb69)


### Day 24: June 25, 2020

**Today's Progress:** Unsuccesfull attempt to do bigger refactoring. Added a form for new target VC connection

**Thoughts:** I may need to re-think the class implementation...

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/a84b44a9d81bbbbca34f78c36c02de32eba56a7b)


### Day 25: June 26, 2020

**Today's Progress:** Did some real refactoring today. Rewrote the way how the VC connection is handled. Touched pretty much all classes

**Thoughts:** It starts to feel like Java already, I like the way things are going

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/783579fc32b2b09f10c06e8ad8655f0b57711cf1)


### Day 26: June 27, 2020

**Today's Progress:** Used inheritance of the VcConnectionUi class to achieve different functionality for different use cases

**Thoughts:** Already used almost all of the theory I learned in the last 3 weeks

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/9effa3aee81ab86372f62622c137abdeb9d79e22)


### Day 27: June 28, 2020

**Today's Progress:** Finished the Copy vCenter Role implementation! Happy to see it fully workign now!

**Thoughts:** My main struggle is still the Swing UI. Can't wait to learn how to implement REST API endpoints!

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/a3754a873172e0eb22017be2f3f8754b5e5235a7)


### Day 28: June 29, 2020

**Today's Progress:** Created custom cluster and host classes

**Thoughts:** Moving towards implementaion of the "Check vMotion compatibility" method

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/e338986af0acebedd7669264ef134f5ccc642c7b)


### Day 29: June 30, 2020

**Today's Progress:** Collected VMs and prepared all inputs for the Check vMotion Compatibility method

**Thoughts:** I actually even executed the method, but I need now to parse the response

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/d9dfa235302adb0532c41faf5d9240a536254029)


### Day 30: July 1, 2020

**Today's Progress:** Parsed the reponse from queryVMotionCompatibilityExTask method

**Thoughts:** I can now evaluate and show the potential error if vMotion is not possible for some VM in a given cluster

**Link to work:** [Small TIN application](https://github.com/ivgivanov/tin/commit/2f6115ff7eb50ca2066121a07b3b06b31add91f3)


### Day 31: July 2, 2020

**Today's Progress:** Theoretical lesson, Java Collections

**Thoughts:** Started a short course at pluralsight covering Java Collections. Explains in depth benfits and usecases. Covered the Collection interface and List

**Link to work:** N/A


### Day 32: July 3, 2020

**Today's Progress:** Theoretical lesson, Java Collections (continued)

**Thoughts:** Breaking down Maps. It's a datastructure that it's proven to be really useful in the real world. Need more practice to get used to it

**Link to work:** N/A


### Day 33: July 4, 2020

**Today's Progress:** Hands on with small internal PoC

**Thoughts:** Decided to tackle a small internal PoC. I'll be super happy if later on this gets really implemented

**Link to work:** N/A - internal


### Day 34: July 5, 2020

**Today's Progress:** Hands on with small internal PoC

**Thoughts:** Didn't progress as planned. Found multiple ways how something doesn't work...

**Link to work:** N/A - internal


### Day 35: July 6, 2020

**Today's Progress:** Hands on with small internal PoC - came up with better data structure

**Thoughts:** With better way to represent my data everything clicked together!

**Link to work:** N/A - internal


### Day 36: July 7, 2020

**Today's Progress:** Theory, finished the Java Collections course

**Thoughts:** Today's focus was on Streams and Sets.

**Link to work:** N/A


### Day 37: July 8, 2020

**Today's Progress:** Read code for alsmot 2 hours, and then made only couple of adjustments

**Thoughts:** Getting nice inspirations reading other people's code

**Link to work:** N/A - internal


### Day 38: July 9, 2020

**Today's Progress:** Registerred at leetcode and worked on some problems there

**Thoughts:** Even though some problems are marked as 'easy' they could be quite a brain teasers

**Link to work:** N/A


### Day 39: July 10, 2020

**Today's Progress:** Theory, first steps into Spring framework

**Thoughts:** This is one of the reason I started the 100DaysOfCode challenge

**Link to work:** N/A


### Day 40: July 11, 2020

**Today's Progress:** Theory, learned about what makes the Spring framework

**Thoughts:** The course also covered an  overview of multiple Spring projects and their use-cases

**Link to work:** N/A


### Day 41: July 12, 2020

**Today's Progress:** Created my first Spring application!

**Thoughts:** It's a lot to process, but I think I'm getting the idea. The pluralsight course I'm following is quite good.

**Link to work:** https://github.com/ivgivanov/learningJava/commit/f77b7ca7624f5bfcf018a32757be74f8466ad1d4


### Day 42: July 13, 2020

**Today's Progress:** Spring scope and autowiring

**Thoughts:** Autowiring seems quite cool, but haven't fully understood it yet

**Link to work:** https://github.com/ivgivanov/learningJava/commit/ff829821fb91974e09d1dcea6303afd036c8b4b7


### Day 43: July 14, 2020

**Today's Progress:** Theory, looking into how configuration can be applied via xml

**Thoughts:** I prefer the Java configuration. For me it's easier to read and follow when it's in the code

**Link to work:** N/A


### Day 44: July 15, 2020

**Today's Progress:** Finished the Spring Fundamentals course on pluralsight

**Thoughts:** I have some basic, high level understanding of the Spring framework. At lease enough so know what questions to ask

**Link to work:** https://github.com/ivgivanov/learningJava/commit/01c3122313ee8e608c7e34b17a0d8a36c4884a06


### Day 45: July 16, 2020

**Today's Progress:** Introduction to Spring MVC

**Thoughts:** Looking forward to building my first Java web application

**Link to work:** N/A


### Day 46: July 17, 2020

**Today's Progress:** Did my first Java web app!

**Thoughts:** Following the course, I created my first web app and even a controller that prints a message. Starting to feel the power of web development

**Link to work:** https://github.com/ivgivanov/learningJava/commit/389cba5d687b24a4af0caf35840ef68b343aaf09


### Day 47: July 18, 2020

**Today's Progress:** Controllers in Spring MVC

**Thoughts:** Implemented my first get and post methods in Java! Also learned how to server static pages if needed

**Link to work:** https://github.com/ivgivanov/learningJava/commit/9cbec358890db947def2388bda6d067e0df35225


### Day 48: July 19, 2020

**Today's Progress:** Finished the Spring MVC course

**Thoughts:** One more piece of the puzzle. I'm ready to start my next personal project

**Link to work:** ### https://github.com/ivgivanov/learningJava/commit/743ad200f2e9b736315d9c612ec13578f2952ce3


### Day 49: July 20, 2020

**Today's Progress:** Started prototyping my next personal project - TIN using spring boot

**Thoughts:** Used https://start.spring.io/ to get a head start and have the shell of the app ready

**Link to work:** ### N/A


### Day 50: July 21, 2020

**Today's Progress:** Spending some time to better define the requirements and goals I want to achieve with my next app

**Thoughts:** From past experience, I always prefer to have as clear idea as possible. Then solving the coding part is easier.

**Link to work:** ### N/A


### Day 51: July 22, 2020

**Today's Progress:** Consuming REST services from JAVA

**Thoughts:** Used for the first time Spring's RestTemplate and I'm supper happy about it. Now I can offer and consume REST services!

**Link to work:** ### local commit only


### Day 52: July 23, 2020

**Today's Progress:** Used Thymeleaf templates to generate HTML pages and display them as response to a GET endpoint

**Thoughts:** I have all required pieces in order to start working on a complete app

**Link to work:** ### local commit only


### Day 53: July 24, 2020

**Today's Progress:** Got familiar with vSphere Automation SDK

**Thoughts:** Manage to connect, authenticate, retrieve list of VMs from vCenter Server and display them back in a table in thymeleaf html template. Lesson learned, didn't had apache http client and lost 30 minutes in troubleshooting.

**Link to work:** ### local commit only


### Day 54: July 25, 2020

**Today's Progress:** Managed to break my app

**Thoughts:** In the process of making it better, I broke even the existing functionality. I guess I need to go back for some more theory.

**Link to work:** ### N/A


### Day 55: July 26, 2020

**Today's Progress:** Fixed the app!

**Thoughts:** Went back to theory for some calrification on Spring beans and autowiring and fixed the issue in my app.

**Link to work:** ### local commit only


### Day 56: July 27, 2020

**Today's Progress:** Extended VM collection, externalized vSphere collector

**Thoughts:** Prepared the design to further extend with host and vCenter collection. Planned for tomorrow.

**Link to work:** ### local commit only


### Day 57: July 28, 2020

**Today's Progress:** Added collection for host and vCenter data

**Thoughts:** It was a good practice with spring boot and vsphere automation sdk.

**Link to work:** ### local commit only


### Day 58: July 29, 2020

**Today's Progress:** Laid the groundwork to prepare a new endpoint for internal use

**Thoughts:** I want to use my new skills to help other teammates in their daily tasks by addint new endpoint to existing tool

**Link to work:** ### N/A


### Day 59: July 30, 2020

**Today's Progress:** First part is ready

**Thoughts:** Spent quite some time to read existing code today. Looks quite diffrent than Hello World program

**Link to work:** ### local commit only


### Day 60: July 31, 2020

**Today's Progress:** Make a good progress today, prepared regular GetMapping to return result + another that returns json formatted object

**Thoughts:** I need to consider using pure REST endpoints and call them with javascript from the fron end. I'll achieve better UX this way

**Link to work:** ### local commit only


### Day 61: August 1, 2020

**Today's Progress:** Hit quite a few blockers today, no actual progress

**Thoughts:** Sometimes it feels quite demotivating when you spend hours and there is nothing to show

**Link to work:** ### N/A


### Day 62: August 2, 2020

**Today's Progress:** I'm almost ready to preapre a PR!

**Thoughts:** About to create a PR for some additions to an internal tool which me and my colleagues are using. I hope the review will not be devastating

**Link to work:** ### local commit only


### Day 63: August 3, 2020

**Today's Progress:** Theory, started Spring Data JPA course

**Thoughts:** This seems like a crucial part of any serious application. Today started the Spring Data JPA course on Pluralsight

**Link to work:** ### N/A


### Day 64: August 4, 2020

**Today's Progress:** Super excited! Used javascript to call my Java endpoints!

**Thoughts:** I don't plan focusing much on front-end, but being able to provide working solution (be + fe) is really cool!

**Link to work:** ### local commit only


### Day 65: August 5, 2020

**Today's Progress:** Polished my small internal project and requested review

**Thoughts:** Looking forward to get some feedback for my internal project.

**Link to work:** ### local commit only


### Day 66: August 6, 2020

**Today's Progress:** Received quite good review with just couple of suggestions for improvements which I just fixed.

**Thoughts:** It's great to receive comments from real developer. Especially when the commet is positive!

**Link to work:** ### local commit only


### Day 67: August 7, 2020

**Today's Progress:** Resumed my Spring Data JPA course

**Thoughts:** Installing and configuring Spring Data JPA

**Link to work:** ### N/A


### Day 68: August 8, 2020

**Today's Progress:** "Installing" and configuring Spring Data JPA

**Thoughts:** I have my local postgres db up and running and even queried already via JPA repostiory

**Link to work:** ### N/A


### Day 69: August 9, 2020

**Today's Progress:** Theory, Spring Data JPA Repositories

**Thoughts:** Best practices and migration methods

**Link to work:** ### local commit only


### Day 70: August 10, 2020

**Today's Progress:** Theory, Query DSL

**Thoughts:** I had great 'aha' moment today! I've been reading some code before and couldn't understand how that works. The Query DSL does so much behind the scenes!

**Link to work:** ### local commit only


### Day 71: August 11, 2020

**Today's Progress:** Theory, Query DSL - more practice with writing methods

**Thoughts:** Today I used more DSL keywords to test different queries

**Link to work:** ### local commit only


### Day 72: August 12, 2020

**Today's Progress:** Theory, Query Annotation - when Query DSL is not enough

**Thoughts:** For more complex query QueryDSL may not be sufficient. Then the @Query can be used to write the sql query

**Link to work:** ### local commit only


### Day 73: August 13, 2020

**Today's Progress:** Theory, Native SQL support

**Thoughts:** After spending quite some time with the Spring Data JPA I thin I may need some refresh and upgrade of my SQL knowledge

**Link to work:** ### local commit only


### Day 74: August 14, 2020

**Today's Progress:** Finished the Spring Data JPA course

**Thoughts:** I have lined up all hands-on weekend. I have much better understanding how modern Java apps are interacting with DBs

**Link to work:** ### N/A


### Day 75: August 15, 2020

**Today's Progress:** Added yet another internal endpoint along with UI

**Thoughts:** Spent more time than planned, but I finished it all - BE + FE!

**Link to work:** ### private repository


### Day 76: August 16, 2020

**Today's Progress:** Spend the evening improving the error handling

**Thoughts:** Something to figure out - how to print correct error message when the exception is cought in the code of some library and handled (printend to console)?

**Link to work:** ### private repository


### Day 77: August 17, 2020

**Today's Progress:** Troubleshooting deserialization of json

**Thoughts:** Of course, it worked on my machine, but doesn't work on real build... trying to identify what went worng... and why

**Link to work:** ### N/A


### Day 78: August 18, 2020

**Today's Progress:** Getting more involved in the development process at work. I wrote some tests today

**Thoughts:** It's nice to be able to implement something that helps your teammates. I'm happy that now I can actually contribute to tools used by other people!

**Link to work:** ### private repository


### Day 79: August 19, 2020

**Today's Progress:** Theory, Introduction and strucutre of Maven

**Thoughts:** Building your application is as important as the app iteslf. Understanding how Maven works can signifucantly help you manage the app lifecycle

**Link to work:** ### N/A


### Day 80: August 20, 2020

**Today's Progress:** Theory, Maven Dependencies and Repositories

**Thoughts:** The most important thing I learned today was about the SNAPSHOT versions. It basically tells maven to always pull the latest code available for that version

**Link to work:** ### N/A


### Day 81: August 21, 2020

**Today's Progress:** Finished the Maven Fundamentals course

**Thoughts:** Honestly I was expecting some more advanced functionality to be covered, but it was nice to understand the basics

**Link to work:** ### N/A


### Day 82: August 22, 2020

**Today's Progress:** Added a commit to an internal project. I do that now much more often than before

**Thoughts:** Spring in a real application is not as straight forward as in a small demo app. I need to get used to reading and finding my way easy in such cases

**Link to work:** ### Private repository


### Day 83: August 23, 2020

**Today's Progress:** Reiterating some Spring realted topics. Going over short spring boot course

**Thoughts:** Learned about the existence of Spring Boot CLI. Not planning to use it soon, but I wasn't expecting such thing would exists

**Link to work:** ### N/A


### Day 84: August 24, 2020

**Today's Progress:** Unfortunately I don't have much progress today. I sped quite some time dealing with solving conflicts after git force push

**Thoughts:** Personally, I consider that once a branch is pushed to remote, fore push can cause more problems that it solves 

**Link to work:** ### N/A


### Day 85: August 25, 2020

**Today's Progress:** Reviewing design priciples for REST services with springboot

**Thoughts:** Ability to implement REST endpoints was one of the drivers for me to start this challenge. Now that I had better understanding, I wanted to go a bit deeper into the principles that should be followed

**Link to work:** ### N/A


### Day 86: August 26, 2020

**Today's Progress:** Started working on the requirements for my last 100DaysOfCode project

**Thoughts:** Planning to utilize everything I've lerned so far... rest api controllers with spring boot, maven and of course interacting with VMware vCenter Server

**Link to work:** ### N/A only on paper


### Day 87: August 27, 2020

**Today's Progress:** Worked on internal task and found an error in the current approach that requires somebody else to look into

**Thoughts:** 30 minutes to get "in the zone" of what I'm going to do and how. About 1 hour coding and then 30 minutes of troubleshooting. At least I'm happy I found the root cause!

**Link to work:** ### Private repository


### Day 88: August 28, 2020

**Today's Progress:** Most productinve code day so far!

**Thoughts:** Did 2 or 3 implementations until I was satisfied enough with the code before sending it to review

**Link to work:** ### Private repository


### Day 89: August 29, 2020

**Today's Progress:** Back to the Spring Initializr 

**Thoughts:** Started the actual code work for my last project as part of the challenge. First, implementing only the REST controllers, will deal with UI later

**Link to work:** ### Private repository


### Day 90: August 30, 2020

**Today's Progress:** Implemented REST endpoint that returns vCenter collection object

**Thoughts:** I want to add some more infe regarding the vCenter Server, currently I have only what is part of the AboutInfo vim25 object.

**Link to work:** ### Private repository


### Day 91: August 31, 2020

**Today's Progress:** Added vCenter advanced settings and vCenter extensions to the data collection

**Thoughts:** I forgot how time consuming is to work with the property collector. Still I'm glad I made it work!

**Link to work:** ### Private repository


### Day 92: September 1, 2020

**Today's Progress:** Implemented collection for 'config' and 'hardware' for ESXi hosts

**Thoughts:** Even though I'm happy with the result so far, I think it can be done better

**Link to work:** ### Private repository


### Day 93: September 2, 2020

**Today's Progress:** Implemented collection for vCenter release names from external source

**Thoughts:** As the project gets bigger, it's getting harder and harder to maintain and keep it in my head. I guess I need better separation and working on one thing at a time

**Link to work:** ### Private repository


### Day 94: September 3, 2020

**Today's Progress:** Prepred new classes to for transformed data and started working on 'vSphere Processor' that will do the needed computation

**Thoughts:** I'll have a 'code review' with a colleague at work tomorrow to get second opition on the general architecture

**Link to work:** ### Private repository


### Day 95: September 4, 2020

**Today's Progress:** Architecture review with a colleague

**Thoughts:** I needed to hear external opinion on the way I do thigs and also some general guidence on building the UI

**Link to work:** ### N/A
