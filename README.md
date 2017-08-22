# JavaScript-NODE
CS_546 Labs
All the labs are semi projects using NODE.JS and Mongo DB.
LAB 1: Initial introduction to the NODE.JS

Lab 2: This metric will print out a variety of shapes on your console

Lab 3: in this lab working with files; particularly, reading them, creating metrics on them, and storing them using promises.
input: {
    totalLetters: total number of letters in the text,
    totalWords: total number of words in the text,
    uniqueWords: total number of unique words that appear in the text,
    longWords: number of words in the text that are 6 or more letters long,
    averageWordLength: the average number of letters in a word in the text,
    wordOccurrences: a dictionary of each word (lowercased, no punctuation) and how many times each word occurs in the text.
 }
 output: totalLetters: 49,
    totalWords: 16,
    uniqueWords: 14,
    longWords: 1,
    averageWordLength: 3.0625,
    wordOccurrences: {
        hello: 3,
        my: 1,
        friends: 1,
        this: 1,
        is: 1,
        a: 1,
        great: 1,
        day: 1,
        to: 1,
        say: 1,
        2: 1,
        3: 1, 
        4: 1,
        23: 1
    }
}   

Lab 4: The major concepts of this lab are:
    Seperating concerns into different modules:
        Database connection in one module
        Collections defined in another
        Data manipulation in another
    Further practicing the usage of promises for asynchronous code
    Continuing our exercises of only linking these modules together as needed

Lab 5: For this lab, we will create our first 3 HTML files!
This lab is unique in a major way: there is no node code this week!
The major concepts of this lab are:
    Making data-centered HTML Documents
        Thinking in terms of describing our data, without care for the visual aspect
        Focusing on structure and semantical validity.
    Writing valid HTML
        Your HTML must be valid (Links to an external site.)Links to an external site. or you will lose points on the assignment.
    Linking between pages
        You will use a basic navigation structure (see below) on each page to link to all the pages you are writing.

Lab 6: For this lab, you will create a simple server that will represent the same data that you created in lab 5 by sending JSON down through API calls.
For this lab, you will not need to use a database. You can store your data right in your routes.

Lab 7: For this lab, you will create a simple server that provides an API for someone to Create, Read, Update, and Delete recipes. These recipes will be stored in a database named lab7-recipes.
This recipe database will also provide support for creating, reading, updating, and deleting comments for a recipe.

Lab 8:For this lab, you will be using HTML, CSS, and JavaScript on the user's browser to make a simple palindrome checker!
A palindrome is a phrase that is spelled the same way, backwards and forwards (ignoring spacing and punctuation). For example, the following phrases are palindromes:
    Madam
    Was it a cat I saw?
    He did, eh?
    Go hang a salami, I’m a lasagna hog.
    Poor Dan is in a droop
You will create an express server with a single page at the location / that will provide the user with a web page to allow them to check if a phrase is a palindrome.

Lab 9: A Simple User Login System
Using the concepts learned on authentication, middleware, etc, you will use a node package to implement a basic user system with only 3 routes.
This lab will require a good deal of reading, but relatively little code to be written out.
You must first read up on Passport (Links to an external site.)Links to an external site. and what it accomplishes, then read up on the Passport Local Strategy (Links to an external site.)Links to an external site. in order to complete this lab.
Passport is a very simple, easy to drop in middleware that allows you to quickly add application authentication.
A strategy is a way of checking whether or not a request is authenticated.

Lab 10: Fixing All The Things
Using all you have learned about jQuery, accessibility, and node in general, you will find the (approximately) 11 issues in the simple repository (Links to an external site.)Links to an external site. for lab 10.
You will submit an updated version of the lab 10 code without accessibility issues, and where the the form sends data back and forth to the server and prints the reply on the page in the paragraph with an id of the-result.
