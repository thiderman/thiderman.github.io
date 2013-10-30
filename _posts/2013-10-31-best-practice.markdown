---
layout: post
title: Best practices and when to avoid them?
category: post
---

This is actually not a blog post. Well, it is, but it was written as the
manuscript for a talk for the [Stockholm Python User Group][pysthlm].

---

Just as a little disclaimer before I start talking, this is not really
a standard talk. This is the story about a talk that never happened, and it is
almost more of a monologue that will hopefully inspire discussion. So, let me
tell you how the hell this happened.

As you probably know, we recently had a poll regarding what the topics for
talks should be. When **Best Practices** was chosen, I was very quick to sign
my talker skillz up for a talk. I thought I'd do the very effective
*Inflammatory Rebuttal* kind of talk. You might be aware of the kind; on any
conference for any given subject, Django for example, there will always be
three or four talks about "*Why Django sucks and is horrible*". These talks are
inflammatory to gain an audience, but tries to give some kind of constructive
notion at the end. I thought I'd do this for best practices.  Trendy and edgy.
Such wow.

---

I was going to be inflammatory about Best Practices, and I was going to do it
with my [doge][doge] project. Doge is my current little love, and in my mind
I had skipped literally every practice in the book while writing it. To me,
I had written it for teh lelz and it was a chaotic mess and an extraordinary
example of bad practices galore.

...and then I started to look at it. I was right about one thing. I did miss
out on the most important best practice of all in any programming language;
I had no tests what-so-ever. But, other than that and to my chagrin, I found
that I actually did follow many best practices without even thinking about
them.

I mean, I religiously follow [PEP8][pep8] (as one should), I care for Python2 and
Python3, and I even write for dependency injection even though I have no
intentions what-so-ever in writing any tests for this specific project. This
made me think; "What things are best practices, really? I also do Object
Oriented Programming. Is that a best practice? It's literally built into the
language, but I'm not really forced to use it. Does that make it a best
practice to do it?"

I kind of realized that I don't really know what the hell a "Best Practice" is.

---

So, naturally, [I hit the Wikipedia][bp]. I didn't even make it to the third
sentence until the word "buzzword" reared it's head. In all honesty, that kind
of wiki page is the kind that I as a developer really do not like. It's very
long, equally vague, and the vague length is filled with the bad kind of
manager speak. What it doesn't contain is anything very related to, well,
developing.  The only real takeaway was that "best practices are things that
are not mandatory but are considered as good goals".

So, Wikipedia didn't really give me much. Then I remembered! The DD's!
Originating from [Test Driven Development][tdd], there are now loads of those.
TDD is the most well known one. It states that if you want to be a good
developer, you should write your tests before your code. That feels like a best
practice, right? It's literally a practice you do so that you can strive for
perfection, by utilizing tests. A subset of TDD, BDD (or [Behavior Driven
Development][bdd]) is also kind of popular.

But everyone knows of those! I find joy in the less common ones!  There is also
RDD, [README Driven Development][rdd]! It strives for the developer to write
a complete README before writing any code. Or tests, for that matter. The
imperative is that if you write your README first, you will need to document
your interface and put your design idea into practice testing before even
coding anything. You'll eventually need a README anyway, so utilizing it to
your advantage early on only makes sense.

Relatedly, there is DDD, Documentation Driven Development. Write documentation
first. This will net you with, well, documentation.  And finally, there is
a blog post about [Asshole Driven Development][add], which has tons of new ones
in the comments.

Anyway, most of these driven developments strive to make developers take some
kind of preemptive action before coding so that they don't forget about
important things. To me, that sounds like a very sound definition of a best
practice.

---

I was pleased. I know knew more than I thought I knew before, and that is
always a very good feeling. But, it still didn't really feel completely right.
The DD's are very high level, and I felt that there had to be something else.
Things like PEP8 and really low level things like "writing good comments" are
not really there either, and I feel that they belong.

Frustrated like a Farnsworth, I went into my Angry Dome for a while to ponder.
Once again, I emerged victorious! After cautious thinking, I reasoned that the
DD's are a subset of a higher abstract. Now, to me, a "best practice" is
anything that will help someone else to use your code. And also the inverse;
things that when absent from a project make you go "wow this is bad Python".
This makes the DD's be part of best practices, because all of them will force
the developer to strive for the good things.

So, down to the nitty-gritty. I need some examples of best practices in Python!
PEP8? Definitely. Using performance-focused language features like generators?
Absolutely. Writing comments and docstrings? Probably, but not excessively
(aka, pointless documentation). Having a proper and working `setup.py` that can
be used for distribution and testing? Of course.

As I was sitting and writing this list, I became more and more bothered by the
fact that no one else seems to have made an effort to document this and put it
up on the interwebs, at least not for Python.

---

So, in the beginning I was going to hold this talk about why you should not
follow best practices, sometimes. Apparently, my choice of topic was a failure
for me, because I found out that I don't really know what best practices really
are. I think I am arriving on an idea and some understanding, but in the end
I am now much more interested in documenting Python best practices and putting
them on the webs.

And, I would like to do that with you guys. During the Open Space after the
upcoming speakers, I will sit down with a whiteboard or a laptop or something,
and I will, hopefully together with a couple of you, try to document as many
best practices as possible, with the intention of putting them online. If you
would come and join me, that would be most brilliant.

If that is successful and we produce something, maybe I will return in a couple
of meetups and actually hold the talk I intended to hold here tonight.  Who
knows? :&gt;

That concludes my monolouge talk thingy. Does anyone have any questions?

---

Thanks for your time, and see you during the Open Space. &lt;3

xoxo


[pysthlm]: http://www.pythonista.se
[doge]: https://github.com/thiderman/doge
[pep8]: http://www.python.org/dev/peps/pep-0008/
[bp]: http://en.wikipedia.org/wiki/Best_Practice
[tdd]: http://en.wikipedia.org/wiki/Test_Driven_Development
[bdd]: http://en.wikipedia.org/wiki/Behavior_Driven_Development
[rdd]: http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
[add]: http://scottberkun.com/2007/asshole-driven-development/
