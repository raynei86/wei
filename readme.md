# wei
A C replacement with ease of implementation in mind.

---
## Goals
### Be simple
The syntax should be easy to parse.
This means changing a lot of C syntax to remove things like the Most Vexing Parse.
Macros and preprocessor are unnecessary, they require too much effort and are an unsafe mess anyways.

### Be opinionated
There should be only one way to do something.
Yeah, I'm making the programmer bend down to the language.
This simplifies implementation and makes *my* life easy :)

### Be sane
It should still be a language that's not painful to use.
Conveniences like slices, improved case statements and defer statements should be included.

### Be elegant
Now this can have a lot of different meanings.
I'm defining elegant as dumb and easy on the reader; something similar to Go and C.
You should be able to tell at a glance what a line looks like in assembly.

# License
Everything is licensed under [WTFPL](http://www.wtfpl.net/).
The code is on the internet, nobody is stopping you doing whatever with it.

