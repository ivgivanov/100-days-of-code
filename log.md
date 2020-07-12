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
