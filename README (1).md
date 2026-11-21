# Assignment 3 – CO3 (DSA0112)

**Student:** S.Adithiyan  
**Register number:** 1925260197  
**Repository:** `DSA0112-1925260197-Assignment3`
**GitHub URL:** https://github.com/Adithiyan-1005/DSA0112-3.gitin

## Compiler
- GNU g++ (Debian 14.2.0-19)
- Standard: C++17
- Compile command: `g++ -std=c++17 -Wall -Wextra -pedantic main.cpp -o program`
- Run: `./program` (Windows MinGW: `program.exe`)

## Tasks
| Folder | Topic | Verified result |
|---|---|---|
| Task01 | Constructors/overloading | Default, delegated, parameterized constructors; negative copies rejected |
| Task02 | Copy constructor/Rule of Three | Deep copies and copy assignment produce independent prescriptions |
| Task03 | Dynamic allocation/destructor | Dynamic seat rows allocated/released; block and heap lifetime observed |
| Task04 | Arithmetic/stream operators | Money addition, equality, paise carry and formatted output |
| Task05 | Increment/comparison/subscript | Prefix/postfix values and checked playlist indexing |
| Task06 | Text/operator rules | Deep copy, self-assignment safety, concatenation and comparisons |
| Task07 | Complex numbers | Series/parallel impedance and safe division-by-zero handling |

## Running
Each task is independent. From its folder:
```sh
g++ -std=c++17 -Wall -Wextra -pedantic main.cpp -o program
./program
```
`output.txt` contains the captured run. `asan_output.txt` and `asan_report.txt` are included for sanitizer checks where applicable. `output.png` is a rendered terminal-output capture.

## Notes before submission
- Review every program and be able to explain/modify it for the viva.
- Student name and GitHub URL are filled in above. Verify that the URL opens the intended repository before submitting.
- The uploaded assignment is Q1–Q7 (7 questions); it does not contain 12 tasks.
- Add faculty as collaborator if the repository is private, and submit the GitHub link/report through Google Classroom yourself.
- The ZIP does not include a Git history. Create/push the repository and make the required progressive task commits in your GitHub workflow.
