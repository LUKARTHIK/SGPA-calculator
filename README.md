# SGPA-calculator


** SGPA Calculator – VTU Results Made Easy**
_This project is a simple and intuitive SGPA (Semester Grade Point Average) calculator designed for students under VTU (Visvesvaraya Technological University) and similar academic systems. It helps students quickly compute their SGPA based on subject credits and grades without manual effort._

** ALGORITHM **
 ### This project calculates SGPA using the following step-by-step logic:

_**Input student details:**_

Ask for student name and USN.

1 . ** Input subject details:**

Ask how many subjects the student has for that semester.

2. **Iterate through each subject:**

 Use a for loop from 1 to number_of_subjects + 1.

3. ** Inside the loop:**

 Take input of marks and credits for each subject.

 4 . **Convert marks to grade points using conditional statements (e.g., if-else or match-case).**

5.  **Calculate earned points:**
  earned_points = grade_point * credit

_Accumulate:_

total_earned_points += earned_points

total_credits += credit

After the loop:

Compute SGPA using the formula:

**𝑆𝐺𝑃𝐴** = Total Earned Points//Total Credits

​
 
>  Print SGPA on the output screen.
