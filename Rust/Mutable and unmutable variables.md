In rust there is a difference compared to C, in rust for you to change the value of a variable you need to use an special function called mut, that indicate the variable value can be changed.

The unmutable variables, are variables that don't have the mut declaration, if the variable don't have that, you can't change it value and even can't compile it.

Something that i found intersting, its that you can do something like first making all variables mutables, but, still that don't affect it [[Ownership]] over a value. Its like you can change the battery of my pc, but that don't mean that you are the owner of my PC.
