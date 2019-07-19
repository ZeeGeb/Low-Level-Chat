Pointers
========

Apparently the hardest part of C but that is just a lie told by the government.

## An introduction to how stuff actually works

First of all before pointers will make sense I want to explain what a "variable" actually is. Upon compile time "variables" like `x`, `y` and `godPleaseHelpMe` and translated to numbers representing addresses in memory.

It might be mapped like so for example:

1. `x` becomes the address `77`
2. `y` becomes the address `88`
3. `godPleaseHelpMe` becomes the address `99`

The way memory works is that you can give it an address, like `77` and then tell it to save a value at that address like `69` for example. Or maybe at address `88` we decide to store the value `255` and so on.

The way you visualise this at the C-level is `x = 69` but what is really happening is that the value of `69` is being set at address `77`.