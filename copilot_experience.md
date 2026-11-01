# Korbin Awender
# CSCI 130
# copilot_experience.md
# 10/31/2026

GitHub Copilot Experience

What Worked Well:
    Copilot quickly generated the basic calculator function that handled addition, subtraction, multiplication, and division. Copilot helped create the brute-force search function by generating the loop structure neeeded to test the values from -100 to 100 in increments of 0.1. Copilot generated error handling using try/except blocks, which helped prevent crashes from invalid user input or division by zero. Copilot was useful for creating functions from simple comments. After describing what I wanted in a comment, it often generated a working starting point. Copilot helped build the menu system and connect the different functions together, reducing repetitive coding.

Challeges: 
    Some suggestions did not fully match the assignment requirements. I had to read the code carefully instead of accepting everything automatically. Copilot occasionally generated code that solved a slightly different problem than what was requested. I needed to understand the suggested code before accepting it, especially when it used logic that I had not written myself.

My Judgement and Changes: 
    One example occurred when I asked Copilot to create the brute-force search function. Its first version searched for exact solutions using a different approach. After comparing the code to the assignment instructions, I realized the assignment required keeping track of the closest value found rather than only searching for an exact match. I modified the solution to track the smallest difference and return the closest value.

    Another issue occurred when Copilot generated a version of the brute-force search function that only accepted parameters a and b and compared the result against x instead of c. After reviewing the logic, I corrected the function to accept all three values (a, b, and c) and compare against the target value c.

    Overall, Copilot was most useful as a coding assistant rather than a replacement for understanding the code. It helped generate ideas and boilerplate code quickly, but reviewing and correcting its suggestions was necessary to ensure the program met the assignment requirements.

All Prompts used to generate code:
    1. Create a function called calculate that accepts a first number, an operator (+, -, *, /), and a second number. Return the result of the calculation and raise an error if division by zero occurs.

    2. Create a function called basic_calculate. Ask the user for two numbers and an operator, call the calculate function, display the result, and handle errors with a try/except block.

    3. Create a brute-force search function called brute_force_search. Solve equations in the form ax + b = c by testing every x value from -100 to 100 in increments of 0.1. Keep track of the closest solution found.

    4. Create a function called equation_solver_menu that asks the user for values a, b, and c, solves the equation using brute_force_search, and displays the approximate value of x.

    5. Create a function called visualize_search that displays every value tested during the search and how far the result is from the target value.

    6. Create a function called explain_search_algorithms that explains how brute-force search works and why it is inefficient.

    7. Create a main menu that connects all program features and repeats until the user chooses to exit.