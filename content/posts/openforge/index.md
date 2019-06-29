---
title: "This Exists in India: Openforge"
date: 2019-06-27T15:57:20+05:30
tags: ["opensource", "india"]
draft: false
---

I had a random thought – what if the Indian Government open-sourced their software? A quick search showed me that they actually do, to some extent.
In fact they have a whole platform that hosts repositories for a whole lot of... you'll see.

### Openforge

Around 2015 the Ministry of Electronics and IT (MeitY)[^1] made a bunch of policies that provided a framework for government source code in repositories and stuff.

Fast forward to 2017 and the government brought in Amit Ranjan as the architect of Openforge. Interestingly, Amit Ranjan comes the startup world and was the co-founder and COO of SlideShare.
No wonder the site looks prettier than what you'd typically expect from the Indian Government.

{{< figure src="full_site.jpg" alt="Full Site" >}}

So I obviously decided to explore and see how it's coming along.

### Closedforge

One of the first few things I did was register an account on their portal, and jumped right into the projects hosted on it. Navigation was decent, although most projects didn't bother categorising themselves properly, which limits the usefulness of having all these categories in the first place.

{{< figure src="categs.png" alt="Too much not specified" caption="Star of the show: Not Specified" >}}

So I instead sorted by popularity. Surely that would give a good picture of what the Openforge community is like, right?

If that's the case it's one sad scene only.

The projects itself seem pretty interesting. The Government's e-Marketplace is currently the most popular project there. It's what the ministries are apparently using as a marketplace for procurement of goods. So I click on it. Time to see that glorious, augustine source code.

The git dashboard is pretty complete, especially for a kid like me. You can see the project tree, commits, diffs and logs. A reference to the documentation shows that if a project requires it, you can setup dashboards on the project page for Continuous Integration, Mailing Lists, Wikis, Agile and a whole other bunch of stuff that I know nothing about. It has support for trackers and a REST API too (Though the docs don't make it clear enough as to what it actually does).

Oh, and it supports SVN too.

There is no syntax highlighting yet though. Not a deal breaker, in my opinion.

After that I hopped on to the next project, called "Delhi Police-onetouch". It said I need to log in to view the code contents.

{{< figure src="loginplis.png" alt="Login Prompt" >}}

Alrighty then I'll... oh wait. I am already logged in!

That's strange. The project's privacy settings are set to "public", so that's no issue. Either Openforge doesn't straight up do its job well, or there is a bug and the message is supposed to be something else.

With no way to see that, I decided to move on to the next one in the list.

Same issue. Oh well. Next one? Yep, still happening.

I got till the tenth project listed there before I gave up. So much for the *Open* in Openforge[^2].

Also in the projects that did work, the website wasn't nearly as snappy in fetching the code as I'd like.

### Community

The homepage says that students, academia, startups, Open Source Devs and Corporations are free to participate in the platform. The caveat being all the registered projects have to have some overlap with governance or civic areas. So all registered projects have to pass this filter in order to be hosted on Openforge. And members who don't work for any government department cannot make private projects.

According to the FAQ's the reason Openforge was made even though GitHub and SourceForge exist is because of this government application specialisation[^3] and the fact that many government employees face restrictions on putting their data on foreign servers.

Okay then.

Let's see what Real People on Openforge are saying. Onto the forums!

{{< figure src="forums.png" alt="Forums page" caption="These are all the messages ever posted on these forums" >}}

Here are some assorted snippets of interesting conversations:

-------------------------------------------------------------------------------

#### 1. The blockchainer

By: Abhishek Upperwal (a.upperwal)  
Problems you face while filing an FIR  
21/10/2018 at 10:00 AM

I look forward to compile a list of issues people face while filing an FIR. We plan to design a decentralised solution (based on blockchains) for complaint redressal system which can register a complaint which is tamper proof and the entire life cycle of the complaint can be committed and tracked on the same chain. This will bring in more transparency and build a tamper proof system.

I am aware of privacy related issues and tackle them as we go.

To kickstart the discussion here are few pain points I can think of.

1. Jurisdiction issue: People don't know where to go to file a complaint. Jurisdiction allocated to each police station is weird. Footpath to some police station and main road to some other station, yeah that's true.

2. No nation wide complaint filing and tracking: Although policing is a state matter but still we can have a nation wide complaint filing and tracking system. Each complaint can then be redirected to the station responsible.

You are welcome to add to this list. Even discuss, what you want to see in such a system.

Thanks

-------------------------------------------------------------------------------

#### 2. The Blockchainer: Aadhar and UPI edition

By: Jerric Lyns John (jerriclynsjohn)  
GST on blockchain  
31/08/2017 at 11:05 AM

We are starting a working group to present to the govt blockchain based implementation using AADHAR and UPI. The intention is to make a public document and code base left out for innovation from across the world. Intention is to streamline the process, which can be automated to a super great extend. 

-------------------------------------------------------------------------------

#### 3. Will my efforts materialise?
By: Gopal Krishan Aggarwal (gopalkriagg)  
Need help in starting  
17/03/2018 at 16:03 PM  
Hi! I am a software engineer really interested in contributing to India's development. This looks like a nice place for that but I am not sure how my efforts will actually materialise. For example, I would like to know, from where are the projects available on OpenForge coming? Are they real government projects? If I contribute in any of them, will my time and effort actually impact people's life?

By: Amit Savant (amitsavant)  
RE: Need help in starting  
03/04/2018 at 10:59 AM  
Dear Mr. Gopal, thank you very much for your interest in OpenForge and the willingness to contribute to the eGovernance projects. The projects on OpenForge are mostly contributed by Government departments. But private organisations, academic institutions and communities can also host projects on OpenForge as long as the projects are related to eGovernance domains and are open source. We are continuously working on bringing in an increasing number of projects on OpenForge. Any contribution to these projects will help to make eGovernance projects better.  
- OpenForge Team

(*He didn't really answer the main question* :/)

-------------------------------------------------------------------------------

#### 4. I'm appalled, thx

By: Sunil Choudhary (suchoudh)  
This forum needs a moderator.  
06/01/2019 at 01:29 AM

Guys  
We need a moderator.  
I am apalled to see the kind of spam in this forum.

Can you make me the moderator for the forums untill we have someone formally taking up the role.

thx  
Sunil Choudhary 

-------------------------------------------------------------------------------

### Conclusion time

I like that the government is actually trying to push Open Source. The execution of Openforge has a long way to go.

Contributing to Open Source can be quite daunting, and Openforge did not look welcoming at all to a student like me. The community still seems to be in its early stages and somewhat hushed and insular.

Maybe I'll check back in a few years.

This wasn't a review but Openforge gets a light 5/10 for me.

[^1]: Not sure where that 'Y' came from ¯\\\_(ツ)\_/¯

[^2]: I did find a few more random projects where the code was actually viewable, but the vast majority of the popular ones seem to have this issue. I did notice that the all the projects having these issues seem to be from this one specific pool of contributors. Can't explain it though.

[^3]: Looks like the Indian Government has no interest in using [this](https://government.github.com/).
