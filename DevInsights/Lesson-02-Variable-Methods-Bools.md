# Lesson 02 — Variables, Methods, and Bools

This lesson explains the basic building blocks of logic in a mod: variables, methods, and boolean values.

---

## Concept

Variables store data, methods execute actions, and booleans represent true or false states.

These elements are fundamental for controlling behavior inside a mod and reacting to game events.

---

## Core Parts

- Variables: store values (int, float, bool, etc.)  
- Methods: perform actions or logic  
- Bools: represent true or false conditions  

---

## Example

    // Variable
    bool isPhoneOpen = false;

    // Method
    void OpenPhone()
    {
        isPhoneOpen = true;
    }

    // Condition using bool
    if (isPhoneOpen)
    {
        // Do something
    }

---

## What Happens Here

1. A boolean variable is created to store a state  
2. A method changes that state  
3. A condition checks the value of the variable  
4. If true, the code inside the block executes  

---

## Why It Is Useful

- Allows storing game states (like phone open/closed)  
- Enables actions through methods  
- Makes decision-making possible with conditions  
- Forms the base of all mod logic  

---

## Key Idea

> Variables store data, methods execute actions, and booleans control decisions.

---

## What I Learned

- I understood how variables store information  
- I learned how methods modify behavior  
- I now see how booleans are used to control logic  

---

## What I Still Need to Practice

- I need to practice combining variables and methods  
- I want to better understand when to use different variable types  
- I should test more conditions using booleans  

---

## Link to Real Project Use

- PhoneOnSkate → uses bools like BlockDismount and PhoneOpen to control behavior  
- ProfitCalculator → uses variables to store prices and calculations  
