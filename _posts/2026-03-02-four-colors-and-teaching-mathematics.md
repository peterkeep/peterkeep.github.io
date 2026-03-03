---
layout: post
title: Four Colors and Teaching Mathematics
subtitle: What the Four Color Theorem and its history tells us about the role of humans and proof in mathematics education.
thumbnail-img: /assets/img/posts/fourcolor.png
share-img: /assets/img/posts/fourcolor.png
tags: [math, teaching, AI]
author: Peter Keep
mathjax: no
---

I was reminded of the Four Color Theorem the other day. I wasn't thinking about maps. I wasn't thinking about about graphs of any kind, honestly. 

I was being asked a question about AI and calculators.

Instead, I was wrapping up a talk with a coworker at our college's Professional Development Day, titled [Generative AI ∉ (Teaching ∪ Learning)](https://www.peter-keep.com/2026-02-06-generative-ai-is-not-an-element-of-teaching-or-learning/). And near the end, when we were answering some questions, one of my colleagues asked me what I thought about the claim (that they did not personally hold) that LLMs like ChatGPT are just "calculators for writing." And it brought up a lot of feelings: there was my knee-jerk reaction that calculators aren't being used to sexually harass women on social media sites, and our government isn't trying to co-opt calculators as a way of surveilling our country's population or plan and execute a terrorist attack on Iran. But then I also started thinking about how generative AI is being used in mathematics, and how, unlike a calculator, it undermines much of the things about mathematics that a large portion of the mathematics community values most.

On February 24, the Atlantic released [an interview with Terence Tao by Matteo Wong](https://www.theatlantic.com/technology/2026/02/ai-math-terrance-tao/686107/) about generative AI in math. While I don't personally hold Tao as the perfect spokesperson for the mathematical community (indeed, I think he might be the one of the worst candidates for this, in that he is far from the typical mathematician), this part of the interview stuck out:

> **Wong:** You’ve written that when human mathematicians approach a new problem, regardless of whether they succeed, they produce insights that others in the field can build on—something AI-based proofs don’t provide. How come?
>
> **Tao:** These problems are like distant locations that you would hike to. And in the past, you would have to go on a journey. You can lay down trail markers that other people could follow, and you could make maps.
>
> AI tools are like taking a helicopter to drop you off at the site. You miss all the benefits of the journey itself. You just get right to the destination, which actually was only just a part of the value of solving these problems.

And if you know much about the history and proof of the Four Color Theorem, you might know why I have been thinking about it.

After my talk, and after I answered the question about comparing generative AI to calculators (my actual answer was just that with this new technology, it is impossible to untangle the technology itself from the use of it by the capitalists backing it), I ended up chatting with the colleague who asked me the question. And in our discussion, I brought up what I see as a main pillar of mathematical thinking: the search for understanding some object or concept. Sure, we love to generate interesting results, and we definitely love to classify things by creating definitions, and some of us even love applying those definitions and results to real-world problems. But one of the most important things in mathematics, and certainly in my approach to *teaching* mathematics, is understanding why we care about classifying objects using some definition and understanding why the results that we generate are true or important.

Mathematical proof, in my classes at least, serves as a tool for illumination and explanation. 

# The Four Color Theorem

The story of the Four Color Theorem is interesting due to the contrast of the easy-to-state claim with the long journey to a proof. Francis Guthrie noticed in 1852 that, while coloring a map of the counties of England, only four colors were needed. Francis Guthrie asked around to see if anyone knew why this was the case, and an open problem was formed.

<div class="box-warning">
    <b>Four Color Theorem:</b> The regions of any simple planar map can be colored with only four colors, in such a way that any two adjacent regions have different colors (where <b>adjacent</b> means that the regions share a boundary larger than a single point).
</div>

{: .caption}
![]({{ '/assets/img/posts/fourcolor.png' | relative_url }})
*Example of a colored map from [Wikipedia](https://en.wikipedia.org/wiki/Four_color_theorem)*

What followed was a flurry of attempts to prove this conjecture, none of which stood up against careful scrutiny. Around 40 years later, Percy Heawood proved that any map could be colored with five colors. 

The interesting part of the story, the part that I was interested in at least, picked up again in the 1970s, when two mathematicians at the University of Illinois announced that, with the help of computers and a sophisticated algorithm to check a huge amount of cases, they had proved the Four Color Theorem. This was the first instance of a computer-assisted proof, and the proof itself remained mostly a mystery since so much of it was hard to verify by people.

This, at least, is the story I learned as an undergraduate student, albeit with some names and dates added that I had not remembered. The proof was generated by a mixture of mathematician and algorithm, and people were critical. I learned that the search for a proof was still on. Sure, even though most mathematicians eventually believed that the Four Color Theorem was true, the original question had not been answered. Augustus De Morgan, Francis Guthrie's brother's advisor, wrote:

> A student of mine asked me to day to give him a reason for a fact which I did not know was a fact—and do not yet. He says that if a figure be any how divided and the compartments differently colored so that figures with any portion of common boundary line are differently colored—four colors may be wanted but not more—the following is his case in which four colors are wanted.

The initial search was for the *reason* that this fact was true. Sure, the mathematical community hadn't realized yet that this was, indeed, a fact, but Guthrie would no doubt find the computer assisted proof unsatisfactory. It didn't explain anything about why only four colors are needed. That's the story I learned. The mathematicians that continued searching for an "elementary" proof of the Four Color Theorem were really searching for understanding.

So this was a part of my explanation to my colleague.

What Tao mentions in his interview, the metaphor of math as a journey, we can see reflected in this story. With the computer-assisted proof, many mathematicians felt those missing trail markers needed to be filled in. Some mathematicians might argue that they were still there...just maybe spaced out a little further and requiring some GPS to use in between. And that's still valid for a journey, but it maybe doesn't fit everyone's idea of what a good hike should be.

But it seems clear to me that, while we're in class doing mathematics with our students, we should retain as many aspects of Tao's "journey" as possible. We should ensure that our proofs are illuminating, and guide students to asking Guthrie's question: *why* is this fact true? Maybe we should be using this story-telling medium to convince ourselves and our students that this has always been one of the primary purposes of mathematical thought and proof, and we certainly shouldn't be searching for shortcuts around it now.

<div class="box-note">
    <h2>Related</h2>
    <ul>
        <li>
            <p>
                Spencer Bagley recommended the book <a href="https://press.princeton.edu/books/paperback/9780691158228/four-colors-suffice" target="_blank"><em>Four Colors Suffice</em></a> by Robin Wilson, claiming that it is <q>one of the best pop-math books I've ever read.</q> I bought it immediately and it should be delivered soon, so I'm excited to read that and learn a bit more about the story of the Four Color Theorem.
            </p>
        </li>
        <li>
            <p>
                Jeremy Kun wrote a really thoughtful blog post titled <a href="https://buttondown.com/j2kun/archive/no-employees/" target="_blank"><q>No Employees</q></a> that does a great job outlining the way that the technology cannot be disentangled from the use: <q>But we can't divorce the technology from its commercialization. This is a tragedy of modern society, that all new technology is fashioned into a financial weapon before it is viable.</q>
            </p>
        </li>
    </ul>
</div>

