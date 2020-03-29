# Tutorials

* [Amit](https://simblob.blogspot.com/) has a [great explanation of A* algorithm with visualizations](https://www.redblobgames.com/pathfinding/a-star/introduction.html)
* [A great primer](https://github.com/donnemartin/system-design-primer) on design of reliable, scalable systems.
* [Build your own X](https://github.com/danistefanovic/build-your-own-x) for many values of X.
* [Aphyr](https://github.com/aphyr) (of [Jepsen](https://jepsen.io/) fame) teaches a class on distributed systems with [notes online](https://github.com/aphyr/distsys-class)
* [Jimmy Bogard](https://jimmybogard.com/) has some good series:
  * [implementing resilient workflows](https://jimmybogard.com/refactoring-towards-resilience-a-primer/) when coordinating multiple services.
  * [resiliency built around loose coupling](https://jimmybogard.com/life-beyond-transactions-implementation-primer/).
* A great [TypeScript project starter](https://github.com/bitjson/typescript-starter)
* Seth Robertson has a fantastic, [choose-your-own-adventure tutorial](http://sethrobertson.github.io/GitFixUm/fixup.html) on modifying your Git history.
* [AsyncGuidance](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md) has a bunch of gotchas and error scenarios juxtaposed against best practices for async programming.
* [Software Design and Architecture in Haskell](https://github.com/graninas/software-design-in-haskell) is a curated collection of links to resources about building real software in Haskell.

# Papers and Articles
* [You're Doing It Wrong](https://queue.acm.org/detail.cfm?id=1814327) describes how optimizing algorithms to be virtual-memory-aware can result in 10x speed improvement over algorithms that are theoretically-algorithmically-more-efficient
* [SageDB: A Learned Database System](http://cidrdb.org/cidr2019/papers/p117-kraska-cidr19.pdf) describes a database that learns about its data to improve performance.
* [Martin Fowler's](https://martinfowler.com/) [Accounting Patterns book](https://martinfowler.com/apsupp/accounting.pdf) describes an event-oriented architecture for dealing with common patterns encountered when implementing accounting systems (where "accounting" is defined pretty broadly).
* [Modern B-Tree Techniques](https://www.nowpublishers.com/article/DownloadSummary/DBS-028) describes modern features, capabilities, and techniques for implementing or augmenting B-Trees
* [The Design and Implementation of Modern Column-Oriented Databases](http://db.csail.mit.edu/pubs/abadi-column-stores.pdf) looks at how column-oriented databases are built under the hood.
* [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf) is an in-depth look at how memory works and implications for software design.
* [Sorting in the Presence of Branch Prediction and Caches](https://www.scss.tcd.ie/publications/tech-reports/reports.05/TCD-CS-2005-57.pdf) explores the implications of modern CPU architectures for common sorting algorithms.
* One of Ayende's employees wrote a great [low-level writeup](https://ayende.com/blog/175009/digging-into-the-coreclr-exceptional-costs-part-i) about the performance impact of exceptions in tight loops.
* Adrian Colyer's consensus paper write-ups are great for understanding distributed consensus:
  * ["Distributed consensus revised" paper](https://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-935.pdf)
    * [Part 1](https://blog.acolyer.org/2019/05/07/distributed-consensus-revised-part-i/)
    * [Part 2](https://blog.acolyer.org/2019/05/08/distributed-consensus-revised-part-ii/)
    * [Part 3](https://blog.acolyer.org/2019/05/10/distributed-consensus-revised-part-iii/)
  * [Can't we all just agree?](https://blog.acolyer.org/2015/03/01/cant-we-all-just-agree/) ten-part series
* [Brendan Gregg](http://www.brendangregg.com/) has a great [list of article links](http://www.brendangregg.com/linuxperf.html) about understanding system and application performance on Linux. (He's the author of many of the articles linked and tools discussed.)
  
# Lists
* [Hacker Laws](https://github.com/dwmkerr/hacker-laws): "laws" about computing.

# Collections

* [Awesome Falsehoods](https://github.com/kdeldycke/awesome-falsehood) is a curated collection of lists of falsehoods that programmers believe. It's very informative.
* [Awesome CRDT](https://github.com/alangibson/awesome-crdt) is a curated collection of articles, papers, blog posts, tutorials, and libraries about CRDTs.
* [Data-Oriented Design Resources](https://github.com/dbartolini/data-oriented-design) is a collection of links and reading about how to design your code -- and change your thinking -- around data and its performance implications as a first-class concern.
* [Awesome Workflow Engines](https://github.com/meirwah/awesome-workflow-engines) is a curated list of open-source workflow engines.
* [Awesome](https://github.com/sindresorhus/awesome) is a collection of "awesome lists" similar to the ones above.
* [Awesome Lists](https://github.com/topics/awesome-list) is a github topic containing links to "awesome lists". Kinda like the item immediately above, but curated by the community instead of a single user.
* [Java Design Patterns](https://github.com/iluwatar/java-design-patterns) is a list of design patterns with implementations in Java.

# Free Stuff

* The [Textures Archive](http://www.grsites.com/archive/textures/) has a bunch of free background textures for building games, websites, apps, or just playing around.
* [Itch.io](https://itch.io/game-assets/free) has as large repository of free and low-cost graphics assets for games (mostly tile- and sprite-focused).
* [Scott Hanelman's](https://www.hanselman.com/) [tools list](https://hanselman.com/tools)
* [The Billion Taxi Ride Dataset](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) contains ride information for over a billion taxi and other for-hire-vehicle rides, and is open data.

# Blogs

* [Ayende's blog](https://ayende.com/blog/) is a gold mine of information about developing professional software in C#, performance optimization, and concurrency.
* [Rands in Repose](http://randsinrepose.com/) for management tips in a software engineering context.
* [Fabulous Adventures in Coding](https://ericlippert.com/) is the blog of Eric Lippert, formerly of the C# compiler team. It's chock-full of static analysis goodness.
* [Jepsen](https://jepsen.io/) tracks behavior of databases against CAP theorem guarantees. Seeing detailed analysis of how systems break under pressure is super-informative about how hard distributed databases are.
