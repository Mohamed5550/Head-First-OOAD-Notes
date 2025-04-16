# Chapter 4: Analysis

- We tested our software in a vacuum where everything is used as we expect it to be used
- We should graduate our project to the real word where real people use it
- Your software has a context that runs in
- Analysis helps you to make your software work in the real world context
- We need to prevent the dog from openning unless it is the correct dog
- We will create a new `Bark` class to store barks
- We will store the correct bark into the door
- We will use delegation to match the incomming bark with the correct one
- Looking at the nouns and verbs in the use case is called `textual analysis`

## The powe of loosely coupled applications

- Delegation sheilds your objects from implementations changes to other objects in your software
- When we need to change the sound object to store `WAV` file instead of string, we will change `Bark->equals` only, without chaning the `BarkRegognizer`

## Why we use UML class diagrams?

- If we go worng, it's faster to change the diagram instead of changing the code
- It's eaiser to explain ideas to others with diagrams
