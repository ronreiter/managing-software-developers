# The 80/20 Approach and Managing Technical Debt

Perhaps the most commonly used software development methodology is the 80/20 approach. I am sure you have heard of it before - but if you haven't, there's still a good chance you are doing it but just calling it something else. 

The 80/20 approach states that the most efficient way of starting out is not by doing things perfectly, but rather doing them good enough to start out with, therefore gaining immense benefit over little time. 80/20 means that you could usually gain 80% of the benefit of doing something by investing 20% of the time required to do it perfectly, whereas the remaining 20% would take you 80% of the time.

A good example is cleaning up files on your hard drive. The correct approach would not be to go over ALL of the files on your hard drive, but rather sorting them by size, investing a few minutes reviewing only the large files, and deleting those that you don’t need anymore. The realization of ordering the files by significance saves us a lot of time because using the same amount of time on smaller files will yield a smaller outcome. This realization is the secret behind the 80/20 approach - do what’s important first, and stop when things become less efficient, in favor of utilizing your time for other things.

The same exact approach can be applied to software engineering and management. The most classic example of where the 80/20 approach should be applied, is when developing software. This is because of two reasons:

1. Product requirements constantly change, especially in start-ups. A product requirement dictates which software should be implemented and how. This means that assuming that your code will stay relevant is not a good assumption. Therefore - why should you invest a lot of time perfecting software that there’s a high chance you will end up not using anymore?
2. Technical teams learn what to invest in and what not to invest in during the development cycle, and not in the design phase, because it’s just too difficult to completely understand what is the optimal design of a system.

This is usually why building prototypes and not investing in software is actually a good thing and not a bad thing. As you progress with software development, you will find out that you and/or your team has new ideas for improvements all the time. You must be always committed to stashing those ideas to the backlog instead of pulling the deadlines further ahead.

The downside of writing sloppy code is obvious - technical debt. Bad code is unmaintainable, and sometimes requires not only refactoring to fix but rather full rewrites to get things right. There’s a misconception that this is a bad thing. It is not. Rewriting code might end up the right thing to do, because of a few reasons:

1. It is faster to rewrite code rather than to refactor it, because rewriting it gives full visibility and control over to the programmer and because he does not need to worry about breaking an existing system.
2. It gives you the opportunity to rethink more things, that might end up saving more time by further reducing technical debt.
3. It gives the developer the agility to write the code in a way that is more convenient for him, for example using a more suitable programming language.

What’s important to realize is that you should not be attached to your code - writing the code is merely a way of achieving your goal. Whenever your goal can be achieved quicker by rewriting things, it should always be considered as an option. This is especially true in today’s world where open source dominates and a lot of systems can achieve simplicity by using open source components and tools that were developed in-house just because they weren’t available at the time of writing the original code.

But when does this approach impose a problem that needs to be addressed? when rewriting the code is too much work that the business cannot prioritize. In this case, the code must be fixed slowly, and over time. This is done by building a solid plan that allows a software manager to take small chunks of technical debt and get rid of them by refactoring or fixing the code as part of larger features. When the system is mature enough and the code has proven to be required for the business, you should commit to yourself that every new feature will only reduce technical debt, instead of increase it.

![Technical Debt](images/techdebt.png)

Writing the code without technical debt from the beginning does save the time required to remove the technical debt later on. But statistically, the code that ends up being used over time is hard to identify at first, which is why you should usually assume that it is OK to accumulate technical debt.

Another approach to handling technical debt is to pursuade the business stakeholders and product managers that R&D needs to go into a year-long project to rearchitect the existing system. In this case, an engineering manager will effectively take the role of the "technical product manager" and plan a new system that will take on the older one, and will have to justify the resource and time allocation that is required to do so. This approach is only possible after the existing system has either proven to be required in the long term future of the company, or that the current operational overhead must be immediately addressed so that the existing business will not be negatively impacted. For example - if immediate scaling is required but the system that was built is not scalable, then the decision makers will simply have to agree to the project.

If the complete rewrite approach is taken, then an engineering manager would likely have to present a solid, time boxed plan, which has very strict goals and advantages over the current system.

