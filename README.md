# Software Engineering Concepts, Idioms, and Interesting Things


## Concepts & Interesting Things


### Minimum Viable Product (MVP)
> A product with just enough features to gather validated learning about the product and its continued development. As a development technique in which a new product or website is developed with sufficient features to satisfy early adopters. *The final, complete set of features is only designed and developed after considering feedback from the product's initial users.*

### Software Decay / Entropy / Rot
> The tendency for computer software to become gradually worse in performance or responsiveness over time, eventually leading to it becoming completely faulty, unresponsive, or unusable. This is either due to software failing to remain up to date and compatible with the operating system in which it operates, or because the software's code has been updated or altered in ways that have introduced more bugs and errors over time.

### Ninety-Ninety Rule
> The first 90 percent of the code accounts for the first 90 percent of the development time. The remaining 10 percent of the code accounts for the other 90 percent of the development time. In some agile software projects, this rule also surfaces when a task is portrayed as "relatively done". This indicates a common scenario where planned work is completed but cannot be signed off, pending a single final activity which may not occur for a substantial amount of time.

### Proof of Principle (Proof of Concept)
> A realization of a certain method or idea in order to demonstrate its feasibility, or a demonstration in principle with the aim of verifying that some concept or theory has practical potential. Typically derived from an experiment or pilot project, which demonstrates that a design concept, business proposal, etc., is feasible and is usually small and may or may not be complete

