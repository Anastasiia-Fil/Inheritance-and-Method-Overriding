
In this program, I created a base class called Animal and then made Dog, Fish, and Shark from it.

Animal has basic things like name and number of legs, and also some methods like getting the name,
legs, and a special ability.

Dog and Fish are simple child classes. They just change the special ability:
Dog says "Woof", and Fish says "Just keep swimming".

Shark is a bit different. It takes the last created animal and "eats" it.
So when we create a Shark, we pass another animal into it, and then it prints
something like "Shark ate Dog".

In the main part of the program, the user types commands like "dog", "fish", or "shark".
The program creates that animal and remembers the last one.
When "shark" is used, it uses the previous animal.

After each command, the program prints the animal info and its special ability.

This shows how inheritance works, how we override methods, and how objects can interact with each other.
