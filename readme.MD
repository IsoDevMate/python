## POSITIONAL ARGUEMENTS
ositional arguments are the ones whose meaning is dictated by their position, e.g., the second argument is outputted after the first, the third is outputted after the second, etc.

Note:  positional argument follows keyword argument e.g the following will output a syntax error.

print(sep="&", "fish", "chips")


## KEYWORD ARGUEMENTS
 keyword argument consists of three elements:

 a keyword identifying the argument (end here);
 an equal sign (=); 
and a value assigned to that argument;

any keyword arguments have to be put after the last positional argument (this is very important)

## EXAMPLE 1

In our example, we have made use of the end keyword argument, and set it to a string containing one space.

## EXAMPLE 3
We said previously that the print() function separates its outputted arguments with spaces. This behavior can be changed, too.

The keyword argument that can do this is named sep (as in separator).
## EXAMPLE 4
Modify the code to output the following  using sep and end 
 
Programming***Essentials***in...Python

## Example 5 


minimize the number of print() function invocations by inserting the \n sequence into the strings;
make the arrow twice as large (but keep the proportions)
duplicate the arrow, placing both arrows side by side; note: a string may be multiplied by using the following trick: "string" * 2 will produce "stringstring" (we'll tell you more about it soon)
remove any of the quotes, and look carefully at Python's response; pay attention to where Python sees an error ‒ is this the place where the error really exists?
do the same with some of the parentheses;
change any of the print words into something else, differing only in case (e.g., Print) ‒ what happens now?
replace some of the quotes with apostrophes; watch what happens carefully.

## SUMMARY OF LITERALS

 Literals are notations for representing some fixed values in code. Python has various types of literals - for example, a literal can be a number (numeric literals, e.g., 123), or a string (string literals, e.g., "I am a literal.").

 To encode an apostrophe or a quote inside a string, you can either use the escape character, e.g., 'I\'m happy.', or open and close the string using an opposite set of symbols to the ones you wish to encode, e.g., "I'm happy." to encode an apostrophe, and 'He said "Python", not "typhoon"' to encode a (double) quote.

 ## Operators 
                                 Divisiob

 A / (slash) sign is a division operator.

The value in front of the slash is a dividend, the value behind the slash, a divisor.

                                  Integer division (floor division)

A // (double slash) sign is an integer division operator. It differs from the standard / operator in two details:

its result lacks the fractional part ‒ it's absent (for integers), or is always equal to zero (for floats); this means that the results are always rounded;
it conforms to the integer vs. float rule.
NOTE :

The result of integer division is always rounded to the nearest integer value that is less than the real (not rounded) result.

This is very important: rounding always goes to the lesser integer
The result is two negative twos. The real (not rounded) result is -1.5 in both cases. However, the results are the subjects of rounding. The rounding goes toward the lesser integer value, and the lesser integer value is -2, hence: -2 and -2.0.
  