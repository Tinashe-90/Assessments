# Assessments
A league table in python 
a production ready, maintainable, testable command-line application that
will calculate the ranking table for a league.
Input/output
The input and output will be text. Either using stdin/stdout or taking filenames on the command
line is fine.
The input contains results of games, one per line. See “Sample input” for details.
The output should be ordered from most to least points, following the format specified in
“Expected output”.
You can expect that the input will be well-formed. There is no need to add special handling for
malformed input files.
The rules
In this league, a draw (tie) is worth 1 point and a win is worth 3 points. A loss is worth 0 points.
If two or more teams have the same number of points, they should have the same rank and be
printed in alphabetical order (as in the tie for 3rd place in the sample data).
Guidelines
This should be implemented in a language with which you are familiar. We would prefer that
you use python, java, golang, or scala, if you are comfortable doing so. If none of these are
comfortable, please choose a language that is both comfortable for you and suited to the task
like, node, ruby, or C.
If you use other libraries installed by a common package manager (rubygems/bundler, npm,
pip), it is not necessary to commit the installed packages.
We write automated tests and we would like you to do so as well.
If there are any complicated setup steps necessary to run your solution, please document them.
Platform support
This will be run in a unix-ish environment (OS X). If you choose to use a compiled language,
please keep this in mind. Please use platform-agnostic constructs where possible (line-endings
and file-path-separators are two problematic areas).
**Sample input:**

Lions 3, Snakes 3
Tarantulas 1, FC Awesome 0
Lions 1, FC Awesome 1
Tarantulas 3, Snakes 1
Lions 4, Grouches 0
**Expected output:**
1. Tarantulas, 6 pts
2. Lions, 5 pts
3. FC Awesome, 1 pt
3. Snakes, 1 pt
5. Grouches, 0 pts
