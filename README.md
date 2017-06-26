![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Learning Python

You've learned Ruby, C, C++, JavaScript and SQL. Getting started with a totally new language doesn't have to be hard. The biggest key is to practice doing something that you *already know* in the context of the new language. This is called a *transfer task*. The more languages and computer science concepts you learn, the easier new ones become to pick up and its mostly syntax, quirks and language-specific tools that become the tricky part.

Now, your task is to *teach yourself* a bit of Python. The goal here isn't to become a Python master, but to explore and learn a bit about a new language.

**All exercises below should be done with Python 3**

## Goals:

By the end of this exercise, you should be able to:

- Create a simple python program
- Execute a simple python program
- Articulate basic differences between Python and other languages you know
- Feel comfortable understanding what is generally happening in most basic python programs

## Installing Python

Your Mac comes with Python 2.7. We want Python 3.

`brew install python3`

Execute the Python REPL with:

`python3`

Execute a Python program with:

`python3 program.py`

## Research: What is Python

Your first task is to research Python to be able to understand some of its basic concepts. Edit this `README.md` file to answer the below questions:

##### What paradigms does Python support?
Python is a multi-paradigm programming language: object-oriented programming and structured programming are fully supported, and many language features support functional programming and aspect-oriented programming (including by metaprogramming and metaobjects (magic methods)). Many other paradigms are supported via extensions, including design by contract and logic programming.

##### What typing discipline does it follow?
Dynamic type checking is the process of verifying the type safety of a program at runtime. Implementations of dynamically type-checked languages generally associate each runtime object with a type tag (i.e., a reference to a type) containing its type information. This runtime type information (RTTI) can also be used to implement dynamic dispatch, late binding, downcasting, reflection, and similar features.

Most type-safe languages include some form of dynamic type checking, even if they also have a static type checker.[citation needed] The reason for this is that many useful features or properties are difficult or impossible to verify statically. For example, suppose that a program defines two types, A and B, where B is a subtype of A. If the program tries to convert a value of type A to type B, which is known as downcasting, then the operation is legal only if the value being converted is actually a value of type B. Thus, a dynamic check is needed to verify that the operation is safe. This requirement is one of the criticisms of downcasting.

By definition, dynamic type checking may cause a program to fail at runtime. In some programming languages, it is possible to anticipate and recover from these failures. In others, type-checking errors are considered fatal.
##### Is it a high or low level language?
High level
##### Does it have built in memory management and garbage collection?

##### What languages was Python influenced by?

##### Is it a compiled or interpeted language?

##### Does it have strong support for functional programming?

##### What's the deal with Python 2 vs Python 3?

##### How do you open a REPL for Python?

##### How does one execute a Python program?


## Read: The Zen of Python

> The Zen of Python, by Tim Peters
>
> Beautiful is better than ugly.
> Explicit is better than implicit.
> Simple is better than complex.
> Complex is better than complicated.
> Flat is better than nested.
> Sparse is better than dense.
> Readability counts.
> Special cases aren't special enough to break the rules.
> Although practicality beats purity.
> Errors should never pass silently.
> Unless explicitly silenced.
> In the face of ambiguity, refuse the temptation to guess.
> There should be one-- and preferably only one --obvious way to do it.
> Although that way may not be obvious at first unless you're Dutch.
> Now is better than never.
> Although never is often better than *right* now.
> If the implementation is hard to explain, it's a bad idea.
> If the implementation is easy to explain, it may be a good idea.
> Namespaces are one honking great idea -- let's do more of those!

## Hello World

Write a program in `hello_world/hello_world.py` that prints 'Hello, World!' to the standard output (terminal).

## Fizzbuzz

Write a program in `fizzbuzz/fizzbuzz.py` that does the following:

For numbers 1 through 100, print `fizz` if the number is divisible by 3, `buzz` if the number is divisible by 5 and `fizzbuzz` if the number if the number is divisible by both 3 and 5. If the number isn't divisible by 3 or 5, just output the number itself.

The output should look something like `1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz Buzz 16 17 Fizz...`

## Fibonacci

Write a program in `fibonacci/fib.py` that will output the N-th term of the [Fibonacci sequence](http://en.wikipedia.org/wiki/Fibonacci_number).

For example: `print fib(6)` should output `8`.

## Project Euler Problem 1

Project Euler's first problem is:

> If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
> Find the sum of all the multiples of 3 or 5 below 1000.

Write the code to complete this in `euler_1/sum_of_natural_numbers.py`

## Conclusion

How does Python compare to other langauges you've used? Which language is is closest to?
