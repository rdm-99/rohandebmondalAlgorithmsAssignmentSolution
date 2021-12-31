# rohandebmondalAlgorithmsAssignmentSolution

PART 1
Marks: 10 (2 marks each )
Find the time complexity of the below functions in Θ form. Write NA if the function does not
apply to any case.
a) T (n) = 3T (n/2) + n
b) T (n) = 64T (n/8) − n^2(log n)
c) T (n) = 2nT (n/2) + n^n
d) T (n) = 3T (n/3) + n/2
e) .T (n) = 7T (n/3) + n^2
Note: You don’t have to submit the full solution, the final time complexity in form of Θ is perfectly
acceptable.
Time Complexity in any other asymptomatic notation will lead to zero marks.
You need to submit a text file (MS word, Notepad etc) in GitHub, name it as
YourName_masterTheoremSolution
-----------------------------------------------------------------------------------------------------------------------
PART 2
Marks : 40
PROBLEM STATEMENT
You are working as a software engineer in a Financial Company, Stockers.
Stockers is a leading MNC that specializes in analyzing a company’s shares and consulting
investors/traders.
Till today the company is working manually and wants to be digital. As a Software Engineer, you
are required to code user stories and create the first version of the application.
The Application will accept the no of companies N, that the user wants to store records of.
a) Users will enter the share price(double format) of N companies.
b) Users will enter a boolean value(TRUE, FALSE) of each company, to keep track of the
company’s share price compared to yesterday.
The user will enter value through the console.
Insight: If today the share price of the company is greater than that of yesterday then the user
will input TRUE, else the user will input FALSE. In the given test cases true, false values are
entered randomly. You can also input values TRUE/FALSE on your own
USER can perform the following operations in the application:
1. Display the companies stock prices in ascending order
2. Display the companies stock prices in descending order
3. Display the total no of companies for which stock prices rose today
4. Display the total no of companies for which stock prices declined today
5. Search a specific stock price //it will only display whether the stock price is present or not.
Note: The time complexity(average, best, worst) of the sorting function used should not be more
than O(nlogn).
