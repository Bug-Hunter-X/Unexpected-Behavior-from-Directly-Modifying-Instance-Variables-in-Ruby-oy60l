# Unexpected Behavior from Directly Modifying Instance Variables in Ruby

This repository demonstrates an uncommon bug in Ruby that can arise from directly modifying instance variables using `instance_variable_set` or `instance_variable_get`.  This can bypass the intended encapsulation and lead to unexpected behavior if not handled carefully.

The `bug.rb` file shows an example where directly manipulating an instance variable circumvents the getter method's logic (if any), potentially disrupting data integrity or breaking assumptions.

The `bugSolution.rb` illustrates the preferred approach, using methods to access and modify instance variables, which maintains better encapsulation and predictability.