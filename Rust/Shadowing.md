Basically, in rust you can "for shadow" a variable. Imagine that you write something like:
let number: i32 = 4;

And, after that you repeat the same name, in this case number:
let number: i32 = 5;

The compiler will use the second one(you need to use let again if you want to do the shadowing of the variable). Something curios is that this thing don't break the [[Mutable and unmutable variables]] property, since you are not reassign the value of the variable, its still a bit confusing to me, but its simple in its root

[[Variable types]]
[[Rust]]