### Pareto Principle
> Can be applied in different ways, roughly 80% of consequences come from 20% of causes. In computer science the Pareto principle can be applied to optimization efforts. For example, Microsoft noted that by fixing the top 20% of the most-reported bugs, 80% of the related errors and crashes in a given system would be eliminated. Lowell Arthur expressed that "20% of the code has 80% of the errors. Find them, fix them!" It was also discovered that in general the 80% of a certain piece of software can be written in 20% of the total allocated time. Conversely, the hardest 20% of the code takes 80% of the time. This factor is usually a part of COCOMO estimating for software coding. WordPerfect and other software developers identify what customers want most of the time and how they want to do it: the 80/20 rule (people use 20% of a program's functions 80% of the time).

### Rule of Three
> A code refactoring rule of thumb to decide when similar pieces of code should be refactored to avoid duplication. It states that two instances of similar code do not require refactoring, but when similar code is used three times, it should be extracted into a new procedure. The rule was popularised by Martin Fowler in Refactoring and attributed to Don Roberts.

### In Layman’s terms
> To describe a complex or technical issue using words and terms that the average individual (someone without professional training in the subject area) can understand, so that they may comprehend the issue to some degree.

### Conway's Law
> Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure

### Brooks' Law
> The law, “Adding manpower to a late software project makes it later,” states that when a person is added to a project team, and the project is already late, the project time is longer, rather than shorter.

### Murphy’s Law
> Anything that can go wrong, will go wrong. 

### Gall's Law
> A complex system that works is invariably found to have evolved from a simple system that worked. The inverse proposition also appears to be true: A complex system designed from scratch never works and cannot be made to work. You have to start over, beginning with a working simple system

### Occam's Razor
> the problem-solving principle that "entities should not be multiplied beyond necessity", sometimes inaccurately paraphrased as "the simplest explanation is usually the best one."

### Technical debt
> Technical debt is the implied cost of reworking an existing codebase or system. It is often incurred as a result of taking a quick and easy option now instead of a creating a better solution which would take longer.

### Code smell
> A code smell is when any characteristic of a piece of code may be caused by a deeper problem within the system or architecture. A common code smell is a bloater, where a piece of code, which could be a component, class or method has increased to an undesirable size.


## Idioms


### Play it by ear
> Rather than sticking to a defined plan, see how things go and decide on a course of action as time goes on.

### Red herring
> Something that misleads or distracts from a relevant or important issue.

### Reinvent the wheel
> Waste a great deal of time or effort in creating something that already exists.

### Bikeshedding
> The Law of Triviality, describes our tendency to devote a disproportionate amount of our time to trivial topics. For example, a team might devote the majority of their time debating what colour a button on their website should be, rather than discussing what front-end framework best fits their needs and bring most value.

### Dogfooding
> Otherwise known as eating your own dog food is the practice of using your own products and projects. This is a good practice if you are able to do it as it means you are able to continuously validate that the product is functioning correctly. It can help to identify bugs, usability or feature gaps before being made available to your paying customers.

### Boil the ocean
> When someone tries to undertake a project or task which would be almost impossible to complete.

### Rubber ducking
> Rubber duck is an analog method of code debugging, where an engineer would articulate a problem using natural human language, either spoken or written. Using an inanimate object such as a rubber duck can help with this method by providing an imaginary listener of the problem. The very act of speaking about the problem can help the engineer to identify the cause of the problem.

### Drinking the Kool-Aid
> When someone “drinks the Kool-Aid”, it means that they have heavily bought into something, sometimes ignoring the arguments against the thing. The “thing” is often a company or its leader, but is sometimes used when referring to software languages, frameworks or methodologies.

### Skunkworks
> Skunkworks refers to a project that involves a specialist team working autonomously on an advanced or secret project, primarily for the sake of rapid innovation.

### Yak Shaving
> Yak shaving is when you start a task but end up having to complete a number of other tasks before you are able to complete the original task.

### Bus factor
> The bus factor of a project is the number equal to the number of team members who, if run over by a bus, would put the project in jeopardy. If a project overly relies on the contributions or knowledge of one person, then you could say that the project’s bus factor is one.

### Airplane Rule (KISS - Keep It Simple Stupid)
> “Complexity increases the possibility of failure; a twin-engine airplane has twice as many engine problems as a single-engine airplane.” By analogy, in both software and electronics, the rule that simplicity increases robustness. It is correspondingly argued that the right way to build reliable systems is to put all your eggs in one basket, after making sure that you've built a really good basket. 

### Angry Fruit Salad
> A bad visual-interface design that uses too many colors. (This term derives, of course, from the bizarre day-glo colors found in canned fruit salad.) Too often one sees similar effects from interface designers using color window systems such as X; there is a tendency to create displays that are flashy and attention-getting but uncomfortable for long-term use.

### Fenceposting Error
> A problem with the discrete equivalent of a boundary condition, often exhibited in programs by iterative loops. For example, suppose you have a long list or array of items, and want to process items m through n; how many items are there? The obvious answer is n - m, but that is off by one; the right answer is n - m + 1. A program that used the ‘obvious’ formula would have a fencepost error in it.

### Bazaar & Cathedral
> In 1997, after meditating on the success of Linux for three years, the Jargon File's own editor ESR wrote an analytical paper on hacker culture and development models titled **The Cathedral and the Bazaar**. The main argument of the paper was that Brooks's Law is not the whole story; given the right social machinery, debugging can be efficiently parallelized across large numbers of programmers. 

> The title metaphor caught on (see also cathedral), and the style of development typical in the Linux community is now often referred to as the bazaar mode. Its characteristics include releasing code early and often, and actively seeking the largest possible pool of peer reviewers. After 1998, the evident success of this way of doing things became one of the strongest arguments for open source. 

> The ‘classical’ mode of software engineering long thought to be necessarily implied by Brooks's Law. Features small teams, tight project control, and long release intervals. This term came into use after analysis of the Linux experience suggested there might be something wrong (or at least incomplete) in the classical assumptions.

### Kitchen Table Software
> Software made by someone, usually an amateur developer or entrepreneur, in their home.

### Bread Crumbs
> Debugging statements inserted into a program that emit output or log indicators of the program's state to a file so you can see where it dies or pin down the cause of surprising behavior. The term is probably a reference to the Hansel and Gretel story from the Brothers Grimm or the older French folktale of Thumbelina; in several variants of these, a character leaves a trail of bread crumbs so as not to get lost in the woods.

### Broken Arrow
> The error code displayed on line 25 of a 3270 terminal (or a PC emulating a 3270) for various kinds of protocol violations and “unexpected” error conditions (including connection to a down computer). On a PC, simulated with ‘->/_’, with the two center characters overstruck. **To appreciate this term fully, it helps to know that “broken arrow” is also military jargon for an accident involving nuclear weapons...**


## Reference & More Information
- [Software Idioms You Should Know](https://endaphelan.me/posts/software-idioms-you-should-know/) 
- [Dev.to Forum: What's your favorite software idiom/aphorism?](https://dev.to/ben/what-s-your-favorite-software-idiom-2cj9)
- [Part II. The Jargon Lexicon](http://www.catb.org/jargon/html/go01.html)
