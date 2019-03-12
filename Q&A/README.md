## Questions asked in the Group
* I wanted to know if there are any pitfalls to using other languages, since I wanted to avoid learning a new language. However Raza gave a good explanation above, that SICP takes the FP approach for its contents. 
A: Okay.

so. LISP is not a pure functional proramming language. What makes a programming language "pure" is the ability to write side-effect free functions or writing pure functions. LISP is not a pure functional programming langugae since it allows you to write non-pure functions. 

If you want to learn a pure functional programming language then Haskell would be better choice. 

That said, Using scheme for the book is cool because that is what the book was made for. Sure you can use another dialect of LISP but there are minor nuances where the results might be different (like evaluation strategy and laziness, type system etc etc). 

As for using any other language that supports "functional programming" (which as of now i think most programming languages do).... it will get too weird too fast.

and w.r.t. programming languages, what is "modern" depends on the kind of job. 

Fortan is still used in some of the most cutting edge computing systems all over the world. It is the oldest programming language. 😊

Similarly LISP started out one year later than Fortran in the MIT AI lab and we are still talking about it. 

I generally refrain from jumping on the latest stuff because personally I feel I can understand the design choices better iff (if and only if) I understand what was wrong with the "old" programming language in the first place.  Like.. there must be a reson why Clojure was created right ? And tbh at this level the differences are so nuanced that we wont even know the difference. 😊

So. tl;dr. Choose whatever LISP dialect/implementation you want. (but try to stick as closely to scheme). 😊


ALSO. 
Lisp is called a meta programming language. Which means. 

you can change the program at run time. 

a very very very basic example is to redefine define to be something else.

try it. 


(you will need to restart your REPL after that. )
