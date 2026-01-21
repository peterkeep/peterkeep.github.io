---
layout: post
title: Two Fun Infinite Series
subtitle: 
cover-img: 
thumbnail-img: /assets/img/posts/series.png
share-img: /assets/img/posts/series.png
tags: [math, teaching]
author: Peter Keep
mathjax: yes
---

I love teaching Calculus II. It hits the perfect sweet-spot of "has really cool mathematics" and "always available to teach," since we run multiple sections of it every semester and, apparently, nobody else in my department really likes teaching it that much. Weird. Anyways, it's my favorite class to teach.

I have made a decent number of changes to the course over the past 10 years, really trying to build up the themes of the course (Approximation! Accumulation!) and make them explicit to students. But sometimes that means that some other little aspect of the course gets cut or diminished. This post is about some of my favorite little problems to pitch to students that I don't get near enough time to chat about with my students. 

# Some Infinite Series

Ok, let's look at some of my favorite little series problems. I don't think I came up with any of these, and I'm sure they were borrowed from other people or derived from other people's examples. 

First, though, some preliminaries.

<div class="box-warning">
    <b>The Harmonic Series:</b> The series of reciprocals is called the Harmonic series:
    $$
        \sum_{k=1}^\infty \frac{1}{k} = 1 + \frac{1}{2}+\frac{1}{3}+\frac{1}{4} + ...
    $$
</div>

An introductory calculus student will find pretty quickly that this infinite sum **diverges**---when we add these terms iteratively (\\(1\\), \\(1+\frac{1}{2}\\), \\(1+\frac{1}{2}+\frac{1}{3}\\), \\(1+\frac{1}{2}+\frac{1}{3}+\frac{1}{4}\\), ...) the cumulative sums (or **partial sums**) do not seem to be converging on any single, real number. In an introductory calculus class, we can prove this[^harmonic].

And from there, we can look at what happens when we fiddle with the exponent on the denominators...maybe instead of the sum of reciprocals, we look at the sum of the reciprocal squares? Or reciprocal cubes! Or reciprocal square roots! And then we quickly arrive at a nice result, connecting this family of infinite sums together.

<div class="box-warning">
    <b>\(p\)-Series:</b> For the real number \(p\), the series
    $$
        \sum_{k=1}^\infty \frac{1}{k^p}
    $$
    converges when \(p\gt1\) and diverges when \(p\leq 1\).
</div>

There is a lot to say about this family of series, but from here forward, we're going to present and talk about some related infinite series. In order to talk about them, we'll assume that we know about series convergence tests like the Integral Test[^integral] and the Comparison Tests[^comparison].

## Counting Digits

Let's consider the following infinite series:

$$
    \sum_{k=1}^\infty \frac{1}{k^pD(k)}
$$

where \\(D(k)\\) is the function that counts the number of digits in \\(k\\). So \\(D(7)=1\\) and \\(D(146)=3\\).

For what values of \\(p\\) does this series converge?

Ok, so this is such a fun problem to pitch to students because:

1. Students are typically not used to working with functions like \\(D\\), where it is easy to describe in words but not formulated mathematically, yet.
2. It is a problem that a student in Calculus II could work through, completely independently.
3. Students in my class work in groups, and so they go into this knowing that they won't be expected to complete it independently.

Try this one yourself, and see how much fun it is!

<details>
    <summary>Hints!</summary>
    <div style="padding: 10px;">
        <p>
            There are a couple of questions you'll want to answer.
            <ol>
                <li>
                    Can you use logs to describe the \(D(k)\) function? It's an interesting function because it's kind of a step function.
                </li>
                <li>
                    Can you start with some basic values of \(p\), and think about comparisons? Note that \(D(k)\geq 1\) for \(k=1,2,3,4,...\)
                </li>
                <li>
                    This is <em>almost</em> something that you could use the Integral Test on...too bad we don't meet the continuity requirement for the integral. Unless...?
                </li>
            </ol>
        </p>
    </div>
</details>

<details>
    <summary>Even More Specific Hints!</summary>
    <div style="padding: 10px;">
        <p>
            Here are some more details about the hints above.
            <ol>
                <li>
                    We know that \(D(k)=\left\lfloor\log(k)+1\right\rfloor\). So our series is really:
                    $$
                        \sum_{k=1}^\infty \frac{1}{\left\lfloor\log(k)+1\right\rfloor(k^p)}.
                    $$
                </li>
                <li>
                    We can use the fact that 
                    $$
                        \log(k) \leq \left\lfloor\log(k)+1\right\rfloor \leq \log(k)+1
                    $$
                    and show then that
                    $$
                        \frac{1}{\log(k)(k^p)}\geq \frac{1}{D(k)k^p} \geq \frac{1}{\left(\log(k)+1\right)k^p}
                    $$
                    Something to note is that this inequality only really works when \(k\gt 1\), so we'll consider the infinite series starting at \(k=2\) instead. Adding back the term when \(k=1\) in our original series will not change the behavior, and so we can start our series at \(k=2\) to classify whether it converges or diverges.
                </li>
                <li>
                    While \(\dfrac{1}{\left\lfloor\log(x)+1\right\rfloor}\) is not continuous on \([2,\infty)\), the functions \(\dfrac{1}{\log(x)(x^p)}\) and \(\dfrac{1}{(\log(x)_+1)(k^p)}\) are. It turns out that the integrals
                    $$
                        \int_{x=2}^\infty \frac{1}{\log(x)x^p}\;dx \;\;\; \text{and} \;\;\; \int_{x=2}^\infty \frac{1}{(\log(x)+1)(x^p)}\;dx
                    $$
                    are fun to evaluate.
                </li>
            </ol>
        </p>
    </div>
