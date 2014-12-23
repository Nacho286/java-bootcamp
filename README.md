# Java BootCamp base folders layout

Please, use this repository as a base for you training phase. The idea is to
fork this project so everyone use the same folder structure for the
exercises.

It's extremelly important to keep the key points easy to be verified by
the reviewers, so **don't mix the key points with the rest of the
exercises**


# Material

#JAVA Boot Camp

###Are you ready for it?
  
####Index

1. [Objective](#objective)

2. [Who Should Attend](#who-should-attend)

3. [Duration](#duration)

4. [Technical Assistance](#technical-assistance)

5. [Performance Measurement](#performance-measurement)

6. [Handling advanced Developers](#handling-advanced-developers)

7. [Materials](#materials)

8. [General Guidelines](#general-guidelines)

9. [Proposed Test Applications](#proposed-test-applications)

10. [Learning Days](#learning-days)

    * [Topic 0: Introduction to Object Oriented Programming Concepts (OOP)](#topic-0-introduction-to-object-oriented-programming-concepts-1-day)

    * [Topic 1: Design Patterns](#topic-1-maven-2-days)

    * [Topic 2: Maven](#topic-2-maven-1-day)

    * [Topic 3: Test Driven Development](#topic-3-tdd-3-days)

    * [Topic 4: Services](#topic-4-services-4-days)

    * [Topic 5: SQL - MySql](#topic-5-sql-mySql-1-day)

    * [Topic 6: Sprint Core](#topic-6-sprint-core-3-days)

    * [Topic 7: Hibernate](#topic-7-hibernate-1-day)
  
    * [Topic 8: Spring Data & MongoDB](#topic-8-sprint-data--mongoDB-1-day)

11. [Your First Project Starts Now!](#bookmark=id.605681dc8138)

###Objective

This course teaches the basics of Java development applications.

→ [index](#index)

###Who Should Attend

The training will start at a low level and does not require in depth knowledge of the platform in question. Desirable participant profile: trainees and outside Globant candidates. A basic knowledge on OOP is desired, though.

→ [index](#index)

###Duration

Four weeks total.

Three weeks for guided learning and one week for app development. 

→ [index](#index)

###Technical Assistance

You can contact other bootcamp participants or any available tutor if you need technical assistance. We will create one chat for boot camp members only, and another one for boot camp members and tutors when boot camp starts.

###Performance Measurement

1. Code review after each practice and sprint

2. Checkpoint completion after Learning stage with your assigned tutor

→ [index](#index)


###Handling Advanced Developers

Developers that move faster than average can go ahead and complete as much exercises as wanted. 

→ [index](#index)

###Materials

1. Install [Java SDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html).

2. The IDE to use is [Eclipse for Java Developers](http://www.eclipse.org/downloads/).

3. Skype Account + headset (audio calls)

4. Create your own [GitHub](https://github.com/) account. Follow this [guideline](https://help.github.com/articles/set-up-git) to setup your account. Also you can read further about Git in [Try Git](https://try.github.io/levels/1/challenges/1)

5. Fork this repo https://github.com/juanpablopizarro/java-bootcamp to use as a base to host the project code.

→ [index](#index)

 

###General Guidelines

The boot camp is organized in the following way:

1. The first three weeks will be used for intensive self learning. Each topic will have reading and practices parts. Tutors will be available to answer technical questions on a given chat room. 

2. The next week will be used to develop an application following a life process.

3. The project manager will coordinate learning days encouraging team communication in daily meetings.

4. The project manager will gather information regarding individual progress so we can look for alternative assistance where needed.

5. The project manager will lead the boot camp sprints as if it were a real project using SCRUM agile methodology.

6. Two boot camp chats will be created for feedback and technical assistance:

    1. Bootcamp HTML - ALL
Every person participating in the bootcamp is present here (students, tutors and PMs). Here is the place to ask for technical assistance!

    2. Bootcamp HTML - Assistants
Here you will reach just your boot camp fellows for asking question sharing knowledge.

7. Team play is encouraged but the work will be evaluated per person.

8. Sprint duration will be 1 week.

9. The instructions will be vague as they generally are in real life projects. You must look for support and guidance from your PM, teammates and tutors.

10. All code and documentation must be in English.

11. Code must adhere to Globant’s UI [Java coding guidelines](https://github.com/globant-ui/html-style-guide). (update url)

→ [index](#index)

###Proposed Test Applications

The test application will consist in TBD.

###Learning Days###

Each day you will grab the fundamentals of the key building blocks for usual Java applications.

On each learning day you will have to:

1. ####Read:####
We will provide you with documentation related with current sprint content so you can have a background reference, guide and examples to complete the following practice.

2. ####Practice:####
You will implement the previously gathered knowledge in simple coding activities.
Most important task numbers are listed in the "*Key Points*" section for each day and they should get most of your attention; if you feel you don’t have enough time to complete all tasks, start with these ones when possible.

3. ####Commit:####
You will commit all your code on a daily basis, when you finish your practice.

### Introduction

TBD
[JVM](http://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=392:la-maquina-virtual-java-jvm-o-java-virtual-machine-compilador-e-interprete-bytecode-cu00611b&catid=68:curso-aprender-programacion-java-desde-cero&Itemid=188)

####Topic 0: Introduction to Object Oriented Programming Concepts (1 day)####

#####Reading:#####

1. Beginners: Java Concepts [basic tutorial](http://docs.oracle.com/javase/tutorial/java/concepts/) (in case you need it!)

2. Beginners: Have fun with [Introduction to Java Programming](http://www.ntu.edu.sg/home/ehchua/programming/java/J1a_Introduction.html). 

3. Explore [Design Patterns](http://www.avajava.com/tutorials/categories/design-patterns)

#####Extra documentation:#####

* [Design Patterns Card](http://www.mcdonaldland.info/files/designpatterns/designpatternscard.pdf)

* [Design Patterns CD](http://www.saeedsh.com/resources/Design%20Patterns.pdf)

#####Practice:#####

1. [OPP Exercises](http://www.ntu.edu.sg/home/ehchua/programming/java/J3f_OOPExercises.html)

#####Key Points:#####

TBD

#####Commit:#####

Commit your practice code.

→ [index](#index)


####Topic 1: Design Patterns (2 days)####

#####Reading:#####

1. [Design Patterns CD](http://www.saeedsh.com/resources/Design%20Patterns.pdf)

2. Explore [Design Patterns](http://www.avajava.com/tutorials/categories/design-patterns)

#####Extra documentation:#####

* [Design Patterns Card](http://www.mcdonaldland.info/files/designpatterns/designpatternscard.pdf)

* [Refactoring to Patterns Catalog](http://www.industriallogic.com/xp/refactoring/catalog.html)

#####Practice:#####

1. Create a ShoppingCart where a user can buy different items and then decide how to pay them:
 
     * by Credit Card: where a Name and a Credit Number is required.

     * by Paypal: where an email and a password is needed.

     * Cash: no information is required.

2. Add the following discount depending on the payment type

     * 10% by Credit Card.

     * The cheapest item is for free when the user pay by Paypal.

     * 90% of the most expensive item is free if the user pays by Cash.

3. Create a counter to provide unique sequential numbers and use it to set an identification to each payment transaction.

4. Add functionality to display information about the list of items. The item should be displayed as:

     * Item Name ....... $ price

5. Add an offer that includes other individual items or other offers. Take into account that when an offer is displayed, it should say:


     * Offer Name ....... $ price

       - Item Name ...... $ price

6. Add a mailist List where the market manager is notified when:
    
     * A new item/offer is added

     * A price is changed

     * A new transaction was made

7. Audio Player: Modelate an application for listening music. You can play, stop and pause tracks.

#####Key Points:#####

1, 2, 3, 4, 5, 6, 7

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 2: Maven (1 day)####

#####Reading:#####

1. [What is Maven?](http://maven.apache.org/what-is-maven.html)

2. Have fun with [Maven in 5 minutes](http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html). 

3. Explore [Maven build life cycles phases and goals](http://tutorials.jenkov.com/maven/maven-tutorial.html#maven-build-life-cycles-phases-and-goals)

4. [Maven life cycle](http://books.sonatype.com/mvnref-book/reference/pom-relationships-sect-project-relationships.html)

5. Maven: [best practices](http://books.sonatype.com/mvnref-book/reference/pom-relationships-sect-pom-best-practice.html)

#####Practice:#####

(It is assumed that Maven is already installed and working. I think it is not needed as an excercise to install maven locally).

1. Create a simple Maven project:
   - Here, the idea is to use the Maven Archetype plugin from the command line. Run the archetype:generate goal, selecting default archetype suggested by pressing "Enter". (Falta indicar el creado de una clase sencilla del estilo "Hello World" y su correspondiente clases de test para asi pasar al pto 2.)
2. Building a Simple Project:
   - Create, compile, test, and install the Maven project created on the previous point. To prove that this program works, run it from the command line.
3. Playing with POM (different alternatives to achieve goals).
4. Customizing a Maven Project
   Expand the project created on point 2. The idea is to start playing with adding some dependencies, adding some source code, and customizing the project to suit specific needs. 
5. A Simple Web Application  (To be discussed. Not really sure if this will take place).
6. A Multi-module Project.
   Create a multi-module project that combines work done on previous points (2 and 5). The idea when completing this point is to be able to use Maven to develop complex, multi-module projects.
7. Optimizing and Refactoring POMs.
   Need entirely sure what to include here. Probably start working with specific profiles.

#####Key Points:#####

TBD

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 3: Test Driven Development (1 day)####

#####Reading:#####

1. Watch the following videos:

   - [Test-driven development tutorial](https://www.youtube.com/watch?v=QCif_-r8eK4)
   - [Let's Play TDD #1](https://www.youtube.com/watch?v=f3G7gu1IHws)
   - [Let's Play TDD #2](https://www.youtube.com/watch?v=1-sBRRWBxSg)

2. [Test Driven Development](http://www.jamesshore.com/Agile-Book/test_driven_development.html)

3. Have fun with [Test Driven Development in Java using Eclipse](https://www.youtube.com/watch?v=OluA0uJP9ts). 

#####Practice:#####

1. Convert an amount on a check to appropiate text. For example:
  * 2523.04 --> Two thousand five hundred twenty-three and 04/100 dollars

2. Develop a word-wrapping algorithm, which is given a string and a row-length, returns a list of word-wrapped rows. For example:
  * If the row-length is 60 and the input string is 30, the result is just the input string
  * If the row-length is 7 and the input string is "Hello Word!", the result should be: "Hello", "Word!"
  * If the row-length is 3 and the input string is "a b c d e f", the result should be "a b", "c d", "e f"
  * If the row-length is 5 and the input string is "Excelent", the result should be "Excel", "ent"

3. Use TDD to grow the 'Recent file list' behaviour. Some examples of this behaviour is:
  * When the program is run for the first time, the list is empty.
  * When a file is opened, it is added to the recent file list.
  * If an opened file already exists in the recent file list, it is bumped to the top, not duplicated in the list.
  *If the recent file list gets full (typical number of items is 15), the oldest item is removed when a new item is added.

4. Create a Roman Number conversion (both ways, either int to Roman or Roman to int). All rules can be found on wikipedia: [Roman numerals](http://en.wikipedia.org/wiki/Roman_numerals).

5. American Soundex: This algorithm encodes words using a phonetic algorithm that promotes convergence of similar-sounding words. For more information about algorithm please read [American Soundex](http://en.wikipedia.org/wiki/Soundex#American_Soundex). Create a function to return the proper soundex code.

6. Using TDD techniques such as mocking, faking and stubs, try to develop your own blog software featuring:
  * Post new entry
  * Delete existing entry
  * Update existing entry
  * Show 10 most recent entries
  * Tag an entry
  * Show all tags
  * Show blog entry with a certain tag
  * And so on...

#####Key Points:#####

1,2,3,4

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 4: Services (4 days)####

#####Reading:#####

   - [How to create services in Java](http://www.makinggoodsoftware.com/2009/11/17/how-to-create-services-in-java/)
   - [How to design a good API and why it matters](https://www.youtube.com/watch?v=aAb7hSCtvGw)
   - [Spring boot - rest services guide](http://spring.io/guides/tutorials/bookmarks/)

#####Practice:#####

1. Create a shopping cart API spec
2. Implement the previous shopping cart using spring 4 & TDD.
3. Document endpoints
4. Design a UserService for CRUD operations.
5. Implement and document previous UserService.
6. Add a uploadPhoto to the UserService
7. Add friends and likes (photos) to previous UserService.

Note: you can choose any endpoint documentation standard. As an example you can use the [twitter format](https://dev.twitter.com/rest/reference/get/users/lookup)

Note 2: Do not implement JPA or ORM. Services should return in memory data only.

#####Key Points:#####

2,4,7

#####Commit:#####

Commit your practice code.

→ [index](#index)


####Topic 5: SQL - MySql (1 day)####

#####Reading:#####
   - [MySql basis](http://www.vogella.com/tutorials/MySQL/article.html)
   - [Jdbc basis](http://www.vogella.com/tutorials/MySQLJava/article.html#jdbc)
   - [Optimizaciones en MySql](http://www.arsys.info/programacion/bases-de-datos/como-optimizar-bases-de-datos-mysql/)


#####Practice:#####

1. Create a database named 'high-school' and modelate:
 
   - Student: first name, last name, registration number, date of birth)
   - Teacher: first name, last name, date of birth)
   - Course: name, assigned teacher, hours by week, schedule time (they can be dictated several times during the week)

   Notes:
   - An student can assist several courses during the same year.
   - A teacher can be assigned to several courses.
   - For each course, each student has 3 partial notes and a final note.

2. Create all relationship that you think they are required
3. Insert information for 3 teachers, 5 courses and 20 students per course
4. List students and teachers for a given course. The output format should be:

        Course: <course-name>
        Teacher: <last-name>, <first-name>
        Students:
          <last-name>, <first-name> (ordered by alphabetically by last name)

5. List final course notes for a given student (the input could be last name or the registration number). They should be ordered by highest notes and course name)
6. Percentage of students that passed/failed a given course.
7. For a given teacher, list the timeline for each course that he is assigned to (ordered by date), and the course name. The format should be:

        Teacher: <last-name>, <first-name>
        Schedule:
          Monday 09:00 - 11:00: <course-name>
          Monday 15:00 - 17:30: <course-name>
          Friday 08:45 - 10:40: <course-name>

8. Identify and Optimize all queries
9. Create a table for students that have more than 1 partial note with a value less than 7. The table should contain the following information:
    * Student name
    * Course name
    * Average Note
10. Add a new column to the previous table (assigned teacher) and update it with the proper information.
11. Delete the oldest teacher (courses assigned to her should be empty).

#####Key Points:#####

1,2,3,4,5,8

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 6: Sprint Core (1 day)####

#####Reading:#####

   - [Overview](http://docs.spring.io/spring/docs/4.1.4.BUILD-SNAPSHOT/spring-framework-reference/htmlsingle/#overview)
   - [Quick guide](http://www.tutorialspoint.com/spring/spring_quick_guide.htm)
   - [Spring boot](http://docs.spring.io/spring-boot/docs/1.2.1.BUILD-SNAPSHOT/reference/htmlsingle/) up to point III (included)

#####Practice:#####

TBD

#####Key Points:#####

TBD

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 7: ORM (1 day)####

#####Reading:#####
1. [Spring ORM integration](http://docs.spring.io/spring/docs/current/spring-framework-reference/html/orm.html)
2. Spring Boot and [JPA integration](http://spring.io/guides/gs/accessing-data-jpa/)

#####Practice:#####

1. Configure Spring ORM to connect to the DB created on Topic 5.
2. Implement JPA objects for the entities you created on Topic 5.
3. Create one or more DAO or repository with methods to:
    - Store a student, teacher and course.
    - Fetch all students, fetch all teachers, fetch all courses.
4. Create a method to fetch all courses of a given student.
5. Create a method to fetch all students of a given course.

#####Key Points:#####

TBD

#####Commit:#####

Commit your practice code.

→ [index](#index)



####Topic 8: Spring Data & MongoDB (1 day)####

#####Reading:#####

TBD

#####Practice:#####

TBD

#####Key Points:#####

TBD

#####Commit:#####

Commit your practice code.

→ [index](#index)



Thanks for reading!
