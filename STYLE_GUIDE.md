
# Dart Programming Style Guide

This style guide outlines the conventions and best practices for contributing to the Dart Programming repository. Following these guidelines will help maintain consistency and readability throughout the codebase.

## General Principles

1. **Consistency**: Consistent code style makes the codebase easier to read and maintain.
2. **Clarity**: Code should be easy to understand. Use descriptive names and clear logic.
3. **Simplicity**: Aim for simplicity and avoid unnecessary complexity.

## Naming Conventions

- **Variables and Functions**: Use `camelCase` for variable and function names.
  ```dart
  int myVariable = 10;
  void myFunction() {}
  ```

- **Classes and Types**: Use `PascalCase` for class and type names.
  ```dart
  class MyClass {}
  ```

- **Constants**: Use `CONSTANT_CASE` for constant values.
  ```dart
  const int MAX_VALUE = 100;
  ```

## File and Directory Structure

- Organize files by feature or module.
- Use `snake_case` for file names.
  ```
  lib/
  ├── src/
  │   ├── feature_one/
  │   │   ├── feature_one.dart
  │   │   └── feature_one_widget.dart
  │   └── feature_two/
  │       ├── feature_two.dart
  │       └── feature_two_widget.dart
  └── main.dart
  ```

## Code Formatting

- **Indentation**: Use 2 spaces for indentation.
- **Line Length**: Limit lines to 80 characters.
- **Braces**: Use braces for all control structures, even single-line blocks.
  ```dart
  if (condition) {
    // code
  } else {
    // code
  }
  ```

## Documentation

- Use `///` for documentation comments.
  ```dart
  /// This is a documentation comment.
  /// It describes the function below.
  void myFunction() {}
  ```

- Write clear and concise comments to explain complex logic.
- Document all public APIs.

## Dart-Specific Conventions

- **Type Annotations**: Use type annotations for variables and return types.
  ```dart
  String myString = 'Hello';
  int add(int a, int b) {
    return a + b;
  }
  ```

- **Nullable Types**: Use nullable types where necessary.
  ```dart
  String? nullableString.
  ```

- **Cascade Notation**: Use cascade notation for method chains.
  ```dart
  myObject
    ..methodOne()
    ..methodTwo;
  ```

## Error Handling

- Use exceptions for error handling.
  ```dart
  try {
    // code that might throw an exception
  } catch (e) {
    // handle the exception
  }
  ```

## Testing

- Write tests for all new features and bug fixes.
- Use descriptive names for test cases.
- Organize tests in a `test` directory, mirroring the `lib` directory structure.
  ```
  test/
  ├── feature_one_test.dart
  └── feature_two_test.dart
  ```

## Git Commit Messages

- Use the present tense ("Add feature" not "Added feature").
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
- Keep messages concise but descriptive.

## Example Commit Message
```
Add user authentication feature

- Implement login functionality
- Add unit tests for authentication
```

## Code Reviews

- Be respectful and constructive in code reviews.
- Focus on the code, not the person.
- Provide clear and actionable feedback.

---

By following this style guide, we can ensure that the Dart Programming repository remains clean, consistent, and easy to navigate. Thank you for your contributions!
