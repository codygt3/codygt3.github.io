---
layout: essay
type: essay
title: "My Introduction To Typescript"
# All dates must be YYYY-MM-DD format!
date: 2024-09-05
published: true
labels:
  - Writing
---

Hello everyone! Recently I've began learning how to program in Typescript, as it is the language I will be using for my ICS 314 class. From what I gathered from the couple videos I've watched on it, Typescript is a language that, at its core, is Javascript with many tweaks that make it more similar to other programming languages such as Java and C. This language seems really interesting, and I've seen some really cool things that it's capable of doing that I eventually want to grasp and become comfortable using.

### What Makes Typescript Different

Typescript reminds me of many other programming languages I've used in the past. First of all, the way functions are defined and used remind me of C, because functions are intuitive to create and make usage of and don't require dealing with objects to use them like with Java. I can also specify a return type like in C, although how it differs is that you can specify the return type to be multiple different types like this:

    function numOrString(input: number): number | string {

This really intrigues me. I'm also capable of rewriting if-else statements directly into the return statement like this:

    function grader(score: number): string {
    return score >= 90 ? 'A' :
           score >= 80 ? 'B' :
           score >= 70 ? 'C' :
           score >= 60 ? 'D' :
           'F'; }
I find this really cool, as it looks much cleaner than a long if-else chain. I'm excited to learn the other quirks of typescript that can make my code look cleaner and more efficient. 

### Using Typescript In Class

Something interesting to note is that the class I'm using Typescript in, ICS 314, has assignments calls WODs (Workouts of the Day) where I have to do a coding challenge under a limited amount of time. This forces me to manage my time and apply what I've learned without the ability to take my time and google all the answers at a leisurely pace. Having practice working under time constraints and pressure is something I feel is a strength of mine, especially due to my outside interests which involve competition and pressure. I feel I work best when under pressure, and being able to learn how to apply Typescript while under this pressure is a lot of fun. 

Overall, I think Typescript is a really cool language, and having the opportunity to practice using it under pressure is exciting to me. I'm excited for my future ICS 314 classes as I will only get better at using the language over time!

