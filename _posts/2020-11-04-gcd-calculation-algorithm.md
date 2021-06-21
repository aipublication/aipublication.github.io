---
layout: article
mathjax: true
title: GCD Calculation Algorithm
image: "/assets/images/img_test.jpg"
categories:
- DM
desc: '' 
imagealt: Photo by <a href="https://unsplash.com/@mangofantasy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Johnson</a> on <a href="https://unsplash.com/s/photos/logic?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
---

Calculation of [Greatest Common Divisor (GCD)]({% post_url 2020-08-17-greatest-common-divisor-(gcd) %}) of two integers $a$ and $b$ could be reduced to $\gcd(b\ mod\ a, a)$.
This is a recursive implementation of [Euclidean Algorithm]({% post_url 2020-11-07-euclidean-algorithm %}).

```
gcd(a, b):
	if(a>0 and b>0 and a<b):
		if (a==0):
			return b
		else:
			return gcd(b mod a, a)
```

Tags: #algorithm 