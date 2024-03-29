## Variable Assignment:

C++ is a language that requires variable types to be known at compile time.

But, C++ does allow some implicit conversions, for example an integer can be assigned to a float or an integer can be treated as a char. The next programming quiz will demonstrate these concepts.

## PreFix and PostFix

In C++, as in many languages, there are postfix and prefix operators.
The form for each is:

Incrementing

* prefix: ++a
* postfix: a++
Decrementing

* prefix: --a
* postfix: a--

The difference between prefix and postfix is subtle, but crucial.

Prefix operators increment the value of the variable, then return the reference to the variable.

Postfix operators create a copy of the variable and increments the value of the variable. Then it returns a copy from BEFORE the increment.