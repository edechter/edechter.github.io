---
layout: post
title: What are the standards of science journalism?
category: Science
comments: true

excerpt: A sample draft post.

globelink: http://www.bostonglobe.com/ideas/2015/08/10/computer-scientists-have-looked-for-solution-that-doesn-exist/tXO0qNRnbKrClfUPmavifK/story.html

archiv_link: http://arxiv.org/abs/1412.0348

---



The Boston globe [reported today]({{page.globelink}}) on a paper from [Arturs Backurs and Piotr Indyk]({{page.archiv_link}}) that shows that any algorithm that computes the edit distance between two strings in sub-quadratic time implies the existence of a sub-exponential time algorithm for SAT on N variables. Since this would in turn imply that P=NP, the result suggests that such an algorithm does not exist.

Here's how the Globe describes the finding:

> For 40 years, computer scientists have tried in vain to find a
> faster way to do an important calculation known as “edit distance.”
> Thanks to groundbreaking work from two researchers at MIT, they now
> know the reason they’ve continually failed is because a faster
> method is actually impossible to create.

And here's how Backurs and Indyk describe their result in the paper's abstract:

> In this paper we provide **evidence** that the near-quadratic running
> time bounds known for the problem of computing edit distance **might**
> be tight. (emphasis mine)

I understand that the subtlety of arguments based on whether P equals NP might be lost on most of the Globe's readers. On the one hand, the force of the result is contingent on the conjecture that P does not equal NP. On the other hand, it's not a **mere** conjecture; computer scientists will certainly act as if a subquadratic algorithm is impossible to create.

But don't journalist have a responsibility to report on scientific results accurately? Couldn't Harnet (the Globe reporter) have written "almost certainly impossible to create" instead of "actually impossible to create"? We wouldn't tolerate this kind of reporting on, say, whether the wreckage in the Indian ocean belongs to the missing Malaysian Airlines flight; if the authorities say that they strongly suspect it belongs to the missing airplane, that doesn't license reporters to say that authorities are sure it does.


{% include comments.html %}
