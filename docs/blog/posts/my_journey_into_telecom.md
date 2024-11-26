---
draft: false
date: 2024-11-23
slug: my-journey-into-telecom
categories:
  - ICT
---

# My Journey into Telecom

![](/assets/images/my_journey_into_telecom.png){ width="800" }

!!! note

    Originally published on March 23, 2023 on Medium, now updated and hosted here.

My name is Eron Lloyd, and I’ve been working in the telecommunications industry for seven years. When I first started in 2016, I entered as a business analyst while working on my Master’s degree in data science. I had many years of experience in the information technology field, and assumed telecommunications would be a straightforward lateral move.

It wasn’t. I entered into what felt like a new realm. Sure, there were  switches, servers, and many other familiar layers, but it wasn’t a typical enterprise environment. ILEC? CLEC? CLLI codes? Tariffs? Public Utility Commission? Working for a service provider is definitely a different world, and I quickly realized I had a lot to learn and needed to learn it quick.

<!-- more -->

My role quickly expanded into a generalist in a traditional IT capacity, migrating legacy Windows servers to virtualized Linux servers, upgrading mail and DNS services, establishing operational and billing support systems (OSS/BSS), and trying to fit everything into databases. More of a system administrator than network engineer, I started cramming on the networking side to wrap my head around VLANs, subnetting, and routing protocols. Within a year, I was running the IT department.

