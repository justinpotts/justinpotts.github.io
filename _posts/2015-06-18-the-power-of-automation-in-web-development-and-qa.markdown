---
layout: post
title:  "The Power of Automation in Web Development and QA"
date:   2015-06-18
categories: development
---
As many of my readers know, I have a webdev project, [Terml.io](https://terml.io).
Last night, I had my first big launch, besides the first release, and introduced
some new features, like a redesign and Premium Accounts. Since these were major
features that had the potential to bring down the site, or not work properly for
our launch, I compiled a list of features that had to work before we shipped.

#### Visitors
1. Test all pages and make sure the pages display a non-user version
#### Users
2. Test that users can log in
3. Test that users can sign up
#### Sets
4. Test that sets can be created
5. Test that sets can be reviewed
6. Test that sets can be deleted
#### Premium
7. Test that users can sign up for premium
8. Test that users can renew premium subscription
9. Test that premium status stays consistent after logging in/out
10. Test that premium users can create Quizlet sets
11. Test that premium users can download PDF of set

I came up with these items by doing something we call in the QA world, “risk
analysis.” This is going through the features on your site and determining what
can break (terms and conditions), what can break sometimes (non-Latin character
support in definitions), and what can never break (signing in/up, or creating
sets). So for the purpose of this launch, I only focused on what can never
break. This area is also what we usually focus on when we create automated
tests.

To go through these items manually is pretty time-consuming. One of my friends,
who helps out when he can, and I spent at least 30 minutes going through these
items, comparing and discussing results, and fixing bugs. This is where
automation comes into play. Rather than checking to make sure these features
functioned properly after every time we pushed before a release or update, I
could have automatically run automated tests through a continuous integration
(CI) service like Travis, saving a combined total of hours in development time
during Terml.io’s development.

This is precisely why we value automation so much in QA, and even web
development in general. By taking the next step towards continuous deployment,
or at least continuous integration, companies and websites can save so much time
that could’ve been used developing new features.

Tl;Dr: If you aren’t using automation yet, now is the time.

Disclaimer: Don’t let automation take away from the value of manual testing as
well. Manual testing can catch things automation can’t, like design flaws or
more in-depth textbox queries.
