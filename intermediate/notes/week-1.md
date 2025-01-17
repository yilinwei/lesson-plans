# Notes for Intermediate Week 1 Questions

1. This questions ensures they have basic concepts correct. They'll need these concepts to scafold the rest of the concepts we'll learn.

2. Operator notation is kinda dumb and kinda great, but always confusing at first. Let's clear it up early.

3. Practice writing some code.

4. The point here is to emphasise that types are compile-time constructs. Developers who have worked with "dynamically typed" languages will often have a notion of types that corresponds to what we call runtime tags. All these expressions have types though the last one does not evaluate to a value.

5. The questions correspond to three different ways of acquiring knowledge:

- Appeal to authority. Ask a trusted expert, such as a teacher
- Reason from first principles. Mathematics.
- Observe the world. Science.

All three are needed in programming.

6. Answering question could be done using any strategy. E.g. the students could reason from first-principles: types exist at compile-time, the literals have type `Int` and the operation has type `Int`, therefore the entire expression has type `Int`. Or they could observe the world: using the console they could type `:type 1/0`. Or they could ask someone else!

7. Checking basic concepts again.

8. `if` returns a value, so we can compose code more easily. This is a subtle point. Prepping their mind at this point.

9. Checking they understand scope.

10. Bringing up the concept of effects. Operations that return `Unit` has some observable effect on the world. `1 + 2` has no observable effect. We haven't formalised this yet. Just trying to plant the idea as preparation for the next section.

11. There are at least two ways to answer this:
 
- a program might ask for input from the user, and we can't know what that input will be ahead of time and thus we cannot check it as compile-time;
- fundamental limits (Turing's halting problem, Godel's incompleteness theorem) show that in general we cannot compute all possible properties of a program. However we can make progress on specific examples!

I wouldn't expect students to know about the latter. It might be interesting to them, though.

