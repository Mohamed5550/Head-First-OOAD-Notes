# Chapter 1: Well-Designed Apps Rock

    This book will teach you how to write a great software. It will tell you where to start first

## The Guitar search program

- We have a guitar class and an inventory class
- We want to search for a given guitar by any of its properties

## What a great software means?

- `customer friendly programmer:` It is a software that satisfies the client, even if he requires new things
- `the OO programmer:` It is a software that is object-oriented and every object is responsible for its behaviour, ther is no duplicates, and it is easy to extend
- `the design guru:` It is a software that uses a tried-and-true design patterns and principles

### The full answer

    Great software should satisfy both the customer and the programmer

- Great software does what the customer wants it to do
- Great software should apply OO techniques to be flexible
- Great software should be maintainable, reusable and extendable

## Let's fix Rick's app

### The case sensitive search

- Don't make problems to solve problems:
  - You need to ignore the cases of letters
  - But if you do it straigh forward this will make the code less cleaner
  - You will need to solve that issue later
- You can use `enums` instead of string comparision
  - one `enum` to represent one property of the guitar
  - This will limit the number of options, so no misspelling or case issue
- Code that is not `fragile` is called `robust code`

### Rick's customers want choices

- We return list of matched guitars

### Analyze the search() method

    Use a textual description of the problem you're trying to solve to make sure that your design lines up with the intended functionality of your application

- objects does one thing and only one thing. In a well-designed app, objects hate to do something which is not its job

#### Encapsulation

- It is not only about hiding some parts to prevent writing to it
- It is also about breaking your app into logical parts and then separate them
- Anythime you see duplicate code, look for a place to encapsulate

### Let's make it reusable

#### Delegation

- Delegation is that when the object needs to do something it asks another object to do it instead of doing it by itself
