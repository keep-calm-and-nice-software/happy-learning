# Further reading by Martin Fowler

- From [Is Design Dead?](https://martinfowler.com/articles/designDead.html):

> These enabling practices of continuous integration, testing, and refactoring, provide a new environment that makes evolutionary design plausible. However one thing we haven't yet figured out is where the balance point is. I'm sure that, despite the outside impression, XP isn't just test, code, and refactor. **There is room for designing before coding**. Some of this is before there is any coding, most of it occurs in the iterations before coding for a particular task. But there is a new balance between up-front design and refactoring.

> Two of the greatest rallying cries in XP are the slogans **"Do the Simplest Thing that Could Possibly Work"** and "You Aren't Going to Need It" (known as YAGNI). Both are manifestations of the XP practice of Simple Design.

- From [DesignStaminaHypothesis](https://martinfowler.com/bliki/DesignStaminaHypothesis.html):

> Design activities certainly do take up time and effort, but they payoff because they make it easier to evolve the software into the future. You can save short-term time by neglecting design, but this accumulates [TechnicalDebt](https://martinfowler.com/bliki/TechnicalDebt.html) which will slow your productivity later. Putting effort into to the design of your software improves the stamina of your project, allowing you to go faster for longer.

- From [SelfTestingCode](https://martinfowler.com/bliki/SelfTestingCode.html):

> You have self-testing code when you can run a series of automated tests against the code base and be confident that, should the tests pass, your code is free of any substantial defects.

> Self-testing code is a key part of [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html), indeed I say that you aren't really doing continuous integration unless you have self-testing code. As a pillar of Continuous Integration, it is also a necessary part of [Continuous Delivery](https://martinfowler.com/delivery.html).

> One obvious benefit of self-testing code is that it can drastically reduce the number of bugs that get into production software. At the heart of this is building up a testing culture that where developers are naturally thinking about writing code and tests together.
