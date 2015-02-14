#Learn To Code C

## Goals
 - Understand the topics listed in the curriculum.
 - Complete a [personal project][project-ideas] written in C.
 - Contribute to an [open source project that is written in
   C][open-source-c-projects].

[open-source-c-projects]: notes/meta/open_source_projects.md
[project-ideas]: notes/meta/project_ideas.md

## Week 1: Compilation
 - [Why Learn C?][why-learn-c]
 - Compiling and Running C Programs
   - [gcc demo][gcc-demo]
   - [clang demo][clang-demo]
   - [clang versus gcc][clang-vs-gcc] from clang.llvm.org
 - [The "Main" Function][main]
 - **Exercises:**
   - [Hello World][hello-world]
   - [Formatted Printing][learn-c-hard-way-ex-3] from "Learn C The Hard Way"
     (Ignore the comments about using Make.)
   - [Fahrenheit to Celsius][k-r-p8] from "The C Programming Language" (p.  8-14)
   - [Fizz Buzz][fizz-buzz]
   - **Bonus:** [Euler Problem #1: Multiples of 3 and 5][euler-1]
   - **Bonus:** [Euler Problem #2: Even Fibonacci Numbers][euler-2]
   - **Bonus:** [Euler Problem #3: Largest Prime Factor][euler-3]


[why-learn-c]: notes/intro/why_learn_c.md
[gcc-demo]: notes/intro/gcc-demo.md
[clang-demo]: notes/intro/clang-demo.md
[clang-vs-gcc]: http://clang.llvm.org/comparison.html#gcc
[main]: notes/intro/main_function.md
[hello-world]: exercises/intro/hello_world.md
[fizz-buzz]: exercises/intro/fizz_buzz.md
[learn-c-hard-way-ex-3]: http://c.learncodethehardway.org/book/ex3.html
[k-r-p8]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf#page=22
[euler-1]: https://projecteuler.net/problem=1
[euler-2]: https://projecteuler.net/problem=2
[euler-3]: https://projecteuler.net/problem=3

## Week 2: Basics Part 1
 - [Variable Declaration][variables]
 - [Strings in C][c-strings]
 - [Data Types][data-types]
   - **Exercise:** [Types of Variables][learn-c-hard-way-ex-6] from "Learn C The Hard Way"
   - **Exercise:** [Finding the Size of Data Types][finding-size-of]
 - Conditionals *(TODO)*
 - Loops *(TODO)*
   - **Exercise:** [Word Counter][k-r-p20] from "The C Programming Language" (p.  20-22)
 - Printing *(TODO)*
 - [Arithmetic Operations][arithmetic-operations] from "The C Programming Language" (p.41)
   - **Exercise:** [More Variables, Some Math][learn-c-hard-way-ex-7] from "Learn C The Hard Way"
   - **Exercise:** Basic Calculator *(TODO)*
 - External Variables *(TODO)*
   - **Exercise:** [RPN Calculator][k-r-p74] from "The C Programming Language" (p.74-79)
 - [C Snacks (Tips and Tricks)][c-snacks]

[variables]: notes/intro/variables.md
[c-strings]: notes/intro/strings.md
[data-types]: notes/intro/data_types.md
[learn-c-hard-way-ex-6]: http://c.learncodethehardway.org/book/ex6.html
[finding-size-of]: exercises/data_types/finding_size_of.md
[k-r-p20]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf#page=34
[arithmetic-operations]: notes/intro/arithmetic_operations.md
[learn-c-hard-way-ex-7]: http://c.learncodethehardway.org/book/ex7.html
[k-r-p74]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf#page=74
[c-snacks]: notes/intro/c_snacks.md

## Week 3: Basics Part 2
 - Arrays *(TODO)*
 - Functions *(TODO)*
 - More About Data Types *(TODO)*
 - Type Conversion *(TODO)*
 - **exercise**s *(TODO)*

## Week 4: C Specific Basics
 - [C Libraries][c-libraries]
 - Using multiple files in a project *(TODO)*
   - **Exercise:** [Variations of Fizz Buzz][fizz-buzz-variations]
 - [Make Files][make-files] *(TODO)*
   - **Exercise:** [Make some Makefiles][makefile-exercise]
 - sizeof and memory allocation *(TODO)*
   - **Exercise:** Caesar Cipher *(TODO)*

[c-libraries]: notes/intro/libraries_intro.md
[fizz-buzz-variations]: exercises/organizing_code/fizz_buzz_variations.md
[makefile-exercise]: exercises/organizing_code/makefiles.md
[reserved-keywords]: notes/intro/reserved_keywords.md

## Week 5: Pointers and Standard Libraries
 - Pointers *(TODO)*
 - Standard Libraries *(TODO)*
 - **exercise**s *(TODO)*

## Week 6: Memory Allocation
 - *(TODO)*

## Week 7: Data Types
 - [Structs][structs-intro]
 - Unions *(TODO)*
 - Enums *(TODO)*
 - **exercise**s *(TODO)*

[structs-intro]: notes/data_structures/structs.md

## Week 8: Advanced Topic
 - Bitwise Operations or Buffer Overflow *(TODO)*

###Bonus Material:

###Small Tools
 - [Small Tools Intro][small-tools-intro]
 - [Data Streams][data-streams]
 - [Command Line Options & Arguments][command-line-options]
   - **Exercise:** [Tip Calculator][tip-calculator]
   - **Exercise:** [D&D Character Generator][character-generator]

[small-tools-intro]: notes/small_tools/small_tools_intro.md
[data-streams]: notes/small_tools/data_streams.md
[command-line-options]: notes/small_tools/command_line_options.md
[tip-calculator]: exercises/command_line_opts_args/tip_calculator.md
[character-generator]: exercises/command_line_opts_args/character_generator.md

###Resources

Much of the material for this course was drawn from the following:
 - ["The C Programming Language"][k-r-main] by Brian W. Kernighan and Dennis M.  Ritchie
 - ["Learn C The Hard Way"][learn-c-hard-way-main] by Zed Shaw

[k-r-main]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf
[learn-c-hard-way-main]: http://c.learncodethehardway.org/book/

###License
[MIT License][mit-license]

[mit-license]: ./MIT-LICENSE
