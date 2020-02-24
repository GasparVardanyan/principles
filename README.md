# Coding principles
## Software development philosophies and programming principles
### Minimalism
In computing, minimalism refers to the application of minimalist philosophies and principles in the design and use of hardware and software. Minimalism, in this sense, means designing systems that use the least hardware and software resources possible.

[Wikipedia](https://en.wikipedia.org/wiki/Minimalism_(computing))
### Worse is better
*In The Rise of Worse is Better, Gabriel claimed that "Worse-is-Better" is a model of software design and implementation which has the following characteristics (in approximately descending order of importance):*
* **Simplicity**. The design must be simple, both in implementation and interface. It is more important for the implementation to be simple than the interface. Simplicity is the most important consideration in a design.
* **Correctness**. The design should be correct in all observable aspects, but It is slightly better to be simple than correct.
* **Consistency**. The design must not be overly inconsistent. Consistency can be sacrificed for simplicity in some cases, but it is better to drop those parts of the design that deal with less common circumstances than to introduce either complexity or inconsistency in the implementation.
* **Completeness**. The design must cover as many important situations as is practical. All reasonably expected cases should be covered. Completeness can be sacrificed in favor of any other quality. In fact, completeness must be sacrificed whenever implementation simplicity is jeopardized. Consistency can be sacrificed to achieve completeness if simplicity is retained; especially worthless is consistency of interface.

Gabriel argued that early **Unix** and **C**, developed by **Bell Labs**, are **examples** of this **design approach**.

[Wikipedia](https://en.wikipedia.org/wiki/Worse_is_better)
### KISS (keep it simple, stupid)
The KISS principle states that most systems work **best** if they are kept **simple** rather than made **complicated**; therefore, **simplicity** should be a **key** goal in design, and unnecessary **complexity** should be **avoided**.

[Wikipedia](https://en.wikipedia.org/wiki/KISS_principle)
### The Sucksless' philosophy (manifest)
>Many (open source) hackers are proud if they achieve large amounts of code, because they believe the more lines of code they've written, the more progress they have made. The more progress they have made, the more skilled they are. This is simply a delusion.
>
>Most hackers actually don't care much about code quality. Thus, if they get something working which seems to solve a problem, they stick with it. If this kind of software development is applied to the same source code throughout its entire life-cycle, we're left with large amounts of code, a totally screwed code structure, and a flawed system design. This is because of a lack of conceptual clarity and integrity in the development process.
>
>Code complexity is the mother of bloated, hard to use, and totally inconsistent software. With complex code, problems are solved in suboptimal ways, valuable resources are endlessly tied up, performance slows to a halt, and vulnerabilities become a commonplace. The only solution is to scrap the entire project and rewrite it from scratch.
>
>The bad news: quality rewrites rarely happen, because hackers are proud of large amounts of code. They think they understand the complexity in the code, thus there's no need to rewrite it. They think of themselves as masterminds, understanding what others can never hope to grasp. To these types, complex software is the ideal.
>
>Ingenious ideas are simple. Ingenious software is simple. Simplicity is the heart of the Unix philosophy. The more code lines you have removed, the more progress you have made. As the number of lines of code in your software shrinks, the more skilled you have become and the less your software sucks.

[Website](https://suckless.org/philosophy/)
### The Unix philosophy
The Unix philosophy, originated by Ken Thompson, is a set of cultural norms and philosophical approaches to minimalist, modular software development.
The Unix philosophy emphasizes building **simple**, **short**, **clear**, **modular**, and **extensible** code that can be **easily** maintained and repurposed by developers other than its creators. The Unix philosophy favors composability as opposed to monolithic design.

[Wikipedia](https://en.wikipedia.org/wiki/Unix_philosophy)
### The Elements of Programming Style
* Write clearly -- don't be too clever.
* Say what you mean, simply and directly.
* Use library functions whenever feasible.
* Avoid too many temporary variables.
* Write clearly -- don't sacrifice clarity for efficiency.
* Let the machine do the dirty work.
* Replace repetitive expressions by calls to common functions.
* Parenthesize to avoid ambiguity.
* Choose variable names that won't be confused.
* Avoid unnecessary branches.
* If a logical expression is hard to understand, try transforming it.
* Choose a data representation that makes the program simple.
* Write first in easy-to-understand pseudo language; then translate into whatever language you have to use.
* Modularize. Use procedures and functions.
* Avoid gotos completely if you can keep the program readable.
* Don't patch bad code -- rewrite it.
* Write and test a big program in small pieces.
* Use recursive procedures for recursively-defined data structures.
* Test input for plausibility and validity.
* Make sure input doesn't violate the limits of the program.
* Terminate input by end-of-file marker, not by count.
* Identify bad input; recover if possible.
* Make input easy to prepare and output self-explanatory.
* Use uniform input formats.
* Make input easy to proofread.
* Use self-identifying input. Allow defaults. Echo both on output.
* Make sure all variables are initialized before use.
* Don't stop at one bug.
* Use debugging compilers.
* Watch out for off-by-one errors.
* Take care to branch the right way on equality.
* Be careful if a loop exits to the same place from the middle and the bottom.
* Make sure your code does "nothing" gracefully.
* Test programs at their boundary values.
* Check some answers by hand.
* 10.0 times 0.1 is hardly ever 1.0.
* 7/8 is zero while 7.0/8.0 is not zero.
* Don't compare floating point numbers solely for equality.
* Make it right before you make it faster.
* Make it fail-safe before you make it faster.
* Make it clear before you make it faster.
* Don't sacrifice clarity for small gains in efficiency.
* Let your compiler do the simple optimizations.
* Don't strain to re-use code; reorganize instead.
* Make sure special cases are truly special.
* Keep it simple to make it faster.
* Don't diddle code to make it faster -- find a better algorithm.
* Instrument your programs. Measure before making efficiency changes.
* Make sure comments and code agree.
* Don't just echo the code with comments -- make every comment count.
* Don't comment bad code -- rewrite it.
* Use variable names that mean something.
* Use statement labels that mean something.
* Format a program to help the reader understand it.
* Document your data layouts.
* Don't over-comment

[Wikipedia](https://en.wikipedia.org/wiki/The_Elements_of_Programming_Style)
### DRY (don't repeat yourself)
> Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.

[Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
### YAGNI (you aren't gonna need it)
> Always implement things when you actually need them, never when you just foresee that you need them.

[Wikipedia](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
## Coding style
I am coding in my own coding style.
## See also
* [Bell Labs](http://doc.cat-v.org/bell_labs/)
* [Unix](http://doc.cat-v.org/unix/)
* [Plan9](https://9p.io/plan9/) ([[1]](http://doc.cat-v.org/plan_9/))
* [9base](https://tools.suckless.org/9base/)
* [Mk](http://doc.cat-v.org/bell_labs/mk/)
* [OpenBSD](https://www.openbsd.org/)
* [Software that sucks less](https://suckless.org/)
* Text editors [vi](http://ex-vi.sourceforge.net/), [vis](https://github.com/martanne/vis), [ed](https://github.com/openbsd/src/tree/master/bin/ed), [sam](https://github.com/deadpixi/sam).
* Document compilers [troff](https://troff.org/), [mandoc](http://mandoc.bsd.lv/).
* [Stuff that rocks](https://suckless.org/rocks/)
* [Stuff that sucks](https://suckless.org/sucks/)
* [List of harmful software](http://harmful.cat-v.org/software/)
* [GNU is Not Usable](http://harmful.cat-v.org/software/GNU/)
* [Object Oriented Programming is Inherently Harmful](http://harmful.cat-v.org/software/OO_programming/)
    * [Why OO Sucks by Joe Armstrong](http://harmful.cat-v.org/software/OO_programming/why_oo_sucks)
* [C++ is Good for the Economy, It Creates Jobs!](http://harmful.cat-v.org/software/c++/)
    * [Bjarne Stroustrup: “I Did It For You All…”](http://harmful.cat-v.org/software/c++/I_did_it_for_you_all)
    * [C++ in Coders at Work](http://harmful.cat-v.org/software/c++/coders-at-work)
    * [Linus Torvalds on C++](http://harmful.cat-v.org/software/c++/linus)
    * [Richard Stallman Agrees That C++ Sucks](http://harmful.cat-v.org/software/c++/rms)
* [Programming Quotes](http://quotes.cat-v.org/programming/)
