# calculator2
This program was an assignment for CMPSC 132 at Penn State University.
This program accepts an input of a string that contain a mathematical expression that can contain any number of parentheses, exponents, and multiplication, division, subtraction, and addition operators.

This program is broken into different functions with its root function being calculator(). calculator() allows you to input a string with a mathematical expression. From there, it traverses through the string looking for any number of parentheses. Once it finds the innermost parenthesis, I can then look for the first instance of a right parenthesis after the innermost left parenthesis. I can then pass that innermost expression into the _calculator() function, which will then evaluate the inside expression. Once completed, I replace the parenthetical expression with the evaluated expression. From there, I then evaluate the expression in the second inner-most set of parentheses, and so on until I have evaluated all parenthetical expressions.
