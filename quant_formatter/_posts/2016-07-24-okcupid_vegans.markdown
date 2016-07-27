---
layout: post
title:  "Vegans at OKCupid"
date:   2016-07-24
categories: 
---

While searching for a interesting dataset to play around with, I came across 
<a href="https://github.com/rudeboybert/JSE_OkCupid">this</a>.

X and Y (and OKCupid) were nice enough to open source their dataset of OKCupid profiles (scraped from San Francisco, over the period of a day).

While 

Eventually, I think it would be really neat to apply NLP to the profile essays and see what common topic pop up, but before that, I decided to do some simple analysis on the difference between Vegans and Non-vegans, according to OKCupid profiles.

I thought it'd be fun to do some analysis on the factors that differentiate Vegans and Non-Vegans (besides the obvious).

<br>
<small>Note: The data compiled from exclusively San Francisco profiles, so potentially non-San Fran vegans have a completely different lifestyle</small>
<br>

One of the categories you can fill out on the your OKCupid profile your dietary lifestyle.<br>
The diet options are:

`strictly anything`,`mostly other`,`anything`,`vegetarian`,`mostly anything`,`mostly vegetarian`,`strictly vegan`,`strictly vegetarian`,`mostly vegan`,`strictly other`,`mostly halal`,`vegan`,`mostly kosher`,`strictly halal`,`halal`,`strictly kosher`,`kosher`,`other`

To separate between Vegans and Non-Vegans, I simply categorized a profile as vegan if it's diet was either `vegan`, `mostly vegan`, or `strictly vegan`

OKCupid also lets you label your alcohol and drug habits as well, so let's see if there is a difference for these factors between Vegans and Non-Vegans.

![My helpful screenshot](/assets/vegan_drinking.png)

We can see that Vegans have much less alcoholic tendencies than their Non-Vegan friends, since they're less likely to drink socially and more likely to never drink. 
This isn't too unexpected, since most beer and wine are made with animal products.
(Technically vegans can drink distilled alcohol though, like whiskey and vodka.)


But the next plot illustrates something pretty interesting -- Vegans are more likely than Non-Vegans to do drugs. 


![My helpful screenshot](/assets/vegan_drug.png)

In fact, conditioning on a user being vegan, they are 1.7 times more likely to "sometimes" do drugs. 

<br>

Breaking out the plot by vegan type, it looks like all three vegan types have  similar distributions (though the "Strictly" vegans are less likely to do drugs.)

![My helpful screenshot](/assets/vegan_drug_type.png)



So even though they don't drink, I guess some of them still do find ways to have chemically-enhanced fun.

