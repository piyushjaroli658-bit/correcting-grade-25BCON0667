# correcting-grade-25BCON0667
Python Student Utilities & Debugging Exercise (RED -> FIX -> GREEN)

A beginner-friendly Python project demonstrating the RED -> FIX -> GREEN development cycle using automated unit testing (unittest) and guided AI debugging assistance.

🚀 What student_utils.py Contains

The project includes a utility script (student_utils.py) with three core functions designed for student grade evaluation:

calculate_average(marks): Computes the arithmetic mean of a list of numeric marks.

is_passing(mark): Checks whether an individual mark meets or exceeds the passing threshold (40).

get_grade(average): Assigns a letter grade (Distinction, First, Second, or Fail) based on the average score.

📋 Test Specifications

A separate test suite (test_student_utils.py) contains 9 rigorous test cases verifying correct boundary conditions, single-item lists, and grade sorting logic.

Number of tests: 9

Final Result: All tests passing (OK)

⚙️ How to Run the Tests

Ensure you have Python installed, then run the test suite from your terminal or Google Colab:

python test_student_utils.py


🔄 The RED -> FIX -> GREEN Cycle

This project follows a disciplined engineering workflow:

RED Stage: Write and run tests against the original buggy implementation to capture failures and prove that tests detect incorrect behavior.

FIX Stage: Modify the implementation in student_utils.py step-by-step (without altering the tests) to address the core logic bugs (denominator error, boundary comparison, and conditional evaluation order).

GREEN Stage: Rerun the exact same test suite to verify that all bugs are resolved and all 9 tests pass successfully.
