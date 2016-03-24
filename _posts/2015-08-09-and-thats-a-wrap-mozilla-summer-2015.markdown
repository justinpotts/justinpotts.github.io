---
layout: post
title:  "And That's a Wrap! - Mozilla, Summer 2015"
date:   2015-08-09
categories: mozilla
---
It’s been two weeks since my summer ended with Mozilla, and I can’t say it’s
been easy to take a break. I’ve spent so much time with the team, from attending
the work week in Whistler, to chatting with them on IRC. I had a blast working
with Dave Hunt on my project, and learned a lot more about test automation, QA,
and web development.

This summer, I was being mentored by [Dave Hunt](https://twitter.com/davehunt82),
who also works on the Web QA team with [Matt Brandt](https://twitter.com/m8ttyb)
— my mentor from last summer, and still an amazing person I look up to and can
rely on to answer questions and help me out when things get tough. For the
summer of 2015, I chose to work on a project I was a somewhat familiar with, but
with a twist.

In Web QA, we use a plugin called pytest-mozwebqa, which allows us to run our
Selenium test suites using pytest. To make this applicable to a wider audience
outside of Web QA, Dave Hunt decided to take on the task of rebuilding it into
pytest-selenium. In doing this, we added support for multiple variable files,
made writing tests more efficient, and improved the usability and decreased the
complexity of the plugin.

This was a definitely a project that took me out of my comfort zone. Rather than
coding tests to be run by this plugin, I was now writing the plugin to allow
these tests to run. As a visual person, this was hard for me. I work really well
in situations where I can see the progress I am making, and am able to understand
what it is doing. For example, when writing automated tests, I can see the page
interaction, where it gets hung up, and visualize each step of the test-running
process. However, with developing the plugin, I would make a change, and usually,
if there was no visible change, all was well. It was a lot of back-end coding,
and that taught me a few things:

1. I am a visual person. I like to see what I am doing and know how what I write
affects the other aspects of the system its working with, whether it’s designing
and building a website or writing an automated test.

2. Things are not always as complicated as they seem. I had thought that coding
pytest-selenium would be a lot more complicated than it was. Not to say it isn’t,
but I was imagining a lot of files, a lot of things I had never seen before, and
the need to ask a lot of questions. However, after breaking it down into its
component parts and trying to fully understand how each part works, why it works,
and what it does, I could start to see what I was doing.

3. Asking for help when you need it ALWAYS clears things up. This is where a huge
thanks to Dave is due. I like to ask a lot of questions, and there’s no way I
could have figured some of this out by myself. With his support and willingness
to sit down with me and talk me through the motions, I was able to grasp the
concept and see what I was supposed to be doing.

4. I’m going to miss all these guys so much while I’m gone: Stephen Donner, Matt
Brandt, Dave Hunt, Bob Silverberg, Krupa Raj, and Rebecca Billings. They have
all played a huge role in my accomplishments and time I have spent with Mozilla
over the years. They have always been supportive and willing to work with me and
treat me as part of the team, from going out to team dinners to valuing my input
during meetings. Whether it’s next summer during an internship, or getting a full
time job, if I’m not working with them, I hope my team will be as great as they
are and work with the same chemistry and shared passion between them.

So where do I go from here? I’ve spent another amazing summer with Mozilla as a
contributor, making this the second time. From here, I’d like to make it a third,
only I’d like to return as an intern, possibly in web development. QA has been a
lot of fun, but I’ve been here for 1.5 years, and it would be great to try
something new. I want to branch out and expand my skill set around software
development. Plus, with my experience in QA, I will be able to catch errors and
bugs before my code even ships, and better understand the cycle between devs and
QA in effort to make it a more enjoyable experience on both sides.

Mozilla’s internship applications open in September, so until then, I will be
strengthening my portfolio and reinforcing my coding skills. If all goes well,
I’ll be shipping off next summer to live either in Mountain View or San Francisco
(hopefully the latter) and be working on building some cool stuff, supporting the
open web.

Thanks for a great summer, Mozilla.
