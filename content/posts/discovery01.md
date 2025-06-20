+++
date = '2025-05-28T15:57:55+01:00'
draft = true
title = 'Discovery01'
+++
+++
date = '2025-05-28T15:57:55+01:00'
draft = false 
title = 'You use them but do you know what an operation is in group theory?'
+++
# Understanding Operations in Group Theory

What's dark chocolate?

Dark chocolate is a form of chocolate made from...

Can you understand what dark chocolate is if you don't know anything about chocolate? That's the same thing for operations in group theory.

A group is a set equipped with a binary operation that satisfies four axioms. Like the definition of dark chocolate, the notion of operation is coupled with the definition of a group. Learn about operations and sharpen your knowledge of groups for free!

An operation must satisfy three essential properties: being well-defined, closure, and totality (being defined for all elements). We could simply memorize those properties as a gift from those brilliant mathematicians fortunate enough to define mathematics, but that won't build our understanding. Why does each property exist, and what happens when we remove them? Those questions are better candidates for the purpose of comprehension.

## An operation must be well-defined 

For an operation to be useful, it must be well-defined. If an operation is a machine that takes an input and produces an output, we consider an operation unique only if the output of our machine is unique for any given input.

Consider the simple equation:

$$x+2=3$$

To solve for \\(x\\), we apply the subtraction operation to both sides, isolating \\(x\\) on the left side:

$$x=3-2$$

We can confidently conclude that \\(x=1\\) because the operation \\(3-2\\) gives a unique and constant answer.

Now, imagine if the result of \\(3-2\\) was not unique. What if it could sometimes equal \\(100\\) or perhaps \\(4234\\)?  When would it be \\(100\\)? When would it be 1? The very idea of equality assumes uniqueness. Without it, mathematics would become chaotic. We couldn't write equations or prove theorems, as the results of our calculations would be constantly changing.

## An operation must be closed 

Closure ensures that when we perform an operation on elements within our set, the result remains within the same set.

Consider an analog clock. Our operation will be addition of hours on a clock. We know that the clock can't go higher than 12 hours. The time wraps around at 12. No matter what you add.

If you start at 8, add 2 hours, you end up at 10. If you add 10 more hours, you reach 8 (since \\(10 + 10 = 20\\), and \\(20 \bmod 12 = 8\\)). No matter which numbers you chain like this using this addition, you will always stay within the set \\(\\{1, 2, 3, ..., 12\\}\\), which demonstrates closure visually.

Were addition not closed, what would \\(8 + 10 + 9\\) equal? Instead of getting 3 (since \\((8+10+9) \bmod 12 = 27 \bmod 12 = 3\\)), we might get some value outside our clock's range, like 27. In the context of the clock, does 27 hours have any meaning? When the operation is not closed, you lose consistency. You aren't guaranteed to chain operations like I did \\((8 + 9 + 10)\\) and get a meaningful result within your system.

## An operation must be total (defined everywhere)

Finally, an operation must be defined for all pairs of elements in the set - this property is called **totality**. If we have a set \\(S\\) and an operation \\(\oplus\\), then for any two elements \\(a\\) and \\(b\\) in \\(S\\), the operation \\(a \oplus b\\) must be defined and produce a result.

Consider the division operation on real numbers. Division is not total because dividing by zero is undefined. If we tried to use division as our operation on the set of all real numbers, we would have gaps - certain combinations of elements (like \\(5 \div 0\\)) would have no result.

This creates the same consistency problems we saw with closure. If we allow undefined operations within our set, it weakens our ability to describe that set consistently, which means having to deal with exceptions to statements. We can no longer say "any two elements can be combined using our operation" - we'd have to add caveats and exceptions.

Totality ensures that our operation is a true function that works for every possible input from our set, making our mathematical system complete and predictable.
