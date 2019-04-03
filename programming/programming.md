# Programming

## Notes

- In software engineering there are two things you are trying to get right:
  - Software Validation - Did we build the right thing?
  - Software Verification - Did we build the thing right?
- Software simplicity is a prerequisite to reliability.
- A small, simple API is usually also a hallmark of a well-understood problem.
- Run/Right/Fast.
  - Make the code work I write is working. Then I can make it fast (if necessary). Solving the “correct/clean/performant code” problem all at once can be overwhelming. Don’t be overwhelmed. Solve one at a time.
- Reducing the maintenance burden is, for most codebases, the biggest optimization I can do.
  - Of course it's all about striking a balance, but 99% of the time there is a choice between performance and readability, readability is the right answer. Performance should only be chosen if it is absolutely necessary.
- If I write ugly code, anyone who intends to fix a bug or add a feature will not enjoy his work and likely avoid it next time.
- Explicit over implicit is almost always better.
- [One of my principles is to always strive for simplicity when creating. In retrospect, I've learned many thing that I previously thought too complex to understand. The complexities tend to dissolve when you realize they are mostly just extra distractions emerging from the pressures of engineering the thing... distractions that you probably find yourself inventing all over again once you've assimilated the core idea.](https://news.ycombinator.com/item?id=16562827)
- Readme driven development is pretty neat. Write the README first as a specification. Then write the code for it. [Zeit](https://github.com/zeit) do it often.
- We are about to study the idea of a computational process. Computational processes are abstract beings that inhabit computers. As they evolve, processes manipulate other abstract things called data. The evolution of a process is directed by a pattern of rules called a program. People create programs to direct processes.
- Always be looking for patterns. Abstract them always and only when it simplifies.
- Persevere in getting an abstraction just right. When you find it, everything will magically fall into place.
- The implementation is the design.
- Hide whatever the caller shouldn't care about. In particular, you can remove type parameters with appropriate quantification.
- Declarative configuration means that you write down the desired state of the world in a configuration and then submit that configuration to a service that takes actions to ensure the desired state becomes the actual state.
- Every single feature makes product more complex, makes testing more complex, puts constraints on UI design etc. Controlling feature creep (also by revisiting old features) is very important to keep project healthy. Larger the project, more important it is.
- [“Simplicity” often just means that a concept fits cleanly in the maker’s head at a particular point in time. How many times have I returned to a project I thought was simple only to find I had burdened it with spooky magic because I didn’t benefit from critical distance at the time? When was the last time I deemed another person’s work “too complex” because I couldn’t understand it in one sitting and wasn’t aware of the constraints they were operating under? Answers: too often and too recently.](https://lobste.rs/s/qgbkwm/on_simplicity)

## Links

- [One Bite At A Time: Partitioning Complexity](https://www.facebook.com/notes/kent-beck/one-bite-at-a-time-partitioning-complexity/1716882961677894/)
- [Being A Developer After 40](https://medium.freecodecamp.org/being-a-developer-after-40-3c5dd112210c)
- [What's code?](https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/)
- [Portability matters](http://drewdevault.com/2017/11/13/Portability-matters.html)
- [On being an effective developer](https://carlosbecker.com/posts/on-being-an-effective-developer/)
- [Advice to the newish programmer](https://macwright.org/2018/02/08/advice-to-the-newish-programmer.html)
- [Comment Your Code](https://npf.io/2017/11/comments/)
- [Things You Should Never Do](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/)
- [Writing good bug reports](https://pspdfkit.com/blog/2016/writing-good-bug-reports/)
- [Tips for reading new codebases](https://blog.safia.rocks/post/170269021619/tips-for-reading-new-codebases)
- [Engineering Principles at Monzo](https://monzo.com/blog/2018/06/29/engineering-principles/)
- [Awesome Cold Showers](https://github.com/hwayne/awesome-cold-showers#readme) - For when people get too hyped up about things.
- [Fish Design Principles](https://fishshell.com/docs/current/design.html)
- [List of resources about programming practices for writing safety-critical software](https://github.com/stanislaw/awesome-safety-critical#readme)
- [In Pursuit of Production Minimalism](https://brandur.org/minimalism)
- [The 12 Factor App](https://12factor.net)
- [Mostly avoid unit tests](https://lobste.rs/s/trrold/mostly_avoid_unit_tests)
- [Software disenchantment](http://tonsky.me/blog/disenchantment/)
- [In search of software perfection - Xavier Leroy (2016)](https://www.youtube.com/watch?v=lAU5hx_3xRc)
- [Communicating Sequential Processes (CSP)](http://usingcsp.com/)
- [Ask HN: What's the largest amount of bad code you have ever seen work? (2018)](https://news.ycombinator.com/item?id=18442637)
- [HN: Please do not attempt to simplify this code (2018)](https://news.ycombinator.com/item?id=18772873)
- [HN: Minimalism: Practical Guide to Writing Less Code (2018)](https://news.ycombinator.com/item?id=18830732)
- [HN: Software Engineering at Google (2018)](https://news.ycombinator.com/item?id=18818412)
- [Professional Programming](https://github.com/charlax/professional-programming#readme) - Collection of full-stack resources for programmers.
- [Ask HN: What are must-know concepts for back end development? (2019)](https://news.ycombinator.com/item?id=18961793)
- [HN: Advice to new programmers (2019)](https://news.ycombinator.com/item?id=19029206)
- [Shipping code at N26 (2019)](https://hugogiraudel.com/2019/01/28/shipping-code-at-n26/)
- [Junior and senior engineers (2015)](https://luca3m.me/2015/07/04/junior-vs-senior-engineers.html)
- [Ask HN: How to be productive with big existing code base (2019)](https://news.ycombinator.com/item?id=19254008)
- [On Simplicity (2019)](https://lobste.rs/s/qgbkwm/on_simplicity)
- [Programming Dictionary (Russian)](https://github.com/HowProgrammingWorks/Dictionary#readme)
- [Keep a changelog](https://keepachangelog.com/en/1.0.0/)
