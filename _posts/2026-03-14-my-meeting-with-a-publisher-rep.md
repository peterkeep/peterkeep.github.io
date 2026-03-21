---
layout: post
title: My Meeting with a Publisher Rep
subtitle: Ed-Tech is seemingly working towards the opposite goals that I'm working towards.
thumbnail-img: /assets/img/posts/doenet.png
share-img: /assets/img/posts/doenet.png
tags: [math, teaching, OER]
author: Peter Keep
mathjax: yes
---

This post is based on something I wrote on social media that I wanted to expand on a bit. You can read the thread on Bluesky here, but I have some more thoughts.

<blockquote class="bluesky-embed" data-bluesky-uri="at://did:plc:o4kwpag2v3p6qd3ptdr3bmtk/app.bsky.feed.post/3mguejjbv6c25" data-bluesky-cid="bafyreihmsgkhdvb2e6hkuoe65k45cgnzh5o7i4hpjv2wcsfryn3io5ukzq" data-bluesky-embed-color-mode="light"><p lang="en">A bit ago I sat in a meeting with a publisher sales rep where they demonstrated their new online platform for calculus. It&#x27;s one of the major publishers and it&#x27;s used on campus in other math classes, and it ended up being another reminder of how disconnected these ed tech people are from teaching. 🧵</p>&mdash; Peter Keep (<a href="https://bsky.app/profile/did:plc:o4kwpag2v3p6qd3ptdr3bmtk?ref_src=embed">@mathprofpeter.bsky.social</a>) <a href="https://bsky.app/profile/did:plc:o4kwpag2v3p6qd3ptdr3bmtk/post/3mguejjbv6c25?ref_src=embed">Mar 12, 2026 at 7:09 AM</a></blockquote><script async src="https://embed.bsky.app/static/embed.js" charset="utf-8"></script>

I'll likely repeat some of the stuff in this thread, so sorry for the redundancy.

# Setting up the Meeting

A well-known phenomena in higher ed has been happening to me more often lately: publishers sending a rep to my office to talk to me about whatever new products they're trying to push. Some online homework suite. A course management platform that is somehow different enough than everything else that it will be the one that will work. Here's a product to make teaching online classes better (based on a very specific definition of "better")!

Maybe publishers are putting more energy into their sales process. Maybe they've clocked that I'm a new department chair and this just comes with the job. Maybe there's something else that they're seeing that makes them think my department is interested in these products. Who knows? But they come and they email and they drop off cookies. And finally, one of them got me with something that I thought would be interesting. One of the publishers has a widely-used tool for placement testing and also pre-calculus classes that is somewhat popular on our campus, and they're building a version for their calculus classes. And maybe it would be good for me to learn a bit about it so that I could provide information to faculty in my department that might have questions about it. This seems like a good goal, even though I have no interest in using it for my classes.

So I agreed to a 45-minute Zoom call with a rep from the company to show me some the stuff they've built and for them to solicit some feedback from me. 

A good plan. I scheduled the meeting.

# The Meeting

We logged on, made some small-talk about the semester and the weather, and then the rep shared their screen and showed me what they were working on. Some points, right to start:
- The reps who have talked to me about this product kept making a point to emphasize the conceptual understanding that they were focusing on, instead of just computations. The rep in this specific call made a point of that, as well. This would be part of the demo.
- The specific rep on the call did not have a background in math, and felt like they could pretty clearly talk about the Calc 1 part of the demonstration, but clarified that they wouldn't be able to answer many questions about the Calc 2 content, but that they would be able to talk about how students would interact with the parts of the demo that they showed me.
- I was often given control of the cursor on their shared screen, and encouraged to interact with the demo both as a student and also using my instructor lens.

One of the first things I was shown was a new way of testing conceptual understanding! I thought I might pick up some interesting ideas about how I teach and assess students' understanding of things like the derivative. 

The rep excitedly showed me their demo question: given a graph of \\(f(x)\\), I was to sort the values of some derivatives in order from least to greatest. The graph was a static image with no interaction. The rep showed me how students could get hints or feedback: I clicked an icon to bring up some text and more pictures with tangent lines to remind students what a derivative was. They could also watch a video.

It seemed like a combination of (1) a not-very-novel idea and (2) a pretty underwhelming implementation of the idea.

There were some other small demos, but they were largely uninteresting.

Then, we moved on to Calculus 2. I was interested to see what they had to show, because it's my favorite class to teach, and they were so consistent in their messaging that this was a new focus on conceptual questions. There are so many rich and interesting concepts in Calculus 2, so I was sure to find something exciting.

