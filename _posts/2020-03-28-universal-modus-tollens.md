---
layout: article
mathjax: true
title: Universal Modus Tollens
image: "/assets/images/img_test.jpg"
categories:
- DM
desc: '' 
imagealt: Photo by <a href="https://unsplash.com/@mangofantasy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Johnson</a> on <a href="https://unsplash.com/s/photos/logic?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
---

It is a combination of [Modus Tollens]({% post_url 2020-03-11-modus-tollens %}) and [Universal Instantiation]({% post_url 2020-03-23-universal-instantiation %}).
If $\forall x(P(x) \to Q(x))$ is true
and if $Q(a)$ is false for a particular element $a$ in domain.
Then $P(a)$ must also be false for that same element.

$\forall x(P(x) \to Q(x))$
$\neg Q(a)\ for\ a\ particular\ element\ in\ domain$
$\therefore \neg P(a)$