---
id: 474
title: Community Meeting Transcript
date: 2015-09-05T12:36:04+00:00
author: bill
layout: post
guid: http://blog.brightcanopy.com/?p=474
permalink: /2015/09/05/community-meeting-transcript/
categories:
  - Bright Canopy Meetings
  - Events
---
[<img class="aligncenter size-large wp-image-477" src="http://blog.brightcanopy.com/wp-content/uploads/2015/09/Snapshot_001-1024x768.png" alt="Snapshot_001" width="625" height="469" />](http://blog.brightcanopy.com/wp-content/uploads/2015/09/Snapshot_001.png)

Here&#8217;s the transcript from our Community Meeting today. If you have any questions or suggestions that weren&#8217;t addressed, please contact us through support@brightcanopy.com or on Twitter, Facebook or Google+.

[11:05] Chaos (chaos.priestman): Hello, and welcome. We&#8217;re here today talk about this last week and the future of Bright Canopy.
  
[11:05] Chaos (chaos.priestman): We want to answer your questions, but we want to get to everyone, so if you have a question, please IM our Community Coordinator Bethsael Robbiani. We also have some questions sent in by email and we will be answering those too.
  
[11:06] Chaos (chaos.priestman): We will be using text chat and logging nearby chat, so that we can post a transcript to the blog
  
[11:06] Beth (bethsael.robbiani) waves
  
[11:06] Chaos (chaos.priestman): First, I want to give everyone a little bit of context and share where we are and what we know.
  
[11:07] Chaos (chaos.priestman): Bright Canopy started a few months ago as a project to help people get the best out of Second Life and Open Sim without having to buy the latest hardware and eventually to be able to use mobile as well. We built a beta and it worked well and there was alot of interest, so we moved on to pre launch and worked on billing and getting the last bugs ironed out. That also went well, and there was even more interest, so we planned a launch.
  
[11:07] Chaos (chaos.priestman): We did the numbers and with the cost of goods on the back end we had a plan that we believed would break even and even make some money to fund new development and hiring support people.
  
[11:08] Chaos (chaos.priestman): To understand our plan, it’s helpful to know that Bright Canopy uses Frame as a platform for streaming, and, in this case, Frame uses Amazon Elastic Compute Cloud (EC2) g2.2xlarge instances as an important part of the service. We need one per customer/per hour.
  
[11:08] Chaos (chaos.priestman): One instance, that is.
  
[11:08] Chaos (chaos.priestman): Our business model was based on an Amazon Spot instance prices for g2.2xlarge instances remaining below $0.25 as they had since they were introduced. That&#8217;s just the cost of the instances. That doesn&#8217;t include Frame being paid or Bright Canopy being paid or the waste inherent in swapping people on and off those servers (about 1/3 in our observations after launch) or anything else.
  
[11:09] Chaos (chaos.priestman): Beginning the week of August 1st, the price of g2.2xlarge instances spiked, first in Ireland, then in Virginia and California.
  
[11:10] Chaos (chaos.priestman): I&#8217;ll animate this so you can see all of them.
  
[11:11] Chaos (chaos.priestman): What had been $0.12 was now over $1.00 and sometimes almost $8.00. This broke our business model, but it looked like a temporary spike. We decided to continue with the planned launch,
  
[11:11] Chaos (chaos.priestman): We believed the prices would come back down. In the meantime, we moved to on-demand instances at $0.80 and that allowed us to continue.
  
[11:12] Chaos (chaos.priestman): An $0.80 instance price meant we were losing money on every minute of user activity, but we hoped that usage would even out in such a way that we would lose money slowly enough to maintain our course until we could build out a solution that cost less on the back end. In the meantime we also hoped the spot prices would come back down and give us some relief.
  
[11:12] Chaos (chaos.priestman): August 29th, we launched.
  
[11:12] Chaos (chaos.priestman): We had a good look at the usage with more people, and it became clear that we could not sustain the losses. Usage was just not the same as we had seen in Pre Release. We expected a difference, but we didn&#8217;t expect such a huge difference. We agreed to pull the plug and rethink things.
  
[11:13] Chaos (chaos.priestman): Now, as the dust has settled, prices have come back down in California and Virginia, but not in Ireland. And there&#8217;s no guarantee they will remain low. Also, now that we&#8217;ve seen more of people&#8217;s usage patterns we know that even the pre launch prices (similar to this new plan we&#8217;ve posted about) won&#8217;t be profitable. At best we may break-even. It&#8217;s probably a few months out before we could reduce cost enough (by splitting servers) to make it sustainable.
  
[11:14] Chaos (chaos.priestman): Notice I&#8217;ve consistently said sustainable. This has never been about making alot of money. So far, no one but Amazon has made anything at all. Frame has offered a tremendous amount of support because they believe it’s important and could eventually be a sustainable business, and Jerri and I have volunteered our time and invested our savings. We did it because we believed it was important, and we still do.
  
[11:14] Chaos (chaos.priestman): With that in mind, we have worked with Frame on a proposed plan that we would be able to offer to a limited number of people at first. We have not come to an agreement yet on all of the details of that plan. If and when we do, please understand that this is just a stopgap so that the people who most need the service will have an option.
  
[11:14] Chaos (chaos.priestman): This plan will not include any revenue for Bright Canopy or payment for Jerri or myself. The fees will go to pay for infrastructure costs and hopefully some of Frame’s time. We will continue to work and support this effort as volunteers and will still be here for support. We will have to back-off from 24/7 support to answers within 24 hours.
  
[11:15] Chaos (chaos.priestman): I know there’s alot of disappointment, and we all share it. We want this to be easier for everyone, but for now, this is just a small flame that we will have to tend carefully if we want to keep it alive.
  
[11:15] Chaos (chaos.priestman): Now we’ll open up for questions: Please send your questions to Bethsael Robbiani in IM while I answer the first of our questions from email.
  
[11:16] Chaos (chaos.priestman): This one actually came in various forms from several people.
  
[11:16] Chaos (chaos.priestman): &#8220;Doesn&#8217;t having more users make it cheaper for you?&#8221;
  
[11:17] Chaos (chaos.priestman): I understand where this is coming from. We often see volume discounts when we buy things and in a sense it&#8217;s true over the long term. But as I described, that&#8217;s not the case right now. We actually lose a little money on each user until we have a less expensive way of sharing instances.
  
[11:17] Chaos (chaos.priestman): I&#8217;ll answer a question here now and then do another email?
  
[11:18] Beth (bethsael.robbiani): We have a question&#8211;A lot of my time in world is predicable in advance. It tends to be certain times of certain days.
  
[11:19] Beth (bethsael.robbiani): Is there a business model in which a user could buy and pay up front for server time at particular times/days thus getting chaper access to the hardware?
  
[11:19] Beth (bethsael.robbiani): *cheaper
  
[11:20] Chaos (chaos.priestman): That&#8217;s an interesting idea. To make it work we would have to be able to get that time cheaper ourselves or utilize what we have more efficiently. We can look at that, but I&#8217;m not sure I see a way to do it off the top of my head. Thanks for that suggestion. Who was that from?
  
[11:20] Lynxx (lynxxrufus): Me!
  
[11:21] Chaos (chaos.priestman): Thanks, Lynxx
  
[11:21] Chaos (chaos.priestman): OK, another email question:
  
[11:21] Lynxx (lynxxrufus): yvw Chaos
  
[11:21] Beth (bethsael.robbiani): We have another question &#8211; What has the reaction by Linden Lab been to Bright Canopy
  
[11:22] Ⓔⓝⓩⓞ (themaster.enzo): hello all
  
[11:22] Chaos (chaos.priestman): Linden Lab has been very supportive.
  
[11:22] Beth (bethsael.robbiani): Another Question When you are ready
  
[11:23] Chaos (chaos.priestman): We really appreciate the blog post and they have been following BC with interest.
  
[11:23] Ⓔⓝⓩⓞ (themaster.enzo): @
  
[11:23] Chaos (chaos.priestman): OK I&#8217;m email next then that one, Beth, thanks.
  
[11:23] Chaos (chaos.priestman): &#8220;Other services like Kitely have found ways to go to a monthly plan, can&#8217;t you just do what they did?&#8221;
  
[11:24] Chaos (chaos.priestman): I want to explain, that running sims requires different sorts of servers. We use servers that have a GPU card, and special support for streaming.
  
[11:25] Chaos (chaos.priestman): That&#8217;s a relatively rare beast at the moment.
  
[11:25] Chaos (chaos.priestman): But we expect to see other providers stepping up soon, and Amazon is likely to provide more, just based on the demand we&#8217;ve seen.
  
[11:26] Chaos (chaos.priestman): No one has ever pulled this off. We&#8217;re still hoping to be the first to make this work in a sustainable way.
  
[11:26] Chaos (chaos.priestman): OK Next question?
  
[11:26] Beth (bethsael.robbiani): We have several of a similar style, so I am going to paraphrase a bit.
  
[11:27] Beth (bethsael.robbiani): We have questions about the feasibility of using other servers or even our own servers to provide the service at a more affordable rate?
  
[11:28] Beth (bethsael.robbiani): Alternatives to the Spot instances and so on.
  
[11:29] Chaos (chaos.priestman): There aren&#8217;t alot of providers what we need right now. There will be in 2016, I would expect. We could begin buying servers and configuring them and over the long term that might be less expensive, but it&#8217;s a huge upfront capital cost. We don&#8217;t have funding for that, but it is a possibility.
  
[11:30] Chaos (chaos.priestman): Next Question?
  
[11:30] Beth (bethsael.robbiani): Next question &#8211; Is Linden Lab offering any support other than advertising the service?
  
[11:31] Chaos (chaos.priestman): They&#8217;ve been open to talk about other support. We haven&#8217;t talked about anything specific.
  
[11:31] Beth (bethsael.robbiani): I have no other questions in my box at the moment.
  
[11:31] Chaos (chaos.priestman): Anyone else have a question or suggestion?
  
[11:32] Joly John: what server used SL GO ?
  
[11:32] William Palmer (williampalmer): I think it all belonged to them
  
[11:32] Chaos (chaos.priestman): Hi Joly, SLGo built out their own servers, originally for another purpose.
  
[11:32] Beth (bethsael.robbiani): Thank you Joly.
  
[11:33] Joly John: TY
  
[11:33] Beth (bethsael.robbiani): I have a question
  
[11:33] Chaos (chaos.priestman): OK
  
[11:33] Beth (bethsael.robbiani): What is the feasibility of a kickstarter for upfront costs for servers, or would it simply be too prohibitive?
  
[11:34] Chaos (chaos.priestman): That&#8217;s a topic that has come up a couple of times. It&#8217;s not out of the question, but there&#8217;s more than servers. We would want all of the platform that Frame provides, so it would be a discussion about setting up a self-hosted option with Frame I would think.
  
[11:35] Beth (bethsael.robbiani): Another question when you are ready&#8211;
  
[11:35] Chaos (chaos.priestman): OK
  
[11:35] Beth (bethsael.robbiani): I will combine two questions to make it easier. They are similar, but oe goes further
  
[11:36] Beth (bethsael.robbiani) whispers: Do we have an estimate on when we may be accepting new subscribers? Or are we in a holding/wait pattern.
  
[11:37] Chaos (chaos.priestman): Yes, I&#8217;d say a holding pattern is the best way to put it. We mentioned that Monday would be the earliest we could come back up, but we are not ready to do that yet. We want to make sure when we do, we have something that will last.
  
[11:38] Beth (bethsael.robbiani): Also, asking for clarification from &#8220;Other Support&#8221; fro SL&#8211;are we talking financial support? Wouldn&#8217;t it be to their financial advantage to build the customer base or are they more into the new platform now?
  
[11:38] Chaos (chaos.priestman): I can&#8217;t speak for Linden Lab.
  
[11:39] Chaos (chaos.priestman): But I can say our core mission is to bring as many people to this and opensim worlds as we can.
  
[11:39] Beth (bethsael.robbiani): My box is now empty once again. Last call or IM questions, please.
  
[11:39] Beth (bethsael.robbiani): \*for\* IM questions.
  
[11:40] Chaos (chaos.priestman): OK Last call?
  
[11:40] Chaos (chaos.priestman): You can always contact us through support@brightcanopy.com if you have something you think of later.
  
[11:40] Chaos (chaos.priestman): Oh Beth has one.
  
[11:41] Beth (bethsael.robbiani): Question: Do LL realise that services like this are the way forward not everyone can afford to upgrade on a regular basis . Soon they will have a platform that is unusable by the majority&#8221;
  
[11:42] Chaos (chaos.priestman): Or rather has received one.
  
[11:42] Rich Haefeli: dont know that that has ever been a concern to LL or any game makers for that matter..
  
[11:42] Rich Haefeli: sorry .. lol that was for IM
  
[11:43] Chaos (chaos.priestman): I can&#8217;t speak for LL, as I said. But I think everyone understands how important this service is.
  
[11:43] laben Core is offline.
  
[11:43] Chaos (chaos.priestman): We just have to find a way to offer it that will stand on it&#8217;s own two feet.
  
[11:43] Joly John: maybe for SL 2.0 ^^
  
[11:43] Paul (columbus.highmist): we hope you get it there, you all seem like a passionate and great bunch of people
  
[11:43] Paul (columbus.highmist): and it&#8217;s a great idea
  
[11:44] Chaos (chaos.priestman): Thank you Paul. We&#8217;ll never fail for lack of effort, that I can promise.
  
[11:44] Tardesh: Yes. And thanks for the info, good luck, and remember it´s important to sleep enough to work well, nvm how important and urgent everything seems :) CU.
  
