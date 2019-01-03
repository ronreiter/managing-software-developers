# Developers Fail, Methodologies Don't

How do you deal with the fact that developers are inherently unreliable? 

I have met managers that get frustrated from these things, and think that the developers are to blame. Then, they start counting the number of failures and change their attitude to show their dissatisfaction to the point where managing the developer is impossible, and the engineer would either quit or get fired. But the reality is that developers have a certain degree of inherent uncertainty in their output, and they will always produce bugs and inaccurate code. It is on the hands of us, the engineering managers, to turn developers who make mistakes into teams that don't make mistakes.

This is possible, at least to a high degree, using good software development methodologies. 

There are several methodologies we can incorporate so that our teams won't fail:

1. Code reviews - probably the one that would catch the least amount of failures, code reviews are important more for the sake of aligning the code to how it's supposed to be written versus finding bugs.
2. Testing - the most obvious one, but also more geared at preserving the code so it won't break.
3. Validation process - The most important and best way of ensuring that developers don't fail. The validation process is the gating process that verifies that the feature which was implemented actually meets the requirements.

The validation process is the key methodology for ensuring that the output of your team is accurate. Building the validation step requires implementing as many real-world scenarios as you can think of (and that you have time to test), and then ask the developer who implemented the feature to run through.

For example, a classic task for a developer would be to implement a program that writes out the fibonacci sequence. You can then ask your developer to Google the first 100 fibonacci numbers, copy then into a text file, and then use the diff tool to compare the output of their program to the result in Google. You should then ask your developer to send you the output of the diff to see the output for yourself. 

The key here is that you can build small ad-hoc tests that are easy for you to know what to expect, and therefore verify that the code written actually does what it's supposed to do. The difference between asking for this versus writing tests that do the same, is that tests can be wrong themselves, and tests are usually geared at checking that the logic that was written was not broken, rather than checking that the tests produce the output that was required from the product manager.

