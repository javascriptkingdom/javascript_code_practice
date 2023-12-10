---

# JavaScript Control Flow Statements Assignment

## Objective
The objective of this assignment is to enhance your understanding of control flow statements in JavaScript, including `if`, `else if`, `switch` case, nested `if else`, Ternary operators, `while`, `do while`, `for` loop, `break`, and `continue`.

## Instructions

### 1. **`if`, `else if`, `else` Statements**
   - Write a JavaScript program that uses `if`, `else if`, and `else` statements to:
     - Determine if a given number is positive, negative, or zero.
     - Classify a person's age into categories such as "Child," "Teenager," "Adult," or "Senior. Categorize ages as follows:
       
            - 0 to 12 years: "Child"
            - 13 to 19 years: "Teenager"
            - 20 to 64 years: "Adult"
            - 65 and above: "Senior"
     - Imagine you are tasked with developing a JavaScript program that assists a movie ticket booking system. Your program needs to determine the ticket price for customers based on their age.

            The ticket price is determined according to the following criteria:
            
            - For customers aged 0 to 5 (inclusive), the ticket is free.
            - For customers aged 6 to 12 (inclusive), the ticket price is $8.
            - For customers aged 13 to 18 (inclusive), the ticket price is $12.
            - For customers aged 19 to 60 (inclusive), the ticket price is $15.
            - For customers aged 61 and above, the ticket is free as a senior citizen discount.
            
            If the provided age is negative or not a valid number, return "Invalid age."


### 2. **`switch` Case**
   - Extend the program to utilize a `switch` case for:
     - Assigning the day of the week based on a given number (1-7).
     - Identifying the type of fruit based on a provided fruit name.
     - Imagine you're tasked with building a smart home automation system that controls different appliances(tv, Ac, fan, etc..) based on voice commands. Your JavaScript program needs to interpret voice commands and execute actions accordingly using a switch case. Develop a JavaScript program that takes voice commands and performs specific actions based on the command given.

         1. Use a switch case structure to interpret voice commands and execute actions for different appliances in a smart home.
         2. Define at least five voice commands and assign corresponding actions for each command:
            - Example: "Lights on" → Turn on lights, "TV off" → Turn off the TV, etc.
         3. Ensure to handle a default case for unrecognized commands.
         
         ### Example for Help:
         
         ```javascript
         switch (command) {
             case "lights on":
                 console.log("Turning on lights");
                 break;
             // Add more cases and corresponding actions here
             default:
                 console.log("Unrecognized command");
                 break;
         }


### 3. **Nested `if else` Statements**
   - Create a program with nested `if else` statements to:
     - Determine eligibility for voting based on age and citizenship.
        - Implement the following conditions using nested if else statements:

            If the person is both a citizen and aged 18 or older, return "Eligible to vote."
            If the person is not a citizen, return "Not a citizen. Cannot vote."
            If the person is a citizen but below 18 years old, return "Citizen, but not old enough to vote."
            For any other cases or invalid inputs, return "Invalid input."  
     - Categorize a person's BMI (Body Mass Index) as "Underweight," "Normal weight," "Overweight," or "Obese."
         | BMI            | Weight Status   |
         |----------------|-----------------|
         | Below 18.5     | Underweight     |
         | 18.5 – 24.9    | Healthy Weight  |
         | 25.0 – 29.9    | Overweight      |
         | 30.0 and Above | Obesity         |


### 4. **Ternary Operators**
   - Implement a section in your program using Ternary operators to:
     - Check if a given number is even or odd.
     - Determine whether a person is eligible for a discount based on their membership status.
        - Implement the following condition using a ternary operator:

            - If the person is a member, return "Eligible for a discount."
            - If the person is not a member, return "Not eligible for a discount."

### 5. **`while` and `do while` Loops**
   - Write programs utilizing `while` and `do while` loops to:
     - Display numbers from 1 to 10 in reverse order.
     - do while loop to calculate the sum of numbers from 1 to a given positive integer limit. console the total sum of numbers. For example if limit value is 10 then the output should be Expected 55. like (1 + 2 + 3 + ... + 10 = 55)

### 6. **`for` Loop, `break`, and `continue` Statements**
   - Create a program using a `for` loop and demonstrate the use of `break` and `continue` to:
     - Find prime numbers within a specified range.
     - Display the multiplication table of a given number, skipping multiplication by 3.

## Submission
Submit your JavaScript code as a single file or provide a link to an online code repository (e.g., GitHub). Ensure that your code is well-commented, organized, and includes explanations where necessary to clarify the logic used for each task.

---
