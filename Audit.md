# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program calculates student average | Yes | `calculate_average` sums elements in a loop and divides by `len(marks)`[cite: 1]. |
| Program takes user input from terminal via `input()` | No | No `input()` function exists; values are passed directly into functions or tests[cite: 3, 4]. |
| Program validates input or handles errors | No | There are no `try-except` blocks or type/value check conditions[cite: 1, 2]. |
| Program evaluates passing status | Yes | `is_passing(mark)` checks if `mark >= PASS_MARK` (where `PASS_MARK = 40`)[cite: 1, 2]. |
| Program assigns academic grade categories | Yes | `get_grade(average)` assigns Distinction, First, Second, or Fail based on score ranges[cite: 2, 3]. |
| Python 3 is required | Yes | Script uses Python 3 syntax and standard execution tools[cite: 3, 7]. |
| External packages or `requirements.txt` are needed | No | Uses only standard Python features and the built-in `unittest` module[cite: 4, 7]. |
| Unit test suite exists and runs 9 tests | Yes | `test_student_utils.py` uses `unittest` and successfully completes 9 test cases[cite: 4, 7]. |
| Project contains an MIT License file | No | No `LICENSE` file exists in the repository. Section removed. |

```
