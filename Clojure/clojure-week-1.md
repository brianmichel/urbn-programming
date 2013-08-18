Clojure Week 1
=====

Welcome! Let's talk!

What is it?
----

It's Lisp-y, meaning it's going to look weird if you've never used a similar language or dialect. Let's look at some code...

    (+ 9 10)

For those familiar, this is Polish Notiation (PN for short). This may seem a little weird, but really it's similar to other languages in that you evaluate what's in the parenthesis first, let's see another example...

    * (- 5 6) 7

This more commonly would look like this `5-6 * 7`, if anythig PN has removed any ambiguity as to how to process this statement. 

Secondly, this language is functional*, meaning that once you assign a value to a variable, you can't reassign it, in short, variables are immutable. Additionally, Clojure runs on the JVM, and the CLR, and Javascript! Which is pretty cool. This means that theoretically we could deploy Clojure code on our existing JVM stack without ops knowing the wiser :)

Lastly, you can use existing Java sources with Clojure, which is great, becuase there is LOTS of Java code already in the wild (our stuff included).