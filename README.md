# Scala Exception Handling in Setters

This repository demonstrates a potential issue with exception handling in Scala class setters. The `MyClass` example shows a setter that throws an `IllegalArgumentException` if an invalid age (negative) is provided.  This approach is generally good practice for input validation.  However, improper handling of such exceptions in calling code could lead to unexpected application behavior or crashes.  Effective exception management, including error handling and logging, is crucial for robust Scala applications.

## How to Run

1. Ensure you have Scala installed.
2. Save the provided code as `MyClass.scala`.
3. Compile and run using the Scala compiler: `scalac MyClass.scala && scala Main`