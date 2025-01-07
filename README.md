# Unexpected Instance Variable Modification in Ruby

This repository demonstrates a potential issue in Ruby where instance variables can be modified directly without explicit setter methods.  This can lead to unexpected behavior and make code harder to maintain.

The `bug.rb` file shows the issue where an instance variable is modified without using a defined setter method. This can be problematic because it bypasses any potential validation or side effects that might be included in a properly defined setter.

The `bugSolution.rb` file provides a better solution where we use `attr_accessor` or define explicit getter and setter methods. This approach enhances code clarity, maintainability, and allows for better control over data modification.