The two examples that they had to show were Integration by Parts and Polar Curves.

They showed off their first example of a "conceptual question:"

> Given \\(f'(3) = -3\\), \\(f'(0)=2\\), \\(f(3)=4\\) and \\(f(0)=1\\), evaluate \$$ \int_{0}^3 f'(x)\cos(x)\;dx.\$$

I understand the purpose of a question like this: it's a test to see if a student can do integration by parts without relying on an integral calculator website or whatever. I get it. I also understand why this question uses a definite integral: it's easier for the automated grading system to check the correctness of an input when it's a number compared to a function.

So it's not like I think these questions are meaningless. But I did ask the rep where the conceptual emphasis was, compared to computational. Isn't this still a computation problem? This was a hard part of the conversation. Remember, the rep had mentioned that they were less confident with the Calculus 2 material. So while I was asking if students get the opportunity to think about the Product Rule or the roles of \\(u\\) and \\(dv\\) in our formula, our conversation stopped. And it's not their fault! They were, first and foremost, a sales rep. But it was frustrating to have what I thought were pretty foundational concepts not represented at all in the conceptual questions being advertised.

The last part of the call was a demonstration of the graphing utility by looking at a polar function. The prompt was to plot a function like \\(r(\theta)=\sin(2\theta)\\). In the graphing utility, I was presented with some options for the general shape of this graph: a flower, a spiral, a circle, and a cardioid. I might be misremembering, but you get the idea.

When I selected the flower shape, I was asked about the specific graph, like the number of "petals" and some key points. Once I input that, I pasted the pre-built shape into the polar plane.

I asked some questions, and found that the goal was to create a graphing utility that can test students on building graphs of polar functions without students sketching it with their pencils. This was a kind of halfway point between drawing the graph by hand and plotting it by typing `r=sin(2theta)` into Desmos. I had been pretty negative in my feedback throughout the meeting (and I know that I don't do a good job of masking my facial expressions), so I tried to be a little bit more positive here. But in the end, I was left explaining that I just do not care about my students plotting functions by hand in a calculus class. And this just opened up a conversation (that I kept short for both my sake and the sales rep's sake) about goals and objectives in teaching.

# Individualized Learning Paths and Automated Assessment

Something else that stuck out to me throughout the demonstration was that the rep kept talking up the "individualized learning paths" that would be given to students. The idea is simple: based on how students answer questions and which topics they show they understand or don't understand, the ed-tech company recommends a custom-built learning path for each student. That way, students are working on the stuff that they need to work on! It's great, right?

I asked a bit more about this, because I know a bit about how these kinds of course material suites are used in practice: sure, they can be kind of supplemental material for students to use in order to reinforce certain skills, but more consistently these are used as a full course suite. Maybe the instructor provides some of their own learning material, but often these are touted as a kind of full-course-package! Remember how students can watch some videos to get help? These publisher videos can be used as the primary course materials. And while this is a huge problem to me, this isn't the specific problem I had with the demo.

The issue I had was that the primary learning spaces for students in these courses with these materials were *individualized*. But this is essentially the opposite of my goals in a classroom. In almost everything I do in a class, I am trying to foster collaborative work. I am not always as successful in this as I want to be, but this is the goal. I want students to work with me and with each other to explore and discover the course content. I don't want to have them siloed off on their own! I don't think this is how mathematics should be done, and I don't think this is how teaching and learning should be done. And, less important, I want my job to be enjoyable, and I enjoy seeing and being part of the collaboration and discovery in class.

The other big theme of the call, both implicit and explicit at times, was automating assessment and feedback. The types of problems posed, the types of questions asked, and the stuff chosen for this demonstration all pointed towards having the product handle the assessment and feedback process. I asked about this a bit, and was told that the company was planning on implementing a faculty question-authoring feature. But this doesn't really address my concerns.

During the whole demonstration, all I could see was a system that was built to take assessment and feedback, two pillars of what it means to teach, and strip it away from faculty. But then what parts of teaching are left? The initial presentation of material? Even that, though, is supplemented (or fully replaced) by the publisher-provided videos. Or at least, that's what they're trying to do, here. 

But this reveals a complete lack of understanding of what it means to teach. Teaching is, obviously, more than just presentation of content. It *has* to be. And assessment is more than just assigning a score to an answer and linking to some text and pictures as an explanation. It *has* to be. It doesn't have to be the stuff I do in my class: the way that I provide feedback or the way that I assign grades or the way that I present content are all ways that work for me in my classes. And it should be different for other people. Because the differences are based on the differences in us as people. 

