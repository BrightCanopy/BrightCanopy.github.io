---
id: 441
title: Bad Weather
date: 2015-08-08T09:40:16+00:00
author: bill
layout: post
guid: http://blog.brightcanopy.com/?p=441
permalink: /2015/08/08/bad-weather/
categories:
  - General
---
<div id="attachment_443" style="width: 635px" class="wp-caption aligncenter">
  <a href="http://blog.brightcanopy.com/wp-content/uploads/2015/08/452392668_eacbeb8065_o.jpg"><img class="wp-image-443 size-large" src="http://blog.brightcanopy.com/wp-content/uploads/2015/08/452392668_eacbeb8065_o-1024x677.jpg" alt="Tornado" width="625" height="413" /></a>
  
  <p class="wp-caption-text">
    Credit: OAR/ERL/National Severe Storms Laboratory (NSSL)
  </p>
</div>

My great grandparents were farmers.  Farmers work long hard hours to plant a field that may burn up in the sun, drown in a flood, or wither due to disease and pests. A good and lucky farmer, just often enough, yields a crop that pays the bills. Regardless, every year, they go back and do it all over again.

These last few days, I&#8217;ve had just a taste of what it must be like to be a farmer, living at the whim of the weather. As you may know, Bright Canopy is ultimately hosted on Amazon&#8217;s Elastic Compute Cloud. There are many kinds of servers there, we favor one known as &#8220;g2.2xlarge&#8221; because it has this really juicy <a href="http://www.nvidia.com/content/grid/pdf/GRID_K2_BD-06580-001_v02.pdf" target="_blank">Nvidia Grid card</a>.

You can buy time on these servers three different ways, on demand, reserved or spot. On demand is pricey, but you get an instance right now. Reserved is a little cheaper but you have to sign-up to use it for a set length of time. With spot, one sets a bid, and receives an instance if the bid is high enough. Think of it like an auction. Normally spot prices should be lower than the on demand price. In eBay terms, why bid up the price if you can just &#8220;buy now&#8221; at a lower price?

As an experiment we&#8217;ve been using spot instances in pre release exclusively. Using this approach, we&#8217;ve enjoyed very good prices on the back-end, allowing us to offer a pre-release at $0.013/minute or about $0.78/hr. And the prices on our back end had been very stable historically.

As August 1st rolled around we started to see some very  unusual fluctuations.

<div id="attachment_445" style="width: 635px" class="wp-caption aligncenter">
  <a href="http://blog.brightcanopy.com/wp-content/uploads/2015/08/california-spot-prices.png"><img class="wp-image-445 size-large" src="http://blog.brightcanopy.com/wp-content/uploads/2015/08/california-spot-prices-1024x771.png" alt="California spot price chart." width="625" height="471" /></a>
  
  <p class="wp-caption-text">
    California spot prices up 500%
  </p>
</div>

A short price spike doesn&#8217;t effect us too much, but these were long periods with prices higher than we had seen before.

<div id="attachment_446" style="width: 635px" class="wp-caption alignnone">
  <a href="http://blog.brightcanopy.com/wp-content/uploads/2015/08/dublin-spot-prices.png"><img class="wp-image-446 size-large" src="http://blog.brightcanopy.com/wp-content/uploads/2015/08/dublin-spot-prices-1024x766.png" alt="Dublin spot price chart." width="625" height="468" /></a>
  
  <p class="wp-caption-text">
    Dublin spot prices up 1000%
  </p>
</div>

Notice those $4.00 spikes! It&#8217;s interesting to note that someone out there right now is paying $1.10 for a spot instance when they could get an on demand <a href="http://aws.amazon.com/ec2/pricing/" target="_blank">instance at $0.76</a>.

It&#8217;s hard to say what might be going on here. It could be someone or several someone&#8217;s running a render farm for animation. It could be banks running financial simulations using the GPUs. It could be a runaway bot mining bitcoin, but someone is willing to pay alot of money for g2.2xlarge spot instances this month. Likely its a mix of things.

The good news is that these prices will probably give Amazon an incentive to increase the size of the farm over the long term and drop prices back down. In the short term, being a new phenomenon, these spikes may not last long.

Regardless of what happens, we are looking at changing our mix of instances to handle these kinds of fluctuations better. I know it has been frustrating dealing with the rolling outage in pre release, but we plan to have a much more robust setup when we launch. The important thing right now, is that we want to share exactly what we know, what we&#8217;re doing, and what we&#8217;re seeing. We are all in this together, you and I. We all want people to have access to the best of their virtual world at an affordable price, and we are committed to making that happen.

We will be providing more updates soon, and some long awaited, good news.

&nbsp;