I wasn’t directly responsible for managing the network, but as the department head, I needed to understand how everything worked and how to at least support my team in their jobs. I listened to every [Packet Pushers](https://www.packetpushers.net/) podcast I thought I could learn from as I commuted to and from work. To fill the gaps in my knowledge, I grabbed what was most commonly recommended, [CompTIA’s Network+](https://www.comptia.org/certifications/network) and [Cisco’s CCNA](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna.html) certification guides, and though I would have everything covered. I 
found Network+ to be broad, which was very helpful, but the training material on it I found sometimes lacked practical detail. CCNA was nearly the opposite, but was also too vendor-specific and I didn’t have Cisco gear to practice on.

Next came all the challenges of connecting customers (or “subs,” short for subscribers, as they’re more commonly called in the service provider world). CPEs? Double NAT? Wi-Fi troubleshooting? I finally grasped IPv4 and subnetting, and I realized that we’d be exhausting our public IPv4 address space and need to implement dual-stack address planning. IPv6?! All the documentation I’d studied was primarily in IPv4, including my CompTIA+ and CCNA books! Back into the rabbit hole I went.

Around that time we were preparing to roll out a new broadband service, based on gigabit passive optical network (GPON) technology, which wasn’t covered in either of my study materials. OLTs? ONTs? PLC splitters?! Another huge knowledge gap opened up, and I was stuck digging through 
literally thousands of pages of vendor material, then searching online to piece together the fundamentals. None of this was in either the Network+ or CCNA material. Fortunately I discovered [Light Brigade’s training material for the Fiber Broadband Association’s Certified Fiber to the Home Professional (CFHP) program](https://www.fiberbroadband.org/page/cfhp-and-service-provider-network-certification), and it finally all made sense.

I was beginning to feel like everything was accounted for. We had an IPAM/DCIM system for our data center, modern firewalling to protect the network, subscribers were getting service and our billing system was allowing them to pay, and I just wrapped my head around how many IPv6 addresses we had in our first /32 allocation from ARIN.

All of this was non-trivial; there were challenges at every level, and experience was hard-earned through trial and error. Understanding it all, however, made it actually manageable, and I thought to myself, “I think I finally know this, and I can do this.” Countless hours studying, talking with and learning from my team, reading industry news and magazines, and constantly working to improve upon every mistake we encountered gave way to a rewarding feeling of personal achievement.

“Hmm, I guess I’m beginning to ‘get’ telecom,” I thought as I stood deep inside the rabbit hole, feeling proud as I peered up at the entrance (or further down the learning curve?). I finally did it. I conceptually and officially carved out my domain in the company, which started out in my mind as the “IT department,” but more accurately became what’s called the “Central Office,” or “CO” for short. But there was other side of equation of telecom operations that I still did not understand: the 
“Outside Plant,” or “OSP” for short.

For my first year in telecom, OSP was just another department in the company, and my interactions were limited to a few key aspects where my team and their team had to coordinate. This included testing and connecting new customer circuits and troubleshooting when something went wrong. For the most part, both sides quickly tried to determine if it was a CO or OSP problem, and hand it off accordingly.

It wasn’t long after that, however, that I began to realize that the line between these two departments was not as clear as the “demarc” delineating responsibility between the customer and service provider. For instance, OSP oversaw the installation technicians that ran the cabling and set up the customer premises equipment (CPE) that brought service to our subscribers. When something went wrong with the CPE, and the fiber connection wasn’t the issue, who’s problem was it?

The general rule was that if it plugged in, and wasn’t a power tool or specialized OSP equipment, it became CO’s responsibility. For CPE, this was especially true when it turned out to be a bug in the firmware or provisioning error. When a service call was necessary to correct the issue, coordination was harder to control. “CO doesn’t train and manage the technicians,” I thought, “but we’re dependent on them as the front-line of our network. Our work is more interrelated than I 
realized.”

This became further ingrained when we had to rethink our OSP deployment to meet demand for our services. Until then, OSP relied on a combination of legacy documentation, paper and PDF-based CAD drawings, and Google Earth for network planning. Knowing this, as well as how difficult 
managing this information would be as we scaled, I stepped in and implemented a geographic information system (GIS) solution for OSP.

In order to model the geodatabase that would store all the former KMZ files and newly digitized records, I needed to better understand the terms and concepts of OSP. We needed records for poles, attachments, conduit, cables, hand holes, and many other individual elements. I identified several dozen common types of hardware just for attachments, and struggled to determine the official names for these items. I learned a lot, as usual, digging in vendor materials and websites I found while searching online, but it was still all very abstract, and nothing seemed authoritative. For the most part, I was building data models.

Several months later, however, it all became very real for me. In the Fall of 2017, a dispute with a pole owner we had extensive facilities attached to turned into a lawsuit, and subsequent personnel changes left the position overseeing OSP vacant. I was asked by my boss to temporarily take over OSP operations and assist with lawsuit preparations, and my time on OSP went into overdrive. Joint use agreements, the National Electrical Safety Code (NESC), and telecommunications regulatory law consumed most my time, but I still had to deal with daily work of construction, installation, and outage restorations.

I was fortunate to have already developed the company’s GIS, which became instrumental in auditing and documenting the network. I spent weeks in the field with my team examining alleged safety and authorization issues, to the point I couldn’t stop looking at poles anywhere I went. J-hook? Through bolt? ADSS cable? Mid-span clearance? Worker safety zone? I had to learn them all, and I accumulated many valuable resources along the way, especially from [Building Industry Consulting Service International (BICSI)](https://www.bicsi.org/) and the [Fiber Optics Association (FOA)](https://www.foa.org/).

I got so absorbed in OSP that I wrote my graduate thesis on the topic of [Utility Pole Measurements and Feature Analysis Using Computer Vision and Photogrammetry,](https://gitlab.com/eronlloyd/polevision/-/raw/master/reports/Eron%20Lloyd--Final%20Report.pdf) which blended OSP with data science disciplines. I learned a lot through my research, which only just scratched the surface, and I look forward to picking up where I left off there.

After completing my Master’s degree in Data Science in the Summer of 2018, I was able to focus more time and energy into my OSP studies. Our company became a [FOA Corporate Member](https://foa.org/corporate.html),
 which gave us access to resources and material discounts enough to start an in-house training program for our technicians to attain the [CFOT](https://foa.org/cfot.htm) designation. These are a great starting point for technicians and network engineers in the fiber industry.

After setting that up and becoming comfortable enough with the material, I decided to join BICSI as a member and dedicate my time to studying the [OSP Design Reference Manual](https://www.bicsi.org/education-certification/education-@-bicsi-learning-academy/technical-publications/outside-plant-design). After reading that (which took several months!), I felt like I finally grasped OSP, as well, and was on the right track. I followed up with attending the live [OSP102: Applied Outside Plant Design](https://www.bicsi.org/education-certification/education-@-bicsi-learning-academy/courses/face-to-face/osp102) course, which was fantastic (thanks Mark and Craig!). Earlier this year, I sat for the BICSI OSP exam, and earned my first official industry certification.

Fast forward to today, and looking back on all the conceptual studies and real-world projects I’ve completed, I can proudly say I’m a telecom craftsman, someone skilled in what I do. That doesn’t mean I’m an expert, by any means. Like with my Master’s degree, I now simply know what I don’t really know, and I know what I really need to keep learning.

At this point in my journey, my goal is to share as much as I can with new craftspeople, and encourage other seasoned craftspeople share their stories, as well. I view it as learning by teaching, you could say. Telecommunications is a great industry to be in, during a time when our skills and abilities are not only necessary, but essential to fueling the future in a connected World. Let’s craft it together.
