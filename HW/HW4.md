# HW4

Complete and extend the workshop to solve the following measures:

1. Do a simple calculations (50 points)

   * **String Usage**: How many string literals are used in file.
   * **ParameterCount**: The number of parameters for function.
   * **PackageComplexity**: The number of imports used in file.
   * **Returns**: The number of return statements in function. 
   * **AllConditions**: The total number of conditions in file.

2. Using multiple visitors (50 points).

   * **SimpleCyclomaticComplexity**: The number of if statements/loops + 1.
   * **MaxMessageChains**: The max length of a message chain in a function. A message chain can be formed from a method call (), a data access (.), or array access [0].
     For example, 
     
     ```
     // Message Chain: 4
     mints.name.toString().split(".")[0];
     ``` 

3. Bonus (20 points):

   * **MaxConditions**: The max number of conditions inside one if statement per function.
   * **MaxNestingDepth**: The max depth of scopes (nested ifs, loops, etc) per function.

## Submit

Submit code [here](https://goo.gl/forms/nSz7BQYlchXudon22) by Thursday October 27th, midnight.
