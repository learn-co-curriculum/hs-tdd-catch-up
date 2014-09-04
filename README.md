---
tags: tdd
type: catch-up
---
#Catch Up!
Missed the class on TDD. Not to worry, amigo. Here's what you need to know.

<img src="http://oversimplified.net/comics/2011-04-28.tdd_.png">

In a nutshell, TDD  isa way that developers work to build high quality programs and prevent errors/bugs from developing in the program. Developers first write tests that check to make sure that their code is doing what it’s supposed to be doing.

Tests are written using a program called Rspec (among others), and the tests can be found in files ending in `spec.rb`. For example, if you have a ruby file called `test.rb`, the tests would be written in a file called `test_spec.rb`.

To run tests, go to the root of your project and type `rspec` - The tests will run and you'll see the failures that you have to work on.

Failures are good. Let me repeat: FAILURES ARE GOOD. They are breadcrumbs on the path to success. Read the failures carefully, change your code, and run `rspec` again until everything is passing.

Try working through the tests in [test-first ruby](http://testfirst.org/learn_ruby). It gets progressively harder, so don't get discouraged if you feel stuck!