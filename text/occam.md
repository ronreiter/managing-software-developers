# Occam's Razor

Occam's Razor is a philosophical principle that states the following:

>  Suppose there exist two explanations for an occurrence. In this case the one that requires the least speculation is usually better. Another way of saying it is that the more assumptions you have to make, the more unlikely an explanation. 

To summarize, Occam's Razor is a theoretical tool that guides us to choose the simplest solution for a given problem that can properly solve the problem. Or in other words, don't overcomplicate the system you are building more than you must.

In the software world, as we are given the requirements of the system we need to build, we are often faced with a dillema of building a generic system vs a specific system. The generic system would be more flexible, more abstract, be open to change and to new requirements, whereas the specific system will be simpler, easier to understand and maintain, hard to extend and prone to tech debt accumulation.

The philisophical analogy isn't accurate of course. Occam's Razor is a guideline for choosing the "right" theory, whereas in the software development world we just aim to make a more efficient choice.

It's not easy to make a decision on how generic vs how specific you should write your system as. The software development version of Occam's Razor tells us we should be focusing our efforts to build a system which is complex at just the right amount - no less, no more. It has to be at least as complex as it needs to be to fulfill the requirements, but it also should not be more complex than it should be.

But what does it mean "no more complex than it should be"? There are several reasons to make a system more complex than the initial requirements require it to be:

1. Extensibility - as new features are required to be developed, a more generic system will be able to accumulate less technical debt if written properly.
2. Simplicity - more generic systems tend to be more readable and rely more on configuration rather than hard-coded logic and values.
3. Reusability - more generic systems can be reused in other places where there are other but similar requirements. Another advantage in writing reusable code is that developers can open source the code and make their system into a community supported system - both for maintenance purposes and fame/recruitment purposes.

However, there are also downsides for doing this:

1. More generic systems simply require more time to design and develop.
2. Maintenance - more generic systems require more maintenance, as it often means that more changes are required in the code to get to the same result.
3. Learning curve - more generic systems require that developers learn more about how the system works before being comfortable with making changes.
4. Focus on the technology rather than the business needs - more generic systems tend to attract developers to enhance the system in ways that may not benefit the business needs directly, as there's more ability to extend and upgrade the system. A more specific system would often be focused on the specific use case at hand.
5. Throwaway code - systems tend to be temporary, so a larger investment than needed can be a waste of development effort. 

Throwaway code is often overlooked at development teams as they usually don't feel like they are accountable to the overall resource spend of the business. Often times the engineering manager often does not even have the ability to predict the chances of the code being thrown away. The guideline should be "don't write a generic system for the first version of the system". When you're a start-up - it's better to get something out the door sooner rather than later, and you'll be lucky if something sticks. 

Here's an example: Let's say you have the option of writing three specific systems and one generic system using one man-month. It would be better to write all three specific systems, and later on understand that only system #2 needs to be developed into a generic system (which costs us two months), compared to spending three months of writing three generic systems and throwing away two of them. Of course this is a very theoretical example, but the example should guide you to look at the ratio between writing a generic system versus a specific system, as well as the chances for the system to stick around for the long term according to the needs of the business. Once you can calculate the odds, you can make the decision.

 