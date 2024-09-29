modifying a program such that it evaluates the value of average marks and print
grade correspond to marks obtained in adding to printing either “pass” or “fail”. Given
that pass marks =75.
Possible grades
A is equal or greater than 93 passed exam
Bis equal or greater than 85 passed exam
C equal or greater than 80 passed exam
D is equal or greater than 75 passed exam
E less than 75 fail exam

EXPLANATION
Input: The program takes an array of integer marks (int[] marks = {90, 85, 78, 92, 88}) representing the scores of a student in different subjects.
Average Calculation:
The method calculateAverage(int[] marks) calculates the average by summing up the marks and dividing the total by the number of subjects.
Grade and Pass/Fail Determination:
Based on the average, the program assigns a grade and determines if the student has passed or failed:
A if average is ≥ 93
B if average is ≥ 85
C if average is ≥ 80
D if average is ≥ 75
E if average is < 75
The student passes if the average is 75 or higher.
Output: The program prints the average marks, the grade, and whether the student has passed or failed.
