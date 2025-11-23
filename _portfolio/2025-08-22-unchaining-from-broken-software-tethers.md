---
creators:
- J. Nathan Matias
date: '2025-08-22'
excerpt: ''
hosts: []
image: 'https://live.staticflickr.com/65535/54737355535_f202caf4f3_b.jpg'
description: How could a group of executives halfway across the world, with a single email, disrupt my community’s mobility, and what could we do about it?
 
tags:
- technology
- policy
- consumer protection
- community
title: "Escaping the chains of tethered products: the Juice Rescue project"
---
Last fall, just around the time I got the news that my neighbor Mark’s cancer treatments were going well, I read an email that transformed my year. The oaks, maples, and hickory trees across New York’s Finger Lakes were just changing from summer green into autumn gold, and I had pulled my wool layers out of the closet. On my way out the door, I often ran into my neighbors Mark and Pat, who planted the apples and plums behind our home a decade earlier and taught me how to prune them.

That’s when I got an email from Enel X Way, an Italian power company, that the software in the boxes that charge our cars would be disconnected in just a few short weeks. I immediately thought of Mark, whose medical care required reliable travel to the nearby city of Syracuse. Across our entire neighborhood, forty homes had exactly the same box, many supported by a New York State electric charging grant. And now all of us were about to have tens of thousands of dollars in critical infrastructure lose functionality \- infrastructure we relied on to get to work, access medical care, and live our daily lives.


<div align="center"><hr style="width:50%; height:2px; background:#ccc;"/></div>

How was it that a group of executives halfway across the world could, with a single email, disrupt a whole community’s lives, and what could we do about it? Over the next ten months, whether I liked it or not, I was about to gain a lesson in infrastructure, law, electronics, and the power of collective action. And this month, as my neighbors and I finally put this problem to rest, I’m relieved to say that we have made ourselves much less dependent on the whims of faraway companies.

