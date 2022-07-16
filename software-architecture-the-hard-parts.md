# Software Architecture: The Hard Parts

## Summary

I like the fact that this book has stores, which are quite similar to the real
world, to accompany with and explain the theoretical concepts. It makes the book
less dry to read, unlike other books in the same category. The storytelling is
pretty similar to that of "The Phoenix Project".

One minor nuance I find while reading the book is that some sections are a little
wordy. For those who like to read every word when reading like me, that means a
little more are required to go through certain parts of the book.

## The Hard Parts

> Software architecture is the stuff that’s hard to change later.

The challenges that software architects often encounter are decision making when
solving problems. Why that is the hard part? Mostly because each real-world
problem is unique, it encompasses the organization and also the specific context
in which the problem is being solved.

Essentially, there is "no silver bullet".

Anyone, even software engineers, who has ever designed a software system would
have had to navigate between many approaches and options, analyze their trade-offs,
and eventually make a final decision on how to solve the problem.

## Architecture vs Design

The easiest analogy is the architecture and the design of a house.

_Architecture_ is the stuff that usually must be thought through carefully upfront
and they are **hard to change**.

_Design_ is easier to modify if we change our mind afterwards.

However, I often find these terms used interchangeably in the real world. People
often means the same thing when they say "designing a system" or "architecting
a system". There might be, and I should probably find one, examples to better
represent the differences.

> Keeping architecture and design as separate but related activities.

### Focus on Architecture

Two important things an architect must understand:

- The underlying architecture principles to make effective decisions
- _Why_ is more important than _how_

### Examples

When building a new software, we usually need to pick an architecture to follow,
whether it is multi-tier or microservices architecture. That decision forms the
core structure of the system. Afterwards, there are many ways to design the system
to follow that architecture. For example, there are multiple variants of a
microservices architecture.

Another aspect is synchronous vs asynchronous communication. The decision to pick
one over another is an architectural decision. How it is implemented afterwards
is a design decision, for example, choosing RPC or REST style for services to
talk synchronously to each other.
