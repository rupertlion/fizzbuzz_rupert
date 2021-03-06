# **FizzBuzz Weekend Challenge (Wk 2)**
-------
## Prerequisites
-------
Initialised npm (package manager) and utilising: superstatic (for feature-testing), mocha (for unit-testing).

## Built With
-------

* [Javascript](https://www.javascript.com/) - The programming language used
* [npm](https://www.npmjs.com/) - Package manager
* [Chai](http://www.chaijs.com/) - BDD / TDD assertion library
* [Mocha](https://mochajs.org/) - Testing framework
* [Tailwind](https://tailwindcss.com/) - CSS Styling

## **Overview**
-------
The purpose of this challenge is to create a FizzBuzz app in Javascript programming lanugage, test and style the site.

## **Specific questions**
-------

### Question 1:

#### In your README to the best of your knowledge please explain what the following lines of code do?

    ```
    let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
    eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
    ```

#### Answer:

* The previous lines of code required 'fs'.The fs module provides an API for interacting with a file system when using node.js. This allows use of node.js as a file server, including the ability to read, write, update and delete files in local folders. (Node.js allows us to run on our machine as a standalone application rather than only in a browser)

* The following line of code allows node.js modules to read the fizz-buzz.js implementation code that resides locally on my computer. That function is subsequently stored in a variable called 'fizzBuzz' 
    ```
    let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js')
    ```

*  The eval() method reads strings as js code. In the case of the code above, `\nexports.FizzBuzz = FizzBuzz;` is appended to the implementation code in fizz-buzz.js. My assumption is that this, in effect allows the the implementation code to be exported to node modules

-------

### Question 2:

#### In your README to the best of your knowledge please explain what the following lines of code do?

    ```
    let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
    eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
    ```

#### Answer:

    nhgnfhgnhf

-------

## **Author**
-------
* **Rupert Lion**