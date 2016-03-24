---
layout: post
title:  "I Tried Firefox OS for a (Half) Day. Here's What Happened."
date:   2015-12-09
categories: mozilla
---
I am honored to be part of the Foxfooding program, by Mozilla. This is a program
that allows employees and contributors to test drive a Firefox OS device. The
catch is that you have to use the device daily. Now, it doesn’t say you have to
use it as your primary device with SIM card and the works, but I decided to be
adventurous, and given I wanted to work closely with the Firefox OS team next
summer, I decided why not.

So the other night I transferred my SIM card and four contacts I’d need for the
day over to my FxOS device.And so it began. I loaded it up with apps and some
cool tools, and experimented with the NFC reader and my Disney MagicBand,
dreaming of how I could turn my room at home into the coolest connected-device
center in the world.

I woke up this morning to the alarm of my Xperia. Cool. First actual use, check.
I went on throughout the morning, texting some co-workers and people I knew,
browsing the web, and adding events to my schedule for the day.

I decided I wanted to experiment with the developer tools on the device (they’re
quite interesting), so I enabled developer mode.

> This will perform a factory reset your device. Are you sure?

Ugh, okay. I can re-download everything. So I did, and I walked over to the
conference center, adding my four contacts, and loading apps and cool tools.

Now, I’ve been meaning to get more into the Firefox OS QA side of things.
Running tests on my phone and adding to the test coverage as well. I have a
Flame device (one of the most popular FxOS testing + development phones), and
I’ve done a little bit on that, so I decided I’d give it a whirl on my new one.

A little bit of background so you know the irony of the events that will follow.
To run these tests, there’s a risk acknowledgement you have to, well, acknowledge.
It basically says, we’re not responsible for a loss of data or issues that may
occur on your device. Acknowledging this risk takes a little bit of work, setting
a variable in a config file. As if that wasn’t enough, there’s then a warning that
appears and won’t run the tests for 30 seconds while it let’s you read the risks
associated with what you’re about to do. So, you modify another variable in the
config file.

You go through a lot of work acknowledging that what you’re about to do is
potentially dangerous. And it is. It resets your device to a factory reset and
you lose all contacts, photos, or items you’ve saved on the device (not sure
about the SD card).

“Wait,” you say, realizing I had spent all last night setting it up, downloading
apps, and adding contacts. “It’s going to delete everything?” Yes. “And you knew
this would happen?” Well, yes.

You see, in my excitement about getting the tests up and running after trudging
through errors I had forgotten about the implications running the tests would
have on my phone. And yes. I lost everything. Nothing was really important though,
it would all just be a pain to set back up again. And since I wanted to experiment
a lot with the development side of the device, I felt it was too risky to use as
my primary phone.

I’m still going to use the device daily. It’s my obligation as a contributor and
Foxfood Community Member. But I think I like my iPhone. After all, I didn’t spend
$350 to turn my iPhone into a beautifully designed brick.

So I ejected the SIM card, dug out my iPhone, and here I am. Back where I started.
