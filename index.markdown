---
title: DevOps Principles
layout: home
---

List of DevOps Principles as they are described in the book "The Phoenix Project".
They are written down here as a reminder for myself.
If you are interested, you should read the book to have a better understanding of them.

## DevOps Principles

The principles are three. 
Each of them subdivided into practical hints.

***
### Principle of Flow

1. Make you work visible

A very visual example is to organize the work in a Kanban board. 

2. Limit Work in Progress (WIP)

Limit work in progress to few tasks, ideally three. 
In this way bad multitasking is limited and it is easier to reason about the flow of work.
If we find out that limiting the WIP we have nothing to do, then it means we are depending on someone else.
Instead of catching new work, we should detect what is cause the delay.

3. Reduce batch size

It was common to produce in large batch size but the result is long lead time and poor quality because when a problem is found, the entire batch is affected by it.
Instead, we should focus on smaller batch size.
This approach results in less WIP and faster lead time and detection of errors.

4. Reduce number of handoff

Each time some work passes from team to team there is a lot of coordination involved.
Each step is a potential queue where work will wait.

5. Continually identify and elevate constrain

In *Beyond the Goal* Dr. Goldratt stats: 
> In any value stream, there is always a direction of flow, and there is always one and only one constraint; any improvement not made at that constraint is an illusion

6. Eliminate hardships and waste in the value stream

There are several categories of waste and hardship (from *Implementing Lean Software Development*)
   * Partially done work
   * Extra processes
   * Extra features
   * Task switching
   * Waiting
   * Motion
   * Defects
   * Nonstandard or manual work
   * Heroics

***
### Principle of Feedback

- Working safely within complex systems
- See problems as they occur
- Swarm and solve problems to build new knowledge
- Keep pushing quality closer to the source
- Enable optimizing for downstream work centers

***
### Principle of Continual Learning and Experimentation

- Enabling organizational learning and a safety culture
- Institutionalize the improvement of daily work
- Transform local discoveries into global improvements
- Inject resilience patterns into our daily work
- Leaders reinforce a learning culture

