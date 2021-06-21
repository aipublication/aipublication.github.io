---
layout: article
mathjax: true
title: Correctness of Conditional Statement
image: "/assets/images/img_test.jpg"
categories:
- DM
desc: '' 
imagealt: Photo by <a href="https://unsplash.com/@mangofantasy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Johnson</a> on <a href="https://unsplash.com/s/photos/logic?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
---

To prove that a [Conditional Statement]({% post_url 2020-01-15-conditional-statement %}) is true we have to prove:
* if [Initial Assertion]({% post_url 2020-09-20-initial-assertion %}) is true and *condition* is true then [Final Assertion]({% post_url 2020-09-21-final-assertion %}) is true when program terminates.
* if [Initial Assertion]({% post_url 2020-09-20-initial-assertion %}) is true and *condition* is false then [Final Assertion]({% post_url 2020-09-21-final-assertion %}) is true when program terminates because [Final Assertion]({% post_url 2020-09-21-final-assertion %}) checks validity of all outputs.

$$
\begin{align}
	(p \wedge\ condition) \{S\}q \\
	(p \wedge\ \neg condition) \to q \\
	\hline \\
	\therefore p\{if\ condition\ then\ S\}q
\end{align}
$$