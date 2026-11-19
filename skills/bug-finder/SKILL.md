# Bug Finder

Read the given Python exercise file with line numbers.

Compare every function with its docstring to understand what it should do.

Check every function carefully and find all bugs.

Pay special attention to boundary conditions:
- "at least" means >=
- "or more" means >=
- "at most" means <=
- "more than" means >
- "less than" means <

Check exact boundary values, not only values above or below them.

Also check mathematical operations and incorrect variables.

For EACH bug, output EXACTLY these four lines:

Line: <the exact line number>
Problem: <what is wrong and why>
Example: <function call, actual result, expected result>
Fix: <one corrected Python line>

Put one blank line between bug reports.

Use exactly these labels:
Line:
Problem:
Example:
Fix:

Do not use Markdown code blocks, bullet points, headings, or extra explanations in the bug reports.

Report every distinct bug.
Do not modify the original exercise file.
Do not write tests.

Check every function separately before producing the final reports.

For password validation, carefully check minimum length requirements.
"At least 8 characters" means length >= 8, not length > 8.

Test a password with exactly 8 characters and at least one digit.

Do not stop after finding two bugs.
Check all functions and report every incorrect return statement.

Use exactly the required Line, Problem, Example, Fix format.
