# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The provided code attempts to access a user by ID, but fails to handle cases where the ID is not a valid integer. This can lead to unexpected behavior or crashes.

The `bug.js` file shows the flawed code, while `bugSolution.js` presents a corrected version with appropriate error handling.