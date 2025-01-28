# Unhandled JSON Key Access in Dart

This repository demonstrates a common error in Dart applications: attempting to access a JSON key without verifying its existence.  The `bug.dart` file shows the problematic code, which throws an exception if the key is missing.  The `bugSolution.dart` file shows a corrected version using null-aware operators and proper error handling.

## How to Reproduce

1. Clone this repository.
2. Run `bug.dart`.
3. Observe the error if the key 'key' is not present in the API response.