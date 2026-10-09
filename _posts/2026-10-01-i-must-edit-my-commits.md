---
title: I am once again being told to edit my commits
subtitle: Or, the cost of perfection.
link_preview: Or, the cost of perfection.
post_date:
modified_date:
tags:
  - reflections
comments: true
hidden: false
---
> The ceramics teacher announced on opening day that he was dividing the class into two groups. All those on the left side of the studio, he said, would be graded solely on the *quantity* of work they produced, all those on the right solely on its *quality*. His procedure was simple: on the final day of class he would bring in his bathroom scales and weigh the work of the “quantity” group: fifty pounds of pots rated an “A”, forty pounds a “B”, and so on. Those being graded on “quality”, however, needed to produce only one pot—albeit a perfect one—​to get an “A”. Well, came grading time and a curious fact emerged: the works of highest quality were all produced by the group being graded for quantity. It seems that while the “quantity” group was busily churning out piles of work—and learning from their mistakes—the “quality” group had sat theorizing about perfection, and in the end had little more to show for their efforts than grandiose theories and a pile of dead clay.
> 
> ---David Bayles and Ted Orland, [*Art & Fear*](https://tpl.bibliocommons.com/v2/record/S234C3140551), p. 29
> {: .attribution}

This June, I ended a nearly-one-year stint working remote as a programmer at a quantum research lab. It sounds more impressive than it actually was—I don’t know any quantum physics. I just worked on the software.

The software team was quite small. Just me working part-time, the lead developer who we’ll call Joe[^1] and a PhD student named Mathieu. Joe had been there for about a decade, and Mathieu for just a couple years. I also had a manager but he barely spoke to me so we’ll leave him out of this.

Going into the job, I thought it’d be more like the startups I had been a part of previously: small, agile, collaborative. Boy, was I in for a shock.

Mathieu was quite nice and very personable. He and I would talk back and forth on any problems or tasks that would arise. I visited the lab once and got to know him a bit in person—he spent most of his time thinking about quantum physics but used to play curling, from what I remember. Mathieu would also instruct and keep track of the co-op interns, and would probably make a good manager, not that he wanted to be.

Joe, meanwhile, kept to himself. I hardly got to know him in my time there. And his code review process was extremely particular. I think it was partially rooted in the need for the software to work in real-world conditions, partially that it was hard to test software that communicates with satellites remotely, and partially his perfectionism. And to add to that, he had a particular coding style that he wanted me to emulate, which I found difficult and unnecessary.[^2] Eventually I found myself overthinking even the smallest of changes, which I don’t think was healthy, and reminded me of how I used to overthink things more often when I was younger.

<details markdown="1">
<summary>Aside: Technical Debt</summary>
In coding, there’s this idea of *[technical debt](https://wiki.c2.com/?WardExplainsDebtMetaphor)*. It’s what happens when you make something that ends up being difficult to maintain or isn’t future-proof. On the surface, this sounds bad, but I think tech debt can be a good thing in moderation.

What does having zero tech debt look like? It looks like scope creep. It looks like writing code and building things while considering every possible use case imaginable. For small projects this is somewhat feasible, but for large ones it’s virtually impossible.

What does too much tech debt look like? It looks like having to work around old, bulky systems that don’t make sense anymore. It looks like taking forever to get even the simplest tasks done.

Feel free to disagree with me, but I believe both having too much and too little tech debt forces teams into taking lots of time to work on things. Having some tech debt gives you the flexibility to write code and build things without having to consider every possible contingency.
</details>

---

I first realized I was a perfectionist in grade one, when Mme Donald kindly told my parents so.[^3] It sure explained why I was very particular over how I would do homework, or why I would take longer to do anything really.

Even to this day, I feel the lingering hold it has over me. Left unchecked, perfectionism as a condition leaves you in a daze, working long hours to get every detail right until you inevitably lose the motivation to finish what you started. Or it can paralyze you before you even start, dreading action because of how the outcome will undoubtedly fail to meet your exceedingly high standards.

I’m much less of a perfectionist nowadays than I used to be. I’ve come to realize that it’s often better to make many things imperfectly than to spend all your time on one thing. (Even so, I can’t help but feel an aching in my soul whenever I need to take shortcuts or I see someone doing something poorly that I feel responsible for.) What the job at the quantum lab reinforced in me is that it’s okay not to be perfect. In fact, I’ve seen how the persuit of perfection can not only demotivate yourself, but also drive other people away.

> All of us who do creative work, we get into it because we have good taste. But there’s this gap, that for the first couple years that you’re making stuff, it’s really not that great. But your taste is still killer. Your taste is good enough that you can tell that what you're making is a disappointment to you.
> 
> A lot of people never get past that phase, they quit. And the thing that I would just say to you with all my heart, is that most everybody I know has gone through a phase of years where they had really good taste, but they knew it fell short.
> 
> You gotta know it’s totally normal, and the *most important possible thing you can do* is a lot of work. Do a huge volume of work. Because it’s only by going through a volume of work that you’re actually going to catch up and close that gap.
> 
> It’s gonna take you a while. You just have to fight your way through that. You will make things that aren’t as good as you know in your heart you want them to be, and you’ll just make them one after another.
> 
> ---[Ira Glass](/notes/ira-glass-on-taste/)
> {: .attribution}

I try to remind myself that it’s usually better to do something imperfectly, just to have something out there, despite the dissatisfaction of not attaining my goals for quality and the fear of poor reception. *To err is human*, as they say; *to forgive, divine*. 

I pray you'll forgive my mistakes. And your own too.

[^1]: Names have been changed for anonymity.

[^2]: Git commits should be self-contained. This commit should appear before other commits—please reorder them. Proper capitalization and punctuation in comments and git messages please; this is a professional working environment. (*I’d never been asked to edit individual commits before.*) Nit: rename this already-descriptive variable to a slightly different name. This block of code that you didn’t write yourself but are moving around—is this really the most efficient, standardized way of doing things? Looks great now. Wait, I changed my mind, can you revert this code to what it was before? Thanks, LGTM.

[^3]: I cried a lot that year for unrelated reasons.
