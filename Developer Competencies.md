

### 1. FRONT END DEVELOPMENT HTML & CSS

*Demonstrated proficiency here: https://codepen.io/econno11y/pen/gRPYNP?editors=1111  and in Bootcamp HTML & CSS unit*

- [x] Solid Knowledge of common tag types and how to implement them

      Document Structure	

      Content Tags

      Semantic Tags - introduced in HTML5 - designed to indicate function of content blocks

      Empty Tags

      Tables


- [x] Understands how the browser handles conflicting styles


- [x] Understands how the DOM is laid out and is structured - *The DOM is an API that allows programmers to manipulate elements on a webpage in a CRUD-like. The DOM treats elements as objects and interfaces that exist in a tree-like hierarchy* 


- [x] Understands the difference between content & styling


- [x] Understands that different browsers render and interpret things slightly differently and the need to test on commonly used platforms - *performed cross-platform testing and corrected peoplegrid rendering issues on different browsers for HVA*

##### Bootstrap

- [x] Knowledge of Bootstrap properties and design principles


- [x] Understands grid concept & how to manipulate it


- [x] Can install either by CDN or local file


​

### 2. MIDDLEWARE DEVELOPMENT

- [x] ##### JavaScript 

      *Demonstrated proficiency here: https://github.com/econno11ee/JavaScript-Library, https://github.com/econno11ee/Games-App, and https://github.com/econno11ee/MvcMovieApp*


- [x] Solid understanding of HTML & CSS


- [x] Understanding of browser runtime & where to inject scripts


- [x] Understanding of dynamic typing and how it makes using the language quick and easy - *more concise, better for runtime debugging in the console, more suited to prototyping*


- [x] Understanding of Document Object Model


- [x] Knowledge of JSON and working with JSON objects


- [x] Knowledge on how to traverse the DOM for element handles


- [x] Know how to structure native JavaScript classes (OOP, Pub/Sub) using prototype or object literal statements - *See 4 ways of creating objects in JS:*

      Function constructor:

      ```
      var Obj = function(name) {
        this.name = name
      }
      var c = new Obj("hello"); 
      ```

      Function constructor + prototype:

      ```
      function myObj(){};
      myObj.prototype.name = "hello";
      var k = new myObj();
      ```

      Object literal:

      ```
      var contactDetails = {name: "Erin", phone number: "602-284-1864", email: "econnolly@techtonicgroup.com"}
      ```

      Object.create method:

      ```
      var a = Object.create(null);
      ```

      ​

##### AJAX

*Most demonstrated in MvcMovieApp, using Angular.js factories and ng-controllers to create, read, update, and delete.  Made reference to help me understand factory pattern in depth: https://docs.google.com/spreadsheets/d/18fE5JpUMEyP5uy91cDl53Ee56nHjjnlMnxl5BUuVgYM/edit?usp=sharing*

*Additionally, created JavaScript API Client for **Misty Robot*** 

- [x] Understanding of asynchronous concepts and implications such as callbacks 


- [x] Ability to implement AJAX calls in a project


- [x] Understanding the difference between HTTP methods (get, post, load, etc) and their uses


- [x] Understanding of error handling and promises

##### HTTP Methods

- [x] Understands difference between HTTP Methods POST, GET, and PUT


- [x] Understands difference between AJAX and HTTP Methods - **AJAX, or Asynchronous JavaScript and XML, is a jQuery wrapper that implements the  DOM's built in XMLHttpRequest Object, which enables asynchronous interaction with the server (ie the page can be updated or data sent to the server without reloading).  HTTP methods indicate the action to be performed on the data in the server, whether it be get, put, post, delete, patch, etc.* * 

##### jQuery

- [x] Understands where to inject script files and how to make it function


- [x] Understanding of basic operations & functions


- [x] Able to add localized scripts

### 3. DATABASE DEVELOPMENT



- [x] Understands the difference between a relational database and document based database

##### MongoDB

- Knowledge of basic installation of MongoDB and C Driver, JSON, schema design, querying, insertion of data, indexing & working with C# driver
- Able to build a MongoDB-based app
- Can Write repository methods that perform basic CRUD operations
- Able to interact with MongoDB documents, & database collections using either RoboMongo or MongoVUE

**SQL**

- [x] Can create tables, columns & stored procedures in a timely manner
      - *Demonstrated proficiency creating tables, adding columns here: Demonstrated proficiency here:  https://www.codecademy.com/cloudSurfer22422*
- [x] Can take business logic and turn it into a database design


- [x] Knowledge of how to make a primary key or foreign key & how all the relationships work


- [x] Can create reliable, tested queries that efficiently return data


- [x] Comfortable with CLI and/or GUI tools


- [x] Can write repository methods that perform basic CRUD operations
      - *Demonstrated in MVCMovie project: https://github.com/econno11ee/MvcMovieApp*

### 4. BACKEND DEVELOPMENT

##### C# ####

- [x] Solid understanding of object-oriented programming in C#


- [x] Knowledge of Visual Studio, can identify Solution Explorer, the debugging menu, the build, run, and clean functions & unit testing


- [x] Understanding all common modifiers (static, abstract, etc) & can build and implement classes correctly
      - *Demonstrated in MVCMovie project:* https://github.com/econno11ee/MvcMovieApp


- [x] Understanding namespaces & how to import dependencies