[11:44] Chaos (chaos.priestman): Thank you all for coming.
  
[11:44] Paul (columbus.highmist): thank you for inviting us.
  
[11:45] Rich Haefeli: many thanks..
  
[11:45] Chaos (chaos.priestman): Thank you Tardesh, you are very wise..
  
[11:45] Chaos (chaos.priestman) smiles
  
[11:45] Joly John: TY for what you do for us
  
[11:45] Beth (bethsael.robbiani): Thank you everyone.
  
[11:45] ThinkererSelby Evans (thinkerer.melville): Thank you for the useful Information/meeting
  
[11:45] Ingrid Blackheart: thank you, very kind
  
[11:45] Ingrid Blackheart: thank you, very kind
  
[11:45] Chaos (chaos.priestman): We will continue to provide updates through our twitter [@BrightCanopyApp](https://twitter.com/BrightCanopyApp) and through the Bright Canopy group

Here are the slides from the meeting:

[<img class="aligncenter size-large wp-image-478" src="http://blog.brightcanopy.com/wp-content/uploads/2015/09/California-1024x560.png" alt="California" width="625" height="342" />](http://blog.brightcanopy.com/wp-content/uploads/2015/09/California.png) [<img class="aligncenter size-large wp-image-479" src="http://blog.brightcanopy.com/wp-content/uploads/2015/09/Ireland-1024x560.png" alt="Ireland" width="625" height="342" />](http://blog.brightcanopy.com/wp-content/uploads/2015/09/Ireland.png)

[<img class="aligncenter size-large wp-image-480" src="http://blog.brightcanopy.com/wp-content/uploads/2015/09/Virginia-1024x561.png" alt="Virginia" width="625" height="342" />](http://blog.brightcanopy.com/wp-content/uploads/2015/09/Virginia.png)

&nbsp;