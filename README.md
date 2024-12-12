# Ruby Getter Method Assignment Error

This example showcases a common error in Ruby when dealing with getter methods.  Attempting to directly assign a value to an instance variable through the getter method results in a `NoMethodError`. The correct way to modify the instance variable is to use `instance_variable_set`. 

The `bug.rb` file demonstrates the error, while `bugSolution.rb` shows the correct approach.