- [x] Knowledge on how to use model binding
      - *Demonstrated in MVCMovie project:* https://github.com/econno11ee/MvcMovieApp


- [x] Knowledge of serialization and deserialization with JSON
      - *Demonstrated through development of RESTful API for Techtonic Client*


- [x] Understanding the difference between pass by reference and pass by value

##### Ruby on Rails

- Understand how an application accesses stored data, and how to reduce load by steamlining data requests
- Strong knowledge of gems, both to locate and install simple add-ons to their application, and create their own custom gems
- Knowledge of unit testing and Spec to produce clean, tested code

##### PHP

- Solid understanding how to use forms
- Understaning of how to assign variables into HTML elements
- Before writing a function or class, be able to utilize existing functions or classes

##### APIs

- [x] Create modern, REST API's from existing information assets 


- [ ] Integrates and orchestrates enterprise services across silos


- [ ] Secure and authorize information assets exposed via APIs


- [x] Understanding C.R.U.D

### 5. CODING STANDARDS

##### Code Formatting

- [x] While going through code, check the code formatting to improve readability and ensure there are no blockers

##### Architecture

- [x] Separation of Concerns followed


- [x] Split into respective files (HTML, JavaScript and CSS)


- [x] Split into multiple layers and tiers as per requirements (Presentation, Business, and Data Layers)


- [x] Code is in sync with existing code patterns/technologies


- [x] Design patterns: Use appropriate design pattern (if if helps), after completely understanding the problem and context

##### Coding Best Practices

- [x] No hard coding, use constants/configuration values


- [x] Group similar values under an enumeration (enum)


- [x] Comments - Do not write comments for what you are doing, instead write comments on why you are doing. Specify about any hacks workaround and temporary fixes. Additionally mention pending tasks in your to-do comments, which can be tracked easily


- [x] Avoid multiple if/else blocks


- [x] Use framework features, wherever possible instead of writing custom code

##### Non Functional Requirements

- [x] a.) Maintainability (Supportability) - The application should require the least amount of effort to support in the near future. It should be easy to identify, fix, and detect.

      ​	Readability: Code should be self-explanatory. Get a feel of story reading. whlile going through code. Use appropriate name for variables, functions and classes. If you are taking more time to understand  the code, then either code needs refactoring or at least comments have to be written to make it clear.

      ​	Testability: The code should be easy to test. Refactor into separate function (if required). Use interfaces while talking to other layers, as interfaces can be mocked easily. Try to avoid static functions, singleton classes as these are not easily testable by mocks.

      ​	Debuggability: Provide support to log the flow of control, paramater data and exception details to find the root cause easily. if you are using Log4Net like component then add support for database logging also as querying the log table is easy.

      ​	Configurability: Keep the configurable values in place (XML file, database table) so that no code changes are required, if the data is changed frequently.


- [x] b.) Reusability

      ​	DRY (Do not Repeat Yourself) principle: The same code should not be repeated more than twice

      ​	Consider reusable services, functions and components

      ​	Consider generic functions and classes


- [ ] c.) Reliability - Exception handling and cleanup (dispose) resources.



- [ ] d.) Extensibility - Easy to add enhancements with minimal changes to existing code. One component should be easily replaceable by a better component.



- [ ] e.) Security - Authentication, authorization, input data validation against security threats such as SQL injections and Cross Site Scripting (XSS), encrypting the sensitive data (passwords, credit card information etc.)



- [ ] f.) Performance 

      Use a data type that best suits the needs such as StringBuilder, generic collection classes

      Lazy loading asynchronous and parallel processing

      Caching and session/application data

- [ ] g.) Scalability - Consider if it supports a large user base/data? Can this be deployed into web farms?



- [ ] h.) Usability - Put yourself in the shoes of a end-user and ascertain, if the user interface/API is easy to understand and use. If you are not convinced with the user interface design, then start discussing your ideas with the business analyst


##### Object-Oriented Analysis and Design (OOAD) Principles

- [x] Single Responsibility Principle (SRS): Do not place more than one responsibility into a single class of function, refactor into separate classes and functions


- [x] Open Closed Principle: While adding new functionality, existing code should not be modified. New functionality should be written in new classes and functions


- [x] Liskov substitutability principle: The child class should not change the behavior (meaning) of the parent class. The child classcan be used as a substitute for a base class.
      - Completed Interface Polygons class


- [x] Interface segregation: Do not create lengthy interfaces, instead split them into smaller interfaces based on the functionality. The interface should not contain any dependencies (paramaters), which are not require for the expected functionality
      - Demonstrated in MVCMovie project: https://github.com/econno11ee/MvcMovieApp


- [x] Dependency Injection: Do not hardcode the dependencies, instead inject them
      - *Exposure to these concepts in MVVM at Techtonic Group client*

### 6. GIT

- [x] Solid knowledge of how source control works why it's important using either CLI or GUI tools


- [x] Know the basic commands: clone, push, fetch, pull, commit


- [x] Understand what remotes are


- [x] Understand how to hide, add, remove, and stash files


- [x] Understand how to branch and merge


- [x] Understand how to resolve merge conflicts


- [x] Can reliably commit based on project needs, with communication to the rest of the team


- [x] Uses relevant and important information in commit notes


- [ ] Understands differences between HTTPS SSH validation
