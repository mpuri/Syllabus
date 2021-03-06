# NYU CS9053 - Template

## Introduction to Java

### Instructor

Brian Langel

| email | phone | office | hours |
| :---: | :---: | ------ | ----- |
| brian@dash.by | (712) 266 3255 | | |

### Course Description
* An introduction to the Java programming language. See [Lectures](#lectures) for topics covered.
* This is *not* an introduction to programming, data structures, algorithms or other computer science topics. It is expected that the student have experience in at least one programming language prior to taking this course. This course will cover Java specific solutions to common algorithms, data structures, concurrency problems and other computer science related topics. Although not a strict prerequisite, it is assumed that the student have taken undergraduate level courses in data structures and algorithms.   
* The Java ecosystem is large and many topics will not be covered; including, _Java 8_, _JDBC_, _EJB_, _Swing_ (although some limited usage might be included), _JSF_, _JNI_, and _Java EE_ topics

### Textbook
* Core Java, volume one, 9th ed.; Cay Horstmann and Gary Cornell. __ISBN-13 978-0137081899__

### Recommended Textbooks
Although these two books are not required they will be referenced extensively throughout the course. If you plan on programming in Java I highly recommend purchasing these books.

* Java Concurrency in Practice; Brian Goetz et al. __ISBN-13 978-0321349606__
* Effective Java, 2nd ed.; Joshua Bloch __ISBN-13 978-0321356680__

### Purpose
The goal of this course is to teach you a pragmatic understanding of the Java programming language. It will avoid the esoteric, the rarely used and the vestigial aspects of the language and the Java ecosystem at large (e.g., _Java EE_)     

### How to Succeed
* Attend lectures
    - Many topics / examples / questions which will appear on the exams and in the homework will be covered in lectures but not necessarily within the textbook. 
* Participate in lecture by asking questions
    - Ask questions! It's the quickest way to learn. All questions will be answered and respected. If you do not feel comfortable asking questions (i.e., shy, feel inarticulate, etc) I still would like you to participate. To make this easier for you I've thought a lot about this and feel I have a good solution (see [Participation](#participation)).
* Study the language
    - Don't simply read the textbook / attend lectures. Study the concepts and ideas to get a firm understanding of them and why they are the way they are in the Java language in particular. For example, if you _know_ about Hashtables don't assume you already understand them in Java. There are peculiarities to every language and learning those for Java is part of this course. 
* Program with the language
    - Studying the language is not sufficient for Java or any other programming language. To actually become proficient in a language you must use it and use it extensively.
* Read others' code
    - In addition to studying and programming with a language, it is extremely important to read others' code in that language when learning it. There are common paradigms and principals that others have developed over time by virtual of working within the confines of the Java language. You can learn these patterns by reading others' code.  Github is an amazing resource for this.

### Lectures
Tentative schedule

| Lecture | Date | Topic | Reading (chapters) |
| :-----: | :--: | ----- | ------------------ |
| 1 | 9/3 | Introduction / Basics | 1 & 2 |
| 2 | 9/10 | Procedural Java | 3 |
| 3 | 9/17 | Objects | 4 |
| 4 | 9/24 | Inheritance | 5 |
| 5 | 10/1 | Interfaces / Nested & Inner Classes | 6 |
| 6 | 10/8 | __Midterm 1__ (see [Exams](#exams)) <br/> Exceptions / Debugging / Annotations & Regular Expressions | 11 & [supplemental]() |
| 7 | 10/15 | Generics | 12 |
| 8 | 10/22 | Collections | 13 |
| 9 | 10/29 | __Midterm 2__ (see [Exams](#exams)) | |
| 10 | 11/5 | Concurrency | 14 & Goetz |
| 11 | 11/12 | Concurrency | 14 |
| 12 | 11/19 | IO/NIO | |  
| 13 | 11/26 | Libraries (Guava / Jackson) / Testing (Junit / Mockito) / IDEs | |
| 14 | 12/3 | TBD (Serialization / Reflection / GUI / Android / Patterns (Builder, Dependency Injection, etc) | |
| 15 | 12/10 | __Final__ (see [Exams](#exams)) | |

### Participation

Ask as many questions as you have. I would encourage you to ask the questions in class by raising your hand. However, I understand that you may not feel comfortable asking in front of a large group and so would prefer to ask your question anonymously. To facilitate as many questions in-class as possible, each lecture I will be opening a stream on [streme.co](http://streme.co/) to allow anyone to ask questions anonymously. I will have the stream running throughout lecture and will answer questions as they are asked. I will post the unique stream URL for the lecture at the start of the lecture. 

### GitHub Usage

This class will use [GitHub](http://github.com) extensively. All lectures, homework assignments and discussion will happen on the class's [repository](https://github.com/NYU-CS9053/Fall-2014);
To read more about the benefits to this for you as a student, read [here](https://education.github.com/)

You must notify me of your GitHub user id. As soon as you do, I will verify that you're enrolled in the class, and then give you access to the class's private [repository](https://github.com/NYU-CS9053/Fall-2014).  The repository is [Fall-2014](https://github.com/NYU-CS9053/Fall-2014). If you do not have access you will get a 404 message. This means either;
* you haven't given me your GitHub user id
* I have not yet added you
* or you are not logged-in with that user id.

Ensure you have access to this [repository](https://github.com/NYU-CS9053/Fall-2014) __ASAP (as soon as possible)__

Upon getting access you must [Fork](https://help.github.com/articles/fork-a-repo) the repository. This will give you write access to a copied version owned by your user. 

### Homework

There will be __10__ homework assignments.  Each assignment will be posted at the end of lecture and will be due at __5 pm__ the day of the following lecture.

Homework assignments will be posted immediately after lecture. They will be due at __5pm__ the day of the next lecture (in general, consult the [Grading Schedule](#grading) for any changes)

The process for viewing and submitting homework assignments is:
* I will make the assignment available immediately after the lecture
* You will work on your assignment and commit locally
* The final commit which I'll review for grading will be the latest commit __before 5pm__ the day of the following lecture (i.e., you'll have about one week to complete the assignment)
* Only __after 5pm__ you should push your changes to your forked repository (`git push`) and then issue a [Pull Request](https://help.github.com/articles/using-pull-requests) for your completed work thus making it available for grading.

__Important__ If any part of this process does not make sense please let me know __ASAP (as soon as possible)__ via e-mail or in the first lecture.

See [Grading](#grading) for dates and overall grade percentage.

### Exams

There will be __3__ exams in total.  

* __Midterm 1__ - this is a take home exam. 
* __Midterm 2__ - this is an in-class exam. It will be longer then the first midterm and will be written (no computer usage).
* __Final__ - this is an in-class exam. It will be slightly longer than the second midterm and will also be written (no computer usage).

See [Grading](#grading) for dates and overall grade percentage.

### Grading

| Activity | Date Due | Overall Grade Percentage |
| :------- | :------: | :----------------------: |
| Homework 1 | 9/10 @ 5 pm | 5% |
| Homework 2 | 9/17 @ 5 pm | 5% |
| Homework 3 | 9/24 @ 5 pm | 5% |
| Homework 4 | 10/1 @ 5 pm | 5% |
| Midterm 1 (take home) | 10/8 @ 5 pm | 10% |
| Homework 5 | 10/15 @ 5 pm | 5% |
| Homework 6 | 10/22 @ 5 pm | 5% |
| Midterm 2 | 10/29 | 15% |
| Homework 7 | 11/5 @ 5 pm | 5% |
| Homework 8 | 11/12 @ 5 pm | 5% |
| Homework 9 | 11/19 @ 5 pm | 5% |
| Homework 10 | 11/26 @ 5 pm | 5% |
| Final | 12/10 | 25% |

####Tips for Homework
* Your code must compile and be tested to work. If it does not compile/work it is better to leave a comment explaining as much of what you've done to try to remedy as you may receive partial credit.
* Comment your code. Be descriptive yet succinct.
* Follow as closely as possible the [Sun Code Conventions](http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html). Mainly:
    - Class names begin with an upper case character
    - Constants (`static final`) variables are all upper case.
    - Methods and variable names should be camel-case (i.e., begin with a lower case and then use an upper case character to distinguish second and subsequent words; e.g., `processRecords`)
* Use descriptive names for variables, methods & classes.

### Cheating / Copying Code
Any form of cheating or using others' code will not be tolerated. All work must be original. If two students hand in essentially the same code then __both__ students will receive __0__ for that assignment and also for another assignment (their highest scoring) and may also face further disciplinary action from NYU.     

### Supplemental Reading

In addition to the [Textbook](#textbook) and the [Recommended Textbooks](#recommended-textbooks) I'd also suggest you read the following:

* Core Java, volume two, Advanced Features, 9th ed.; Cay Horstmann and Gary Cornell. __ISBN-13 978-0137081608__
    - We will be referencing the second volume in lectures 6 and 12
    - Many of the features (like _JDBC_, etc) we will not get into but this is still a good book to own and reference
* The Java Programming Language, 4th ed; Ken Arnold, James Gosling & David Holmes; __ISBN-13 978-0321349804__
    - Great introduction to the language and surprisingly approachable 
* Java Puzzlers; Joshua Bloch & Neal Gafter __ISBN-13 978-0321336781__
    - Fun read and the first lecture will include a couple examples of which for illustrative purposes
    - Many of the puzzles deal with very esoteric aspects of the language but many of them are also _gotchyas_ of which Java programmers should be aware
* The Well-Grounded Java Developer: Vital techniques of Java 7 and polyglot programming; Benjamin J Evans & Martijn Verburg __ISBN-13 978-1617290060__
    - Geared toward Java 7 in particular. I'd recommend you read this after taking this class. It will reinforce a lot of what you should learn in this class.
* Java In A Nutshell, 5th ed; David Flanagan __ISBN-13 978-0596007737__
    - Decent overview of the language. Not as good as _Core Java_ but still worth reading

Online Resources

* Java 7 Documentation - http://docs.oracle.com/javase/7/docs/api/
    - Mostly will be referenced by you via _Google_ searches but still good to browse through proactively to understand how __Javadoc__ structures documentation in general
* Java Tutorials - http://docs.oracle.com/javase/tutorial
    - Fairly good tutorials that are practical and pointed. I would recommend doing most of these.
* The Java Language Specification - http://docs.oracle.com/javase/specs
    - For a rainy day...
* Angelika Langer's FAQ on Java Generics - http://www.angelikalanger.com/GenericsFAQ/JavaGenericsFAQ.html
    - Extremely great FAQ about generics added in Java 5. This is my go-to when I'm twisting my head around edge cases with generics.
* John Sterling's [Java for C++ Programmers](http://cse.poly.edu/jsterling/cs9053/Notes/JavaForC++Programmer.html)
    - A great reference point for those coming to Java from C++. It's written by an NYU professor who has taught CS9053 for years.
* StackOverflow - http://stackoverflow.com
    - The best place to find and post questions to Java problems. I'm guessing you'll be spending a lot of time on this site while learning Java. 