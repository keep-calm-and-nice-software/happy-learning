# What else?

Happy reading! ;)

## 4 rules of simple design

From [BeckDesignRules](https://martinfowler.com/bliki/BeckDesignRules.html), by Martin Fowler:

> The most important of the rules is "passes the tests". XP was revolutionary in how it raised testing to a first-class activity in software development, so it's natural that testing should play a prominent role in these rules. The point is that whatever else you do with the software, the primary aim is that it works as intended and tests are there to ensure that happens.

> "Reveals intention" is Kent's way of saying the code should be easy to understand. Communication is a core value of Extreme Programing, and many programmers like to stress that programs are there to be read by people. Kent's form of expressing this rule implies that the key to enabling understanding is to express your intention in the code, so that your readers can understand what your purpose was when writing it.

> The "no duplication" is perhaps the most powerfully subtle of these rules. It's a notion expressed elsewhere as DRY or SPOT, Kent expressed it as saying everything should be said "Once and only Once." Many programmers have observed that the exercise of eliminating duplication is a powerful way to drive out good designs.

> The last rule tells us that anything that doesn't serve the three prior rules should be removed. At the time these rules were formulated there was a lot of design advice around adding elements to an architecture in order to increase flexibility for future requirements. Ironically the extra complexity of all of these elements usually made the system harder to modify and thus less flexible in practice.

From [Essential XP: Emergent Design](https://ronjeffries.com/xprog/classics/expemergentdesign/), by Ron Jeffries:

> There are many well-known modeling and design techniques that can be used to bring about a "good design". An incremental process may limit the applicability of these techniques, which are most powerful when applied and committed to "up front". Test everything; eliminate duplication; express all ideas; minimize entities:These few simple rules, applied locally, can help a high quality global design to emerge.

From [The Four Elements of Simple Design](https://blog.jbrains.ca/permalink/the-four-elements-of-simple-design), by J.B. Rainsberger:

> I have reduced everything I've ever learned about modular design to the four elements of simple design that I first learned from Kent Beck’s work. Maybe you can, too.

## Further reading, by Martin Fowler

- From [Is Design Dead?](https://martinfowler.com/articles/designDead.html):

> These enabling practices of continuous integration, testing, and refactoring, provide a new environment that makes evolutionary design plausible. However one thing we haven't yet figured out is where the balance point is. I'm sure that, despite the outside impression, XP isn't just test, code, and refactor. **There is room for designing before coding**. Some of this is before there is any coding, most of it occurs in the iterations before coding for a particular task. But there is a new balance between up-front design and refactoring.

> Two of the greatest rallying cries in XP are the slogans **"Do the Simplest Thing that Could Possibly Work"** and "You Aren't Going to Need It" (known as YAGNI). Both are manifestations of the XP practice of Simple Design.

- From [DesignStaminaHypothesis](https://martinfowler.com/bliki/DesignStaminaHypothesis.html):

> Design activities certainly do take up time and effort, but they payoff because they make it easier to evolve the software into the future. You can save short-term time by neglecting design, but this accumulates [TechnicalDebt](https://martinfowler.com/bliki/TechnicalDebt.html) which will slow your productivity later. Putting effort into to the design of your software improves the stamina of your project, allowing you to go faster for longer.

- From [SelfTestingCode](https://martinfowler.com/bliki/SelfTestingCode.html):

> You have self-testing code when you can run a series of automated tests against the code base and be confident that, should the tests pass, your code is free of any substantial defects.

> Self-testing code is a key part of [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html), indeed I say that you aren't really doing continuous integration unless you have self-testing code. As a pillar of Continuous Integration, it is also a necessary part of [Continuous Delivery](https://martinfowler.com/delivery.html).

> One obvious benefit of self-testing code is that it can drastically reduce the number of bugs that get into production software. At the heart of this is building up a testing culture that where developers are naturally thinking about writing code and tests together.

## Good to know @ PHP

- The [PHP Standard Recommendations (PSR)](https://www.php-fig.org/psr/) serve the standardization of programming concepts in PHP. The aim is to enable interoperability of components and to provide a common technical basis for implementation of proven concepts for **optimal programming and testing practices**. The PHP-FIG is formed by several PHP frameworks founders.

- Symfony enforces [Coding Standards](https://symfony.com/doc/current/contributing/code/standards.html) "to make every piece of code look and feel familiar". The [PHP Coding Standards Fixer (PHP CS Fixer) tool](https://github.com/FriendsOfPHP/PHP-CS-Fixer) fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, etc., or other community driven ones like the Symfony one. You can also define your (team's) style through configuration.

- [PHPUnit - Chapter 10. Testing Practices](https://phpunit.de/manual/6.5/en/testing-practices.html) mentions the **4 rules of simple design**…

    > The following conditions will help you to improve the code and design of your project, while using unit tests to verify that the refactoring's transformation steps are, indeed, behavior-preserving and do not introduce errors:
    >
    > - All unit tests run correctly.
    > - The code communicates its design principles.
    > - The code contains no redundancies.
    > - The code contains the minimal number of classes and methods.

    … and suggests **Test-Driven Development**:

    > When you need to add new functionality to the system, write the tests first. Then, you will be done developing when the test runs. This practice will be discussed in detail in the next chapter.

- [PHPStan](https://github.com/phpstan/phpstan) is a static analysis tool which allows you to discover bugs in your code without running it.