This is a story about a Juicebox \- not the waxed paper container of pressed apples with a little straw that you drank in elementary school, but a high voltage electrical device that charges electric cars. First designed for [a Kickstarter campaign](https://en.wikipedia.org/wiki/EMotorWerks) in 2013, this box put home car charging within reach for many people around the world. It plugs into a 50 amp supply like those used for laundry machines and RVs at one end, and into your car on the other. Inside the box is a collection of cables, a relay, and an electronics board. Software inside the board talks to the car, records how much energy was used, and implements safety protocols. It’s a simple piece of tech, and most of the cost of making one is in the cables- thick bundles of copper that convey the power needed to charge a car.

The story of how we freed our chargers from a delinquent company is also a story about community \- both the online community that rallied in collective support for thousands of product owners, and the extraordinary neighbors of the Ecovillage at Ithaca that I call home. 

Here at the Ecovillage, our community of over 240 residents [work together to re-imagine our relationship with the planet and each other](https://www.youtube.com/watch?v=n-uH36w9xg8) through our shared infrastructure. So when we faced an emergency with our chargers, we handled it like we handle every other problem: by working together on a solution.

## The Problem with Products Tethered To Manufacturer Software

How is it that an Italian company could just turn off major functionality of a product that some of our neighbors had purchased nearly a decade ago from American inventors? Juicebox chargers, like many digital products, require users to log in to a website run by the company in order to access all of the features. "Tethered" products like this offer the benefit of ongoing software and security updates. They also allow companies to use and sell your data, and they chain a customers to the company owner for the life of the product. 

<a data-flickr-embed="true" href="https://www.flickr.com/photos/natematias/54738342343/in/dateposted-public/" title="Kia EV6 Plugged in and Charging, Ithaca NY"><img src="https://live.staticflickr.com/65535/54738342343_d29956fdfc_b.jpg" width="1024" height="576" alt="Kia EV6 Plugged in and Charging, Ithaca NY"/></a>

While many owners loved the original "Juicenet" software, owning a tethered product ultimately worked out badly for owners of the Juicebox system. In 2017, the Italian power company Enel X Way bought the company that developed the Juicebox and eventually fired many of the original developers. Over the years, this new company actually removed key features that Juicebox owners relied on, offering product owners notoriously unresponsive tech support. 

As someone who's been an early stage engineer in multiple startups, I understand how this can happen. When companies sell software tethered products, they enter into a relationship with customers who they're stuck with for as long as the product continues to work. With fashion products like a smart watch, the support timeline is kept short by changes in fashion or broken screens. But Juiceboxes have been very reliable, saddling Enel X Way with hundreds of thousands of customers needing ongoing support without any additional revenue. What initially looks like a money-maker probably starts to feel like a ball and chain for companies, especially when hackers find [security vulnerabilities in decade-old products](https://vicone.com/blog/from-pwn2own-automotive-a-stack-based-buffer-overflow-vulnerability-in-juicebox-40-smart-ev-charging-station). The better and more reliable a product is, the less profitable and more risky the tethered product will become.

As software costs from a tethered product rise, managers feel forced to cut the cord to their customers. But what helps companies cut their losses creates a crisis for customers. When Enel X Way threatened on short notice to shut down their servers and leave the North American market, it left hundreds of thousands of US and Canadian owners scrambling to find out what would happen to the system that charged our cars.

## Rescuing Disabled Juiceboxes

What do you do when a part of your community's critical infrastructure is about to shut down and you don't exactly know how that will affect you? Even as the Ecovillage Charge Team discussed our response, we knew we needed to learn from a broader group. With that in mind, I created an online chatroom where people affected by this issue could gather to share information. This community, "[Juice Rescue](https://juice-rescue.org/)" became an essential collective resource for understanding the risk and developing a solution.

<a data-flickr-embed="true" href="https://juice-rescue.org/" title="Screenshot from the Juice Rescue project"><img src="https://live.staticflickr.com/65535/54737239404_b9a7d9bdc7_b.jpg" alt="Screenshot from the Juice Rescue project"/></a>


The community quickly assessed the situation, created a guide for Juicebox owners, and started organizing alternative software and hardware. We also worked with Consumer Reports to [call on the FTC to investigate Enel X](https://advocacy.consumerreports.org/research/consumer-reports-u-s-pirg-and-60-self-reported-owners-of-juicebox-ev-chargers-call-on-the-ftc-to-investigate-enel-x-after-abruptly-discontinuing-sales-and-support-of-its-ev-chargers/). In the short term, the boxes would continue to work, especially after the company kept the servers running in response to public pressure. But what about the long-term?

The Juice-rescue community worked in two directions: a software and hardware solution. The [open source software](https://github.com/JuiceRescue/juicepassproxy), JuicePassProxy, interrupted the charger's network connections to collect data and manage the device even if the company's servers were down. As community members wrestled with our network settings to configure this system, open hardware developers at [OpenEVSE](https://www.openevse.com/) worked on a replacement to the Enel X board. With a replacement, owners could just open the box, screw in a new controller board, and use our chargers without worrying about bankrupt companies.

By early 2025, OpenEVSE had completed the replacement boards ([Juicebox v1](https://store.openevse.com/products/replacement-electronics-for-juicebox-v1-metal-black-and-orange?srsltid=AfmBOop3vGbCx9w0g7VUY4Aou8fCmutHB1sym9qYT0412bcth0ShbZJw), [Juicebox V2](https://store.openevse.com/products/replacement-electronics-for-juicebox-v2-plastic-grey-and-white?srsltid=AfmBOopP8Nhistx44WyX8udAfCYMrePQBtwh13WVvR36r2lX7CN9cpiS))  and started to produce them at large quantities. While a new EV charger would cost us hundreds of dollars and generate a dumpster of waste from cables and parts that were just fine, we could order a replacement board for a fraction of the cost. Across all the chargers in our neighborhood, replacing the boards could save us nearly nine thousand dollars. After getting some legal advice (Many [thanks to the Harvard Cyberlaw Clinic](https://clinic.cyber.harvard.edu/)), we decided to go ahead with the plan.

## A Juicebox Rescue Party

This spring, the Ecovillage charge team held a series of work parties where we gathered neighbors, set up an assembly line, and installed OpenEVSE boards into all our former Juicebox chargers. OpenEVSE has published [helpful guides to replacing the boards](https://openevse.dozuki.com/c/JuiceBox), which were easy enough to follow:

* Take the charger down from the wall  
* Open the box, voiding the worthless warranty  
* Remove the old board and disconnect the wires  
* Screw in the OpenEVSE board, connecting the wires carefully  
* Close the box  
* Test the charger by connecting to it over WIFI and plugging it into a car   
* Re-install it on the wall

We have now been using the chargers all summer without any major issues. 


<a data-flickr-embed="true" href="https://www.flickr.com/photos/natematias/54737296800/in/dateposted-public/" title="Overhauling a Juicebox Charger(1)"><img src="https://live.staticflickr.com/65535/54737296800_69781a9169_b.jpg" alt="Overhauling a Juicebox Charger(1)"/></a>

## Lessons from the Juice Rescue Project

When this project started, I knew about as much about electric vehicle charging as anyone else with an electric car. By the end, I had learned how to safely open and replace electronics hardware. I also learned a lot about the business and policy of charging cars. While I'm still far from an expert, here are some of the lessons I learned from this ordeal:

* **Tethered products cheat consumers out of products we paid for**, from baby's bassinets to laundry machines and car chargers. When companies "brick" their products, it can render products useless or hold consumers hostage. Last September, a group of seventeen organizations urged the Federal Trade Commission to do something about software tethering (see [this article in The Verge](https://www.theverge.com/2024/9/5/24236237/ftc-software-tethering-letter-consumer-reports-ifixit) and [this announcement by Consumer Reports](https://advocacy.consumerreports.org/press_release/ftc-software-tethering/)). In November, the Federal Trade Commission published a report that [89% of "smart" products fail to disclose to consumers how long the product will keep working](https://www.ftc.gov/system/files/ftc_gov/pdf/smart-device-makers-failure-to-provide-software-updates-may-leave-you-smarting.pdf), potentially violating federal laws about disclosing warranties.  
* **Governments should reconsider funding for tethered products** that inevitably create problems for consumers in the future. For example, the New York State Environmental Research and Development Authority (NYSERDA) gives [rebates on EV chargers, up to $1000 \- $3000 per charger](https://www.nyserda.ny.gov/All-Programs/Charge-Ready-NY). Many of these chargers, like the Juicebox, could lose core functionality unexpectedly if the vendor decides to stop supporting them.  
* **Governments can reduce the risks from tethered products**. Policy ideas for addressing this include:  
  * Encourage investment in **open hardware and software vendors**, to enable longer-term maintenance of electronics products. Organizations like the [Open Source Hardware Association](https://oshwa.org/) can explain this far better than me (my Cornell colleague [Wendy Ju](https://tech.cornell.edu/people/wendy-ju/) is on the board).  
  * Compel companies to make contingency plans for the end of life for their software and hardware, including source code and hardware design escrow, so designs don't get accidentally deleted or lost in a messy business situation  
  * Right to repair laws that (a) require companies to make products that are repairable, and (b) give consumers and repair businesses the legal right to repair products when they need maintenance. New York recently [passed the Digital Fair Repair Act](https://www.consumerreports.org/right-to-repair/new-york-right-to-repair-law-digital-fair-repair-act-a8385596436/), which requires manufacturers to make parts, tools, and guides available to everyone. Unfortunately, the law only applies to a few categories of products, and excludes things like appliances. I never got a straight answer on whether the law applies to EV chargers.  
* **People can organize in powerful ways around a crisis**, bringing expertise to bear on hard problems.   
  * The Juice Rescue community organized hundreds of people to collectively support each other during this crisis, and this urgency made it possible to find experts in hardware, software, and EV charging.   
  * At the Ecovillage, our commitment to each other and to our community made it possible to organize collective support.  
  * At the same time, people shouldn't have to organize a global movement every time a company unexpectedly abandons a product.

<a data-flickr-embed="true" href="https://www.flickr.com/photos/natematias/54736931651/in/dateposted-public/" title="Overhauling Juicebox chargers"><img src="https://live.staticflickr.com/65535/54736931651_ca94454cc6_b.jpg" alt="Overhauling Juicebox chargers"/></a>

## Looking forward from the Juicebox Ordeal

Last week, my family and I hosted a neighborhood taco party on a porch looking out over the town of Ithaca and Cayuga Lake. As we served up carnitas, microgreens, fresh salsa, and beans cultivated by the farms in our area, neighbors couldn't resist talking about the EV chargers. This time however, it wasn't an emergency — they were full of ideas for how we could improve and expand our community's support for electric vehicles. 

I was also pleased to see my neighbor Mark. He had just sent a note that the neighborhood pears looked ready to pick, and that we should get moving quickly if we wanted to enjoy them. With the Juicebox problem solved, I was more than happy to oblige with this much tastier emergency.

## Acknowledgments

I am so grateful to everyone who has been conversation partners through the last nine months of this frustrating but ultimately inspiring and educational ordeal. 

This includes the many creative contributors to the [Juice Rescue](https://juice-rescue.org/) project, [Transport Evolved](https://www.transportevolved.com/), the team at Consumer Reports, and the [Harvard Cyberlaw Clinic](https://clinic.cyber.harvard.edu/). Huge credit for this success story goes to Chris and the team at [OpenEVSE](https://openevse.com/about-us.html) who almost immediately realized that there was a need, and who developed the replacement board. I am especially my extraordinary neighbors here at the Ithaca Ecovillage for the collaborative spirit that everyone brought to what was a very real crisis for our community 🍃.

<a data-flickr-embed="true" href="https://www.flickr.com/photos/natematias/54737226264/in/dateposted-public/" title="Electric Charger at the Ithaca Ecovillage"><img src="https://live.staticflickr.com/65535/54737226264_67ae1bf57a_b.jpg" alt="Electric Charger at the Ithaca Ecovillage"/></a>
