# animals-part2

Search...
Umuzi Remote work
1. Syllabus
2. Topics
3. Workshops
4. Projects
Android with Kotlin Projects
Constraint Layout Using Layout Editor
Data Binding Basics
Linear layout using the Layout Editor
User Activity
Androids
Incremental Counter
Information Page
Angular Tutorial
Assertive programming kata
Bootcamp Writing Assignment
Build your first personal website
Capstone project
Gmail Text Scraper
Pair Stairs
Spaced Repitition machine to help you remember what you read
The Quizmaster
build a Chrome Extension that measures time spent in meetings
Consume Github API
DAGs with Airflow
Data-science-specifics
MEDIUM: Cross-validation & Simple Linear Regression
Dashboard Assignment
EASY: Google Data Studio Assignment
HARD: Live Dashboard Assignment
EASY: Plotly Dashboard Assignment
HARD: Webscraping and Live Dashboard Assignment
Data Modelling Challenges
HARD: Network Intrusion
Data Visualisation Projects
MEDIUM: Evolution of Linux Visualisation
MEDIUM: Financial Services Use in Tanzania
MEDIUM: Data Wrangling
MEDIUM: Decision Trees
Introduction to Jupyter Notebooks
MEDIUM: K-Means Clustering Assignment
Logistic regression
MEDIUM: Predict breast cancer
MEDIUM: Predict credit card approvals
MEDIUM: Multivariate Linear Regression
MEDIUM: Natural language processing
MEDIUM: OOP for data science
MEDIUM: Statistical Thinking
Webscraping Assignment
Distributed workloads with ZeroMQ
Email random inspirational quote
Expose a simple REST api for your game
ExpressJS
Game of life: Angular elements
Git Basic Exercises
How to submit your project
Java Projects
Consume own api using curl
File IO + Logging + Errors
Introduction to Spring Boot
Introduction to Spring Boot - part 1
Introduction to Spring Boot - part 2
Introduction to Spring Boot - part 3
Introduction to Spring Boot - part 4
Introduction to Spring Infrastructure
Introduction to Spring Infrastructure part 1
Introduction to Spring Infrastructure part 2
Introduction to Spring Infrastructure part 3
Java Generics
Java collections
Java data structures
SQL Extended
Level 1 programming katas
Linux challenges
Advanced Linux challenges
Beginner Linux challenges
Memory Game: rebuild using a modern web frontend framework
Memory game in vanilla js
Memory game using Angular Material
Nodejs Challenges
1: Node & File IO
2 (alt): Node & mongoDB assignment
3: Express, forms and templates
4: Expose a JSON API
Add a little Ajax
Node & SQL assignment
OOP Excercises
Animals
Animals Part 1. OOP basics
Animals Part 2. Adding Tests
Bank Accounts
Dice
Person
Pre bootcamp challenges
Python projects
Database migrations with SQLAlchemy
Django - exposing a REST api with a real database
Getting to know Python
Python and Kafka
Python and MongoDB
Python and Spark
create a REST api to interact with actual database
expose a simple JSON rest api
RabbitMQ
SQL
Semitone Challenge
1. semitone difference - basic algorithm
1. Make a simple GUI
3. Advanced algorithm
4. A gui that is more...awesome
Add Redux to your semitone game
Test Driven Development
Password Checker
Add logging to password checker
password-checker
MEDIUM: Resturaunt menu system
EASY: factorials
MEDIUM: lots and lots of tdd katas
MEDIUM: recursive search
EASY: simple-calculator part 1
MEDIUM: simple-calculator part 2
string-calculator
HARD: ten-pin bowling scoring system
Validating user input for web
consuming APIs with the requests module
iOS Mobile
Codable, File Manager, URL
Drag and Drop, Multithreading and Delegation
More Swift, Gestures and Animations
Multithreading Layout and Other Functionality - Animated Set
Multithreading Layout and Other Functionality - Graphical Set
Swift and More
5. Katas
6. Department Processes
Code Review Feedback Notes
Contact
Credits
How to Contribute
Online Learning and bootcamp
More
 Github repo
 Credits
  
 Edit this page Umuzi Tech Department > Projects > OOP Excercises > Animals > Animals Part 2. Adding Tests
ANIMALS PART 2. ADDING TESTS
Story points	3
Tags	unit-testing oop
Hard Prerequisites	
PROJECTS: Animals Part 1. OOP basics
To submit this project follow the link below: TILDE
In this challenge you will update your current Animals project and add unit tests to the project

Project structure
Java
The code you push to git should have the following structure:

├── build.gradle
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradlew
├── gradlew.bat
├── settings.gradle
└── src
    ├── main
    |   └── java
    |       ├── Animal.java       <-------- names are important
    |       ├── Cat.java          <-------- names are important
    |       ├── Dog.java          <-------- names are important
    |       ├── Home.java         <-------- names are important
    |       └── MainProgram.java  <-------- names are important
    └── test
        └── java
            ├── CatTest.java   <-------- names are important
            └── DogTest.java   <-------- names are important
            ... other logical things
Please refer to the following to find out more: TOPICS: [TODO] Java project submission requirements

Instructions
You’ll be using JUnit.

Create a class called AnimalTests
Update Animal super class eats() function to return a String, “Food”.
Update Dog class sounds() function to return a String, “Bark”.
Update Cat class sounds() function to return a String, “Meow”.
// Java

Dog dog = new Dog()

dog.eats()    // -> 'Food'
dog.sounds() // -> 'Barks'

Cat cat = new Cat()

cat.eat()    // -> 'Food'
cat.sounds() // -> 'Meow'
Now let’s add our first JUnit test to our AnimalTests. The class should have the following methods TestDogSound(), TestDogEats(), TestCatSound() and TestCatEats().Each method should have the @Test tag placed above it. The tests should work as follows.

// Java

//Dog Tests
Test -> Does dog eat Food should Pass
Test -> Does dog eat food should Fail

//Cat Tests
Cat cat = new Cat();
Test -> Does cat Barkark should Fail
Test -> Does cat Meow should Pass
Test -> Does cat eat meat should Fail
Test -> Does cat eat Food should Pass
Test -> Does cat eat food should Fail

Up for a Challenge?
This section is not compulsory. If you do this we’ll think you’re cool.

Add some functionality to TestDog() and TestCat() so that the tests aren’t case sensitive

eg:

Test -> Does dog eat Food -> Pass
Test -> Does dog eat food -> Pass
RAW CONTENT URL
