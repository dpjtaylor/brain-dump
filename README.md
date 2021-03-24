# Brain Dump

_A place to gather thoughts or useful links_

### Content
- [Agile](#agile)
- [Remote Working](#remote-working)
- [Software Engineering](#software-engineering)
- [Testing](#testing)

## Agile

*Agile practices*

- [Agile in 7 minutes, 26 seconds](https://youtu.be/WSes_PexXcA) - Rapid talk on the Fundamental Theorem of Agile Software Development by J.B. Rainsberger
- [Surviving your Agile Transition](https://youtu.be/UQOmGiv7rUk) - J.B. Rainsberger on Agile Transformation. Agile should be lightweight, but is interpreted in many ways

## Remote Working

- [Shape up](https://basecamp.com/shapeup) - Basecamp describe their way of working (methodology)
- [Remote](https://basecamp.com/books/remote) - Basecamp describe what they've learnt about operating as a fully remote company

## Software Engineering

*General software engineering resources*

### Getting started

- [How to be a Programmer](https://www.doc.ic.ac.uk/~susan/475/HowToBeAProgrammer.pdf) - great general advice

### Advanced
- [Point Free - Functional Programming](https://www.pointfree.co/) - functional programming and app architecture

### At Scale
- [The Mythical Man Month](https://en.wikipedia.org/wiki/The_Mythical_Man-Month) - anyone in a software engineering leadership position should have read this
- [The Influence of Organizational Structure on Software Quality](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-2008-11.pdf) - Impact of Org structure on quality
- [The Taxonomy of Tech Debt](https://technology.riotgames.com/news/taxonomy-tech-debt) - classifying tech debt based on impact, cost to fix and how contagious it is

### Code Reviews
- [Make Your Code Reviewer Fall in Love with You
](https://mtlynch.io/code-review-love/) - how you as the author of the change can make life easier for reviewers

### Wisdom
> Junior programmer's bookshelf: 90% APIs and programming languages; Senior programmer's bookshelf: 80% applied psychology. - [J.B. Rainsberger](https://twitter.com/jbrains/status/616228270841962496?s=20)

> The only proper justification for refactoring is to reduce the volatility in the marginal cost of a feature (i.e. reduce the cost of future features by actively addressing accidental complexity) - [J.B. Rainsberger (paraphrased)](https://www.youtube.com/watch?v=UQOmGiv7rUk)

> I conclude that there are two ways of constructing a software design: One way is to make it so simple that there are obviously no deficiencies and the other way is to make it so complicated that there are no obvious deficiencies. The first method is far more difficult. - Simplicity is Hard -[Out of the Tar Pit (quoted from Hoare 1980 Turing Speech](https://blog.royalsloth.eu/articles/outOfTheTarPit.pdf)

> Any organization that designs a system (defined more broadly here than just information systems) will inevitably produce a design whose structure is a copy of the organization's communication structure - Conway's Law

## Testing
- [Integrated Tests are a Scam](https://vimeo.com/80533536) - J.B. Rainsberger on Integration tests. TL;DR: Integration tests are slow, brittle, difficult in terms of identifying the point of failure, combinatory in nature (explosion of tests to cover all combinations); isolated tests are fast, resilient, easy to understand and linear in nature (typically one per clasas)
