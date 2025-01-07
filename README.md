# Ruby Bug: Unexpected Behavior When Directly Modifying Instance Variables

This repository demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`. Directly manipulating instance variables bypasses any methods or logic that might be used for validation or access control.  This can lead to unexpected behavior and make code difficult to debug and maintain.  The recommended approach involves using accessor methods to interact with instance variables.

## Bug
The `bug.rb` file shows the improper way of modifying instance variables. The solution demonstrates a better approach using accessor methods to maintain data integrity and improved code structure.