</details>

## Primes

Now let's consider a second, but similar, infinite series:

$$
    \sum_{k=1}^\infty \frac{1}{P_k(k^p)}
$$

where \\(P_k\\) is the \\(k\\)th prime number. So \\(P_1=2\\) and \\(P_{16}=53\\).

Again, we can ask: for what values of \\(p\\) does this series converge?

This one is fun to give to students because:

1. The \\(P_k\\) function is another one that they know a bit about, but not much. And it's been historically harder to write out mathematically than the \\(D(k)\\) function above.
2. It requires students to do a bit of looking around in a topic that isn't often connected with calculus. They get to learn about prime numbers, and some great history around an important theorem[^prime].
3. Students in my class are used to having a laptop or tablet or something similar at their tables in their groups, and they know that they can use them. This is a great opportunity to give students some small prompts and set them loose!

I am pretty sure this is a common series to look at in an introductory analysis course, but it's really fun as well! Give it a try!

<details>
    <summary>Hints!</summary>
    <div style="padding: 10px;">
        <p>
            Here are some general thoughts or hints that I might give students.
            <ol>
                <li>
                    Can you start by comparing the size of \(P_k\) with \(k\)? Which one is bigger? Does this ordering remain for all values of \(k\)?
                 </li>
                 <li>
                    It would be helpful to have a written-out function rule for \(P_k\), but unfortunately we don't have one. Take a look at the Prime Number Theorem in the references at the end of the page. This could be helpful!
                 </li>
            </ol>
        </p>
    </div>
</details>

<details>
    <summary>Even More Specific Hints!</summary>
    <div style="padding: 10px;">
        <p>
            Here are some more details about those hints above!
            <ol>
                <li>
                    Once we convince ourselves that \(P_k\gt k\) for all \(k=1,2,3,...\), then we can get 
                    $$
                        \frac{1}{P_k(k^p)} \lt \frac{1}{k^{p+1}}.
                    $$
                    This inequality is a great one to use to show some values of \(p\) that will make the \(\displaystyle\sum_{k=1}^\infty \frac{1}{P_k(k^p)} \) converge.
                 </li>
                 <li>
                    There's a lot of fun reading about the Prime Number Theorem, but one of the statements of it gives us a way of approximating prime numbers:
                    $$
                        P_k \approx k\log(k).
                    $$
                    We also know that as \(k\to\infty\), \(P_k \to k\log(k)\). This is perfect for the purposes of a Limit Comparison Test! We can use it to compare the two series (again, starting at \(k=2\) to avoid division badness with the logarithm):
                    $$
                        \sum_{k=2}^\infty \frac{1}{P_k(k^p)} \;\;\; \text{compared to}\;\;\;\sum_{k=2}^\infty \frac{1}{k^{p+1}\log(k)}.
                    $$
                    Hopefully we can pair this with something like the Integral Test to tell us about the behavior of 
                    $$
                        \displaystyle\sum_{k=2}^\infty \frac{1}{k^{p+1}\log(k)}
                    $$
                    for different values of \(p\) by thinking about the behavior of the integral
                    $$
                        \int_{x=2}^\infty \frac{1}{x^{p+1}\log(x)}\;dx
                    $$
                    for different values of \(p\). 
                 </li>
            </ol>
        </p>
    </div>
</details>

Anyways, these are two fun ones. There are a whole host of similar integrals, where we swap out \\(D(k)\\) or \\(P_k\\) for some other function: we can use \\(F_k\\) to find the \\(k\\)th Fibonacci number or pick some other interesting value.

Remember, my goal here isn't to give problems to students where I can assess their work and assign a grade: these are good problems because they allow students to explore the series, learn a bit about some other math that is interesting, and try a lot of strategies. They're great ways to spend a class period thinking about, talking about, and doing good mathematics!

It doesn't really matter that I've had to cut some of this fun stuff from class. I've still found some good ways of getting stuff like this in front of students when we can. 

## References

[^harmonic]: To see some of the many explanations of proofs of this, see the paper, [The Harmonic Series Diverges Again and Again](https://stevekifowit.com/pubs/harmapa.pdf), and its follow-up, [More Proofs of the Divergence of the Harmonic Series](https://stevekifowit.com/pubs/harm2.pdf).
[^integral]: [Theorem 8.4.7. Integral Test](https://www.discovercalculus.com/web/sec-IntegralTest.html#thm-IntegralTest) from [Discover Calculus](https://www.discovercalculus.com/web/frontmatter.html)
[^comparison]: [Theorem 8.7.4. Direct Comparison Test](https://www.discovercalculus.com/web/sec-ComparisonTests.html#thm-DirectComparisonTest) from [Discover Calculus](https://www.discovercalculus.com/web/frontmatter.html)
[^prime]: [Prime Number Theorem](https://en.wikipedia.org/wiki/Prime_number_theorem#Statement) on Wikipedia