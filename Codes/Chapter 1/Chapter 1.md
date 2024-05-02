# Chapter 1

## Questions

### 1- How would you redesign Rick's app?

- I will return the Guitar in the search function as it always returns `null`

### 2- What do you think a great software is?

- It is a software that:
  - Proven to always return the expected result
  - It is reliable and can handle errors well
  - It is scalable, that it can handle more load, and is scalable from the requirements point of view, which means it can handle adding more features to it over time
  - Its code is clean, that it is easy for othe programmers to change it

### 3- Write a short description of a projec you're currently working on

- It is a booking sysem where the user searches for a car to move from a place and land to other place and books it on some day

### 4- What is the first thing you did on this project?

- First thing was to make sure the user get correct cars when he searches

### 5- Would the app be better if you knew the 3 steps to make the software great?

- Yes, I would ignore many duplications and it would be more optimized and maintainable

### 6- What do you think the mismatched objects are?

- It is that the client doesn't give Rick a guitar to search

### 7- How would you fix it?

- I would pass a guitar as a parameter to search instead of the properties, and I will compare the two guitars instead of comparing each of their properties separately

### 8- Move the method and properties from Guitar to GuitarSpec

- properties to move to GuitarSpec
  - builder
  - model
  - type
  - backWood
  - topWood

- method to move to GuitarSpec
  - getBuilder()
  - getModel()
  - getType()
  - getBackWood()
  - getTopWood()

- properties to add to Guitar
  - spec: GuitarSpec

- methods to add to Guitar
  - getSpecs(): GuitarSpec

### 9- What issues you see in the search code at this step?

- When I add a new property to the GuitarSpec, I will have to edit search method

### 10- where would you add a new property called numString?

- In the GuitarSpec class

### 11- Where would you add a new method called GetNumString?

- In the GuitarSpec class

### 12- What other code would you change?

- addGuitar() methdod
- The search() method
- The test class
