# Complexity-Analysis

This is a group project done by:
1. Sreeparno Dhar
2. Debanjan Rudra
3. Debjit Dasgupta
4. Shamik Lahiri

<h2> #PROJECT DESCRIPTION </h2>

General method to find out space and time complexity:
The time complexity of an algorithm is commonly expressed using big O notation, which excludes coefficients and lower order terms. When expressed this way, the time complexity is said to be described asymptotically, i.e., as the input size goes to infinity.
For example, if the time required by an algorithm on all inputs of size n is at most 5n3 + 3n, the asymptotic time complexity is O(n3).
The space complexity of a program is the total space occupied by the program during the execution of it. The total space consumed is the sum of the fixed space and variable space. 
Fixed space – the space occupied by the instruction space, simple variables and constants. 
Variable space – the dynamically allocated space to the various data structures and the environment stack space varies according to the input from the user. 
Space complexity S(P) = C + sp
Where C is the fixed space and sp is variable space.

Our project calculates time complexity by measuring and accounting for each loop that our program encounters. Our program will read the user’s code like a text file and sequentially check for all the loops that exist within the user’s code. While reading a code file, our program not only counts the number of loops encountered but also if they are nested or not. Nesting loops can give rise to quadratic and even polynomial time complexities.
To make it visually attractive we added the graphical user interface.



<h2> #INSTRUCTIONS TO RUN : 
1. Run the executable_env.py file.
2. Instead of using Tab for indentation, use 4 (four) spaces.
3. Click on File 🡪 Save and save it as test1.py 
4. Click on File 🡪 Run the file.

5. If you already have a file saved or present in your computer, then:
  a.  File -> Open (It will open the saved file)
  b.  File -> Run
