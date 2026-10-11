# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
| --- | --- | --- |
| Program calculates the average of student marks | Yes | `calculate_average` sums the elements in the loop and divides by `len(marks)`.

 |
| Program takes dynamic user input from the terminal via `input()` | No | There is no `input()` function in the code; functions take arguments directly or via unit tests. Claim corrected. |
| Program includes input validation or error handling | No | No `try-except` blocks or type-checking conditions exist in the functions. Claim deleted. |
| Python 3 is required | Yes | The program is written in standard Python 3. |
| External libraries or `requirements.txt` are required | No | Only built-in Python libraries (`unittest`) are used; no external packages needed. |
| Program evaluates passing status | Yes | `is_passing(mark)` checks if a mark meets or exceeds `PASS_MARK = 40`.

 |
| Program assigns academic grades | Yes | `get_grade(average)` categorizes averages into Distinction, First, Second, and Fail.

 |
| Program includes automated unit tests | Yes | `test_student_utils.py` uses Python's built-in `unittest` framework with 9 test cases.

 |
| Project uses MIT License | No | No `LICENSE` file exists in the repository. License section removed. |
