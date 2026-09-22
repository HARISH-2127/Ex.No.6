# Ex.No.6 AI-Assisted Programming and Debugging
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

#AI Tools Required:

# Explanation:
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 
Learnerss generate

Python
C
Java
using AI.

Then

identify bugs
optimise code
explain complexity
generate unit tests
Finally compare manual coding versus AI-assisted coding. 
Deliverable

Code quality analysis.
Procedure
# Step 1: Select an Application

Select a real-world programming problem from an area of interest.

Example:
Student Result Analysis System

The application accepts student marks through an API, calculates the average and grade, and generates useful insights.

# Step 2: Define the Programmer Persona

Give the AI tool a specific persona.

Persona Prompt:

"Act as an experienced software programmer and Python developer. Develop a clean, efficient, well-documented solution for the given application. Follow good programming practices and include proper error handling."

The same persona can be given to different AI tools to ensure a fair comparison.

# Step 3: Generate Python Code
Prompt given to AI Tool 1 – ChatGPT

Act as an experienced Python programmer. Create a Python program for a Student Result Analysis System that retrieves student data from a REST API, calculates the average mark, determines the grade, handles API errors, and displays actionable insights. Write clean, modular and well-documented code.

Prompt given to AI Tool 2 – Google Gemini

Act as an experienced Python programmer. Develop a Python-based Student Result Analysis System that interacts with a REST API, processes student marks, calculates average marks, determines grades, handles exceptions, and generates useful insights. Follow Python best practices.

Prompt given to AI Tool 3 – Microsoft Copilot

Act as a professional Python developer. Generate an efficient Python program that consumes student data from an API, analyses marks, determines grades, handles errors, and produces actionable insights. Include comments and modular functions.

# Step 4: Generate C and Java Code

Use the same problem and requirements to generate implementations in C and Java.

C Prompt

Act as an experienced C programmer. Convert the given Student Result Analysis System into C. Provide clean and efficient code with appropriate functions, error handling, and comments.

Java Prompt

Act as an experienced Java programmer. Implement the Student Result Analysis System using Java. Use appropriate classes and methods, handle errors properly, and provide clean, maintainable code.

# Step 5: Identify Bugs

Ask each AI tool to analyse the generated code.

Prompt

Review the generated code carefully. Identify syntax errors, logical errors, runtime errors, API-related problems, security issues, and poor programming practices. Explain each bug and provide the corrected code.

Bug Analysis Table
Bug Type	Example	Effect
Syntax Error	Incorrect syntax	Program does not execute
Logical Error	Wrong grade calculation	Incorrect result
Runtime Error	Missing API response handling	Program may crash
API Error	Invalid endpoint	Data cannot be retrieved
Input Error	Invalid marks	Incorrect processing
Exception Handling	No error handling	Unexpected termination

# Step 6: Optimize the Code

Ask the AI tools to improve their generated solutions.

Optimization Prompt

Optimize the generated code without changing its functionality. Improve execution efficiency, memory usage, readability, modularity, and error handling. Explain what changes were made and why.

Possible optimization techniques include:

Removing unnecessary loops
Reducing repeated calculations
Using appropriate data structures
Creating reusable functions
Improving API handling
Avoiding redundant variables
Improving exception handling

# Step 7: Complexity Analysis

Ask the AI tool to analyse the complexity.

Prompt

Analyse the time and space complexity of the generated program. Identify the complexity of each major operation and provide the overall Big-O complexity.

Example:

Operation	Time Complexity
API data retrieval	Depends on API/network
Processing N students	O(N)
Calculating average	O(N)
Finding highest mark	O(N)
Generating insights	O(N)
Overall	O(N)

Space complexity may be O(N) if all student records are stored in memory.

# Step 8: Generate Unit Tests

Ask the AI tools to generate test cases.

Prompt

Generate unit tests for the Student Result Analysis System. Include normal cases, boundary cases, invalid inputs, empty API responses, API failures, and exception cases.

Sample Unit Test Cases
Test Case	Input	Expected Output
TC01	Valid marks	Correct average and grade
TC02	All marks = 100	Grade A
TC03	All marks = 0	Lowest grade
TC04	Empty student list	Appropriate message
TC05	Invalid marks	Input validation error
TC06	API unavailable	API error message
TC07	Invalid API response	Exception handled
TC08	One student	Correct individual result
# Step 9: Compare AI Outputs

The outputs generated by different AI tools are compared.

Comparison Table
Parameter	ChatGPT	Gemini	Copilot
Code Correctness	High	High	High
Readability	High	High	High
Error Handling	Good	Good	Good
Optimization	Good	Good	Good
Documentation	Good	Good	Moderate
Unit Tests	Good	Good	Good
Complexity Analysis	Detailed	Detailed	Moderate
Overall Quality	Excellent	Very Good	Very Good

Note: The ratings should be modified according to the actual outputs obtained during the experiment.

# Step 10: Manual Coding vs AI-Assisted Coding
Factor	Manual Coding	AI-Assisted Coding
Development Time	Higher	Lower
Code Generation	Manual	Automatic
Debugging	Time-consuming	AI can suggest fixes
Optimization	Developer-dependent	AI can suggest optimizations
Unit Tests	Need to write manually	Can be generated automatically
Learning	Strong conceptual understanding	Requires verification
Errors	Depends on programmer	AI can also produce errors
Productivity	Moderate	High
Code Review	Required	Required
Final Reliability	Depends on testing	Depends on validation
# Step 11: Code Quality Analysis

The generated programs should be evaluated using the following parameters:

1. Correctness

Check whether the program produces the expected output.

2. Readability

Check variable names, formatting, comments, and overall structure.

3. Maintainability

Check whether the code can easily be modified or extended.

4. Efficiency

Analyse execution time and memory requirements.

5. Error Handling

Check how the program handles invalid inputs, API failures, and unexpected situations.

6. Modularity

Check whether the program is divided into reusable functions or classes.

7. Testability

Check whether the generated code can easily be tested using unit tests.

# Result

The selected application was implemented using Python, C, and Java with the assistance of multiple AI tools. The generated solutions were analysed for bugs, optimized, and tested using suitable unit test cases. The outputs from ChatGPT, Gemini, and Copilot were compared based on correctness, readability, efficiency, error handling, complexity, and code quality.

The experiment demonstrates that AI-assisted coding can significantly reduce development time and help with debugging, optimization, complexity analysis, and test generation, while manual verification and testing remain essential to ensure the correctness and reliability of AI-generated code.