Teaching and learning are both deeply human activities. Humanity needs to be at the center of what we do in a classroom. Sure, that means that I need to be very intentional with how I talk to and treat students. They are humans, and deserve to be treated that way. But it also means that the ways that we use technology and automation should be supporting that humanity and human interaction, not replacing it.

So the pitch that the rep gave me--one of automated grading and instant feedback for students--didn't really connect with me. I don't value timeliness at the cost of humanity! I don't *want* my students to get instant feedback that encourages them to remove themselves from a learning community. Anything that pushes students to isolate themselves from their peers or professors is harmful!

# Ending the Call

At the end of the call, the rep asked me if I'd ever be interested in trying this system in my calculus classes. Before I could stop myself, I said, "Oh absolutely not, I would never put my students through this! I'm just here to get information for our department, so I can relay what I saw if anyone asks about using this." It made for an awkward end to the call.

After the meeting, I built a version of the derivative problem in Doenet, a super useful tool for building interactive activities or explorations of math that is committed to being free to use and collaborative in nature. It's still imperfect (I built it in around 30 minutes).

<iframe src="https://beta.doenet.org/embed/vxyE7NSUR86qioBoV4Ehvp" width="90%" height="700" style="border: 5"></iframe>

This isn't a post about Doenet, but it's a good tool, and I'm a big fan. Check it out at [beta.doenet.org/](https://beta.doenet.org/). You can see the little applet I made here: [Order the Derivatives](https://beta.doenet.org/activityViewer/vxyE7NSUR86qioBoV4Ehvp).

My plan for this activity is essentially the opposite of what I was shown. It won't be a question on a highly individualized quiz for points. It won't even be a part of any formal graded work. It's just going to another option for a quick group activity at the beginning of a class session when we're in the middle of learning about derivatives. It's a way for students to sit together, talk through what they're looking for, get some hints, check their understanding, and then move on to talking about the idea of a derivative with more depth. From here, what does *slope* really mean? What if we weren't thinking about this problem graphically? How do we interpret a derivative more generally? These are some of the conceptual questions that we can think about!

Another aspect of this that I like is that thinking about the graphical connections between \\(f(x)\\) and \\(f'(x)\\) is a big theme in Calculus 1. I start the semester off with a first-day activity that involves a slow-reveal graph that ends up being a representation of a derivative. We talk about it when we learn about the derivative. We talk about when we use the derivative to analyze the function itself. And we use it to discover the connection between areas and antiderivatives, building to the Fundamental Theorem of Calculus. (You can see how I do this here: [The Fundamental Theorem of Calculus](https://www.discovercalculus.com/web/sec-FTOC.html)). 

These are all things that are seemingly left out of the pitch for big publisher material. Because they don't factor in to the goals behind the creation of this kind of course suite. Instead, it's all about isolating students into their own space to learn as independently as possible, and to automate the feedback and assessment portion of the job. Not teaching effectively or fostering learning.

Lastly, just for fun, here's a quick desmos animation I made a few semesters ago. I don't care about students plotting the graph of \\(r=\sin(2\theta)\\) on their own, but I do want them to think a bit about how polar curves work, and especially how they might behave slightly differently than we are used to.

<iframe src="https://www.desmos.com/calculator/9ykod7wp6v?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

There are a lot of questions to ask: why does this look like a flower? Why does the path of the curve end up moving between the quadrants in a non-standard way? What happens when the curve is passing through the origin? Even before we think about calculus with polar curves, I would hope that my students are thinking about questions like this, as opposed to just memorizing which specific kind of shape this function will form.

# What Now?

I suspect that this won't be the end of the "reps popping by my office" phenomena. Sure, they didn't make this sale and I feel like I was pretty clear that they won't make this sale with me ever, but I don't think that's going to buy me peace from them. Maybe I need to come up with a non-combative way of saying clearly that I am not interested.

I still think that information-gathering is important. I haven't used these kinds of course materials in years, and so I think it is worthwhile to infrequently check in on it all. Especially since I'm in a role in my department where faculty could reasonably ask me questions about these tools. I should be in a position to answer some basics, and I'm always happy to share my opinion as well. And now I can at least point to some things happening and tools created in the OER community that are, simply put, *better* than whatever is happening in the paid publisher software. I think it's just that the goals for each group are different. Opposite even.