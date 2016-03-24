---
layout: post
title:  "Pattr - State of Security"
date:   2015-12-01
categories: development
---
As of November 30, 2015, 5:00 PM, all chat rooms on Pattr are encrypted via an
SSL certificate.

Our mission: Pattr believes in fostering an open web, with maximum security
and privacy for its users. We do this buy building creative tools and
platforms for users to engage in untracked conversations, providing intuitive
design while never sacrificing usability.

As part of upholding our mission, we asked our users to donate in effort to
afford an SSL certificate and they answered. We raised enough to afford the
certificate, plus some which will aide in future efforts to support hosting and
more features.

An SSL certificate prevents third-parties from “sniffing” data and intercepting
it, storing it on their own servers. This makes the transition between our users
and Pattr’s servers more secure and reliable.

At this point in time, messages do interact with Pattr’s servers, and we scan 
for input like /users, or /w, but we do not and never will store messages. You
can see this for yourself in the source code.

In the near future, Pattr will feature password protection in rooms, which will
allow messages to be encrypted on the client side. This means Pattr would be
completely unable to scan input or store messages, even if we wanted to.

For more information on the state of security on Pattr, email justin@pattr.me.

-The Pattr Team
