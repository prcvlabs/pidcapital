---
layout: post
title: "Novel Tasks"
date: 2023-04-21 09:41:10 -0700
categories: thoughts
author: 'Everett Berry'
---

There's only one thing to know about the capabilities of GPT-4 and other large language modesl: they cannot produce new ideas. To quote the [Sparks of AGI paper](https://arxiv.org/abs/2303.12712) from Microsoft, "Perhaps the only real test of understanding is whether one can produce _new knowledge_, such as proving new mathematical theorems, a feat that currently remains out of reach for LLMs."

Deeply understanding this limit is the key to using LLMs like ChatGPT effectively. You should not expect it to perform novel tasks, like writing a thought provoking blog or coming up with a new algorithm. Instead focus on tasks which you know others have likely performed before in some way.

Thus far, we have found ChatGPT to be exceptionally effective at the following tasks:

* Writing SQL based on a description of the result and [even tables](https://www.promptingguide.ai/applications/coding#mysql-query-generation).
* Generating Google Sheets/Excel formulas based on describing the data in columns
* Rewriting a piece of code in a different programming language
* Refactoring code, for example:

```
Write a Go program which uses the modules-aware packages package to search a codebase for types which have 
functions with pointer receivers attached. Look for types where there are multiple variable names 
for the pointer receivers. Use godoctor-rename to rename the variables using whichever variable name 
is used in more functions associated with that type.
```

* Summarizing an existing concept (given that the concept existed before the model's cutoff date)
* Documenting a piece of code, for example "explain this code"

The unifying theme of these capabilities? There is nothing novel about completing them. That does not mean that the exact task has to be done before. But the ideas needed to complete these tasks are completely routine. Happily for us, most work is too.
