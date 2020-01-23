---
layout: single
title:  "A step by step guide on solving problems"
categories: problem_solving algorithms interviews
---

Being a data scientist and an educator, I'm solving problems all day every day and regularly help others to do that.

In this guide I'll outline a structure to help you solve problems as well.

Although it's mostly focused on the professional situations, such as interviews or building projects while working on a team, it can be also useful in a personal life and day-to-day activities.

Either way, this framework will help you to get unstuck.

Let's get started!

## Step 0: Understand the problem

I can't emphasize enough how important it is. If you want to remember only one thing from this guide, it's this: **don't start solving any problem until you understand it**.

Solutions for the wrong problem do not count. You may end up doing something irrelevant or overly complex. It will not play well with your interviewer, boss, partner, you name it, since the solution may not address the initial problem.

Yes, they may be surprised, but you can surprise with your solution and overdeliver when everyone is aligned on the problem at hand.

And the best time to identify the misunderstanding is right now!

How to make sure that you understand the problem?
* reformulate the problem and convey it back to the interviewer/manager and ask for the confirmation
* come up with some examples
* ask clarifying questions
* re-read the assignment if taking a test / there is nobody around

Rinse and repeat until the problem is clear and everyone is aligned.

![shared_understanding](/assets/images/2020-01-19-img/understand_the_problem.jpg)

## Step 1: Is this the right problem for me to solve?

Although it's more applicable in the context of work, rather than in the interviews, asking this question can save some time.

Some variations of this problem:
* do we need to worry about these parts of the problem?
* prioritize: often a problem has many aspects, so understanding where to focus is important
* prioritization can be essential in determining the right solution as well
* maybe it's a problem worth solving, but it's better suited for someone else. Then, delegate / advocate, if appropriate
* do we need to solve it now? / is the timing right?
* how it's aligned with the bigger objectives?

## Step 2: Start with an example.

Obviously, if you have already came up with a solution, feel free to skip this for now.

Even if you are an engineer who can easily work with abstractions, our brains are hard-wired to work with concrete things. So, if you are not sure what the solution will look like, start with a concrete and simple example.

Solve an example by hand. Reflect on the process - that can help you to come up with a solution.

How would you instruct a child to solve this problem? An algorithm, after all, is just a set of instructions. So, starting with those high level explanations will get you closer to the solution.

Hint: you can use those examples later to write some tests.

![constraints](/assets/images/2020-01-19-img/paper_prototype.jpg)

## Step 3: Understand context and assumptions

By this point you should have at least some understanding of the problem. Almost any problem has assumptions. Occasionally, some are explicit, but almost always there are some implicit ones.

List them here for others and for future self. It can help you to simplify the problem, or find a good place to start. It will also help to eliminate all the things that you should not worry about.

Hint: once you found any constraints - write them down for your future self.

If working on the project, acceptance criteria is also something that you want to identify at this step.

A word of caution: do not stress too much about identifying the constraints perfectly - things change and projects evolve.

![constraints](/assets/images/2020-01-19-img/constraints.jpg)

## Step 4: Start simple

Start small. Generalize later.

Most of good products and solutions come form iterations. You start simple and improve upon it as you go.

Be it a brute-force solution, a paper prototype, or a baseline model - start simple and improve upon it. This will help you to get started, demonstrate that you can get things done, and get some feedback.

And feel free to ignore some of the constraints identified earlier for this step.

![start_simle](/assets/images/2020-01-19-img/start_simple.jpg)

## Step 5: Use top-down approach

Start with the big picture and dive deeper when needed. Outline the solution on a high level. Have placeholders for details. You may or may not have to implement them later. You also may be able to delegate some of those tasks to your teammates.

Top-down approach helps to break the problem into manageable pieces and set boundaries and interfaces. It can also help to differentiate between the easy parts of the problem and the tricky ones, so you know where to focus.

![constraints](/assets/images/2020-01-19-img/top_down.jpg)

## Step 6: Do your research

Chances are, you have already solved some of those subproblems, or, at least, something similar. There may exist some out-of-the-box solutions as well. All that stuff may or may not be useful, but you should be aware of it.

So, if you decide to reinvent the wheel, it will be a conscious decision with clear reasoning. And, the reinvented wheel will be a much better fit for the problem, and you will leverage the existing knowledge in the process.

If the problem is a novel one, and it took you far outside of the comfort zone - try to reduce the problem to a familiar one. Being able to identify similar problems and to reduce the problem to one that's already solved is a very useful skill. Even if that problem is not the perfect fit, it will give you some idea on where to get started.

## Step 7: Select your approach

If you came up with a few approaches that can solve the problem given the constraints, how to choose the right one?

Here are a few things to consider:
* ease of development
* ease of debugging
* explainability
* solution is a right fit for the problem

![constraints](/assets/images/2020-01-19-img/use_the_right_tool.jpg)

## Step 8: Test your solution

How do you know that the solution is a correct one?

* Walk through how it works.
* Make some tests.
* Test it with a friendly audience

No matter what your situation is, test the solution before releasing/submitting it.

![walk_through](/assets/images/2020-01-19-img/walk_through.jpg)

## Conclusion

Finally, it's an iterative process so feel free to revisit any of the previous steps.

And remember: when in doubt - ask questions! Solving problems is much more fun when done together, and asking good questions is a good way to get others' perspectives.

Good luck with problem solving!
