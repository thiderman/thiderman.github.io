---
layout: post
title: Technical details of this blog
category: meta computer
---

One of the reasons I never really started blogging was that I, as a developer,
was too proud to use WordPress or any similar solution. If I was to have
a blog, I would write one myself, damnit. How hard could it be?

It's not, really. But doing so is an undertaking, and undertakings are
something I've been very good at avoiding. Ergo, blog never happened.

---

Enter [Jekyll][jekyll]. Jekyll is a blog engine written by
[Tom Preston-Werner][mojombo], the dude that started [GitHub][gh]. It has no
backend, and is basically a Ruby script that takes a couple of files and makes
HTML out of it. Being written by the main GitHub dude also grants Jekyll an
awesome perk: GitHub hosts Jekyll pages for free!

That means that this blog [is an open repo on GitHub][io]! It also means that
I can write [the file that generates this page][this] in vim on my laptop, and
that you can create a [pull request][pr] should I make any mistake. :D

It should also be noted that this blog has practically no features. No
comments, no tags, no searches, no auto-post to Facebook and Twitter and etc,
no statistics, pageviews or user trackings. It is solely focused on
[content][self],
which is something that really speaks to me. I _could_ add those features, with
the project being Open Source and all, I just don't want to. :&gt;

All in all, Jekyll is so well written and easy to use I even forgive it for
being written in Ruby.

---

So, if you are technically skilled enough to understand the lingo above,
I challenge you! You should start a Jekyll blog as well! It's a 15 minute
setup, you just fork [my repo][io] (or [the design I based it on][left]) change
a few things, and start writing.

It doesn't even really matter what you write about. With writing, it is very
much quantity over quality until quality surfaces by itself.

It's not like you have something to lose. &lt;3

[jekyll]: http://jekyllrb.com
[gh]: https://github.com
[mojombo]: http://twitter.com/mojombo
[io]: https://github.com/thiderman/thiderman.github.io
[pr]: https://github.com/thiderman/thiderman.github.io/issues
[left]: https://github.com/holman/left
[self]: /
[this]: https://github.com/thiderman/thiderman.github.io/blob/master/_posts/2013-08-14-technical-details-of-this-blog.markdown
