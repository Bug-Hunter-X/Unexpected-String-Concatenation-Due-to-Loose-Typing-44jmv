# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript bug stemming from the language's loose typing system.  The `foo` function intends to add two numbers, but due to the implicit type coercion, it performs string concatenation instead when one argument is a string.

## How to Reproduce

1. Clone the repository.
2. Run `node bug.js`.
3. Observe the unexpected output.

## Solution

The `bugSolution.js` file provides a corrected version of the function that explicitly handles type checking or uses a stricter type system to prevent this issue.

## Lessons Learned

This example highlights the importance of explicit type handling or employing techniques such as TypeScript to enhance the robustness and predictability of JavaScript code.