---
draft: false
date: 2024-11-23
slug: bicsi-ospdrm-resource-review
categories:
    - ICT
---

# Resource Review: BICSI Outside Plant Design Reference Manual (OSPDRM)

![](/assets/images/bicsi_ospdrm_resource_review.png){ width="800" }

!!! note

    Originally published on October 2, 2022 on Medium, now updated and hosted here.

## Introduction

In the early years of [my journey into telecom](my_journey_into_telecom.md), understanding the outside plant (OSP) was one of the most time-consuming things to learn. This was primarily due to the relatively obscure nature of the trade, compared to the more common topics of inside plant (ISP)/premises cabling and what we commonly call network engineering. These other disciplines each have a wealth of books, training material, and overall online content, so it was much easier to get started.

I was somewhat aware of BICSI in 2018, and familiar with the RCDD certification, but somehow I overlooked their OSP offerings for the first two years of my self-study efforts. When I finally looked into it, however, I realized this content could hold the key to my development and I dove in from there. You can read more about my overall [BICSI OSP Designer certification review here](https://blog.telecomcraft.com/bicsi-outside-plant-osp-designer-certification-review-965c3cd3d03d).

The focus of this resource review, however, is to drill down into the main material for the BICSI OSP Designer curriculum: the [BICSI Outside Plant Design Reference Manual, or OSPDRM](https://www.bicsi.org/education-certification/education-@-bicsi-learning-academy/technical-publications/outside-plant-design). In this review I’m going to take an in-depth look at what it is, where you can get it, what makes this a great resource but also where it falls short, and whether or not I recommend it.

For full disclosure, while I am a dues-paying BICSI member and certification holder, this review is completely independent and not affiliated with or sponsored by BICSI in any way—it’s just my honest review. If I ever do sponsored promotional content, you’ll be told upfront.

<!-- more -->

## What is the BICSI OSPDRM?

According to a [2007 article in the Cabling Installation and Maintenance magazine](https://www.cablinginstall.com/home/article/16480897/bicsi-releases-updated-osp-design-manual), the BICSI OSPDRM started out in 1999 as the *Customer-owned Outside Plant Design Manual*, to support “individuals who design, inspect or maintain the outside plant (OSP) infrastructures in a campus environment.” Apparently there was an RCDD/OSP Specialist credential at that time that was being developed in conjunction with this manual, but has since split off completely as the OSP credential.

By 2007, when the fourth edition of the manual was released, it had already evolved into a more generalized OSP reference for both campus networks on private land and regional infrastructure in the public right-of-way (ROW). Now in it’s sixth edition, released in 2018, the BICSI OSPDRM is used internationally as a definitive reference for outside plant design.

In the OSPDRM, “BICSI defines OSP as the telecommunications infrastructure that is designed and installed externally to buildings and typically routed into an entrance facility.” This includes both short haul and long haul networks, with plant “cabling” including “copper, optical fiber, wireless, or coaxial” for short haul networks and “optical fiber, wireless, or satellite provisioning” for long haul networks.

BICSI further defines OSP designers as those “responsible for designing the interbuilding cabling and entrance facility (EF) infrastructure and the termination of the OSP cabling.” To perform these responsibilities, designers are expected to be competent in the following:

- Pathways and spaces
- Cabling (cable and connecting hardware)
- Bonding and grounding (earthing)
- Right-of-way (R/W)
- System documentation
- Applicable codes and standards

Overall, the OSPDRM covers these competencies well. Spanning 959 pages in length, it certainly is comprehensive in scope on these topics. The chapters included cover:

1. Introduction to Outside Plant
2. Cable and Connector Types
3. Cabling Topologies
4. Pathways and Spaces
5. Splicing Hardware
6. Bonding and Grounding (Earthing) and Electrical Protection
7. Right-of-Way
8. Project Design
9. Maintenance and Restoration
10. Other Technologies

and it includes appendices on

- Codes, Standards, Regulations, and Organizations
- Legal Considerations
- Cement and Concrete Applications
- Balanced Twisted-Pair Splice Closure Configuration

as well as a glossary, bibliography, and index.

## Where Can You Get It?

The BICSI OSPDRM is [available from BICSI’s website](https://www.bicsi.org/education-certification/education-@-bicsi-learning-academy/technical-publications/outside-plant-design). As of this article's publishing, the digital-only version retails for $255 for BICSI members and $300 for non-members. You can order a hard copy or digital and hard copy bundle as well.

I originally ordered the bundle, because as much as I appreciate some the advantages of ebooks, I still love having hard copies of my most essential reading material, as you can see behind me. But after working with the 959 page binder for several days, I decided to break it down into chunks within multiple, more manageable-sized binders.

The digital version comes as a web-based ebook. BICSI’s digital publications are actually pretty usable, including full text searching, offline access, built-in highlighting and notes, plus you can access it from anywhere. I’m fortunate enough right now to work from home quite a lot, but when I’m in the office or even the field I still have access to this reference.

So while I love a good hard copy book, I’ve found myself using the digital publications more often for the convenience and, quite honestly, because many of the hard copy binders are just not easily accessible. If you have the [Telecommunications Distribution Methods Manual](https://www.bicsi.org/education-certification/education-@-bicsi-learning-academy/technical-publications/telecommunications-distribution-methods-manual), you’ll know what I’m talking about.

BICSI publications will be updated from time to time in an errata document, but there are none for the OSPDRM at the time of this article. Because of the speed of changes in our industry, and this manual already being four years old, there are some areas where it will begin to show its age. I’ll cover some of those areas later in the article.

## Where Does This Resource Excel and Fall Short?

As expected, each chapter offers an informative overview of the topic, but like anything, some areas are better covered than others. To help you determine whether this resource is worth using, I’ll give a usually quick summary of each, adding some commentary where it excels or falls short, and mention other resources that might fill the gaps.

Chapter 1, Introduction to Outside Plant, provides a brief but solid outline of what OSP is and what is involved from an OSP designer’s perspective. If you’re new to OSP, this will provide you with a good idea of where you’re heading. It’s short and sweet, overall.

Chapter 2, Cable and Connector Types, summarizes fiber, twisted pair, and coaxial cabling and their respective connectors well, too. I especially appreciated a comprehensive walk-through of fiber link loss budgeting, however testing and fiber characterization should have gotten more treatment.

Attenuation is important, but chromatic dispersion and polarization modal dispersion are as well. In general, designing cable plant for anything over 1 Gbps requires serious testing, and anything over 10 Gbps requires full scale characterization, especially for middle mile and long haul routes.

Another shortcoming that I noticed was around the discussion of the types of singlemode fiber. OS1 and OS2 are generic names for singlemode fiber that have more to do with the overall cable performance and not the optical fibers inside, which are indicated based on the [ITU designations, such as G.652](https://www.thefoa.org/tech/smf.htm).

I found the OSPDRM to be much more heavy on twisted pair but light on singlemode specs and applications. There are many different types of singlemode and specific applications that each is best suited for (remember the ITU designations), and like testing, is essential information for the OSP designer.

Fortunately I found other resources that addressed these shortcomings—namely the Fiber Optic Association’s [Certified Fiber Optic Specialist in Testing (CFOS/T)](https://www.thefoa.org/adv-cert.htm#test) course and Optical Technology Training’s [Certified Optical Network Associate (CONA)](https://www.ott.co.uk/courses/certified-optical-network-associate-cona.html) and [Certified Optical Network Engineer (CONE)](https://www.ott.co.uk/courses/certified-optical-network-engineer-cone.html) courses—so keep an eye out as I’ll talk more about those in upcoming reviews.

Chapter 3, Cabling Topologies, covers the many topologies possible for a cable plant and their pros and cons, including hybrid fiber coax (HFC) and passive optical network (PON) systems. I personally enjoy thinking topologically about my designs, and it’s all good stuff here.

Chapter 4, Pathways and Spaces, in my opinion, is by far the longest and most comprehensive part of the manual, going in-depth on direct burial, underground, and aerial pathways, along with the spaces involved in-between each. To give you a sense, it’s about 25% of the entire manual’s pages! It’s so large and I’ve referenced it so much I put it in it’s own binder.

When you’re just getting started in trying to understand and design the OSP, this is your go-to guide, and where BICSI’s OSPDRM definitely excels. It’s well organized, with helpful illustrations to visualize key concepts, make-ready management strategies, and references common NESC requirements for compliance purposes.

Overall, each pathway gets good treatment of what I’ll call conventional OSP design. Now despite all that, because of how important this chapter is, I want to cover some significant shortcomings that I hope can be improved in the next edition.

The first up is microtrenching. I was happy to see it briefly mentioned, but given the growing demand for fiber density, particularly in already congested urban areas, I was hoping for full treatment. The OSPDRM’s acknowledgement does help give the method credibility, but with the recent introduction of purpose-built materials and equipment, I believe it should now be treated as a first-class pathway.

Traditional trenching for underground networks serving campus, FTTX, and 5G endpoints is often too cost prohibitive, so OSP designers need to know these modern approaches to excavation to deliver cost-effective solutions to their clients. Using microtrenching, which I consider to include pavement saw cutting and vibratory plowing, you can create entire underground pathways across the distribution and access networks, all the way to the premises.

But designing and building it right requires guidance around the many pitfalls, as well as the stiff opposition from many AHJs. BICSI has an opportunity to offer that guidance and boost the credibility in the interest of its OSP design community.

The second shortcoming I’d love to see improved is general design best practices in dense urban environments. As I mentioned above, designers face congested underground and aerial pathways. Microtrenching is a promising solution for congested underground, but make-ready on aerial pathways creates a more limited, and sometimes more expensive constraint.

Designers also face restrictions on the creation of new pathways such as in downtowns or campus environments, regardless of congestion levels. In these areas, AHJs place these limitations mainly for aesthetic purposes, and this can create significant challenges. Restrictions on pole placement are common in these areas, for example, as many consider them unsightly.

In such areas, like a dense urban neighborhood, distribution cabling is usually routed through existing duct banks to each block, and then run across each building’s exterior. You’ll see this approach in nearly every city without aerial pathways. There is no guidance for such designs, even though there are approaches to these challenges.

For dense areas where new aerial pathways are allowed, I would have appreciated more pole setting and guying guidance in these environments, too, as setting new pole lines in sidewalks and alleyways are full of challenges. Other options, such as fiber through water or sewer pipes, are now becoming feasible to meet the growing demand for more fiber, and the OSPDRM should pay attention to such advancements.

The third shortcoming is the lack of long-haul and back-haul route discussions. If anything is central to OSP it is long-haul routes, and designing one requires an understanding of optical transmission constraints and the placement of spaces and equipment necessary for signal amplification or regeneration. I think the OSPDRM is incomplete without coverage of long-haul routes.

I’m particularly disappointed that one of my favorite types of long-haul, submarine cabling, wasn’t covered. I recognize that subsea is probably too complex, but freshwater lake or river crossings should be discussed in detail. Think of how many practical questions new designers might have about this topic:

- How do you transition from conduit to the water?
- Where should the hand holes be placed along the shore?
- Must the cable be buried like it is in subsea crossings?
- How do you plan for maintenance and repair of the crossings?
- What cable specifications should even be used for such applications?

I believe submarine crossings are different enough from underground and direct burial that it could be added as a fourth pathway with general recommendations.

Terrestrial and submarine long-haul wireline routes (over 80 km) are obviously a crucial aspect that OSP designers must be familiar with, but I’d like to see proper coverage of wireless, too. Going back to BICSI’s definition of OSP, wireless is considered a type of cabling for both short and long-haul networks, so OSP designers should be given guidance on these topics.

Wireless long-haul is commonly called back-haul, and having vendor-neutral wireless back-haul best practices seems like an important thing to standardize. There are many regions where portions of routes are difficult to get through with underground or aerial pathways because of the terrain, and high speed point-to-point wireless bridges between fiber can be utilized. And even if the entire wireline plant can be built out, having wireless back-haul as route diversity can build resiliency into critical network operations.

Wireless short-haul coverage of fixed wireless access and distribution design should be included, as well. To my knowledge, there is no vendor-neutral standard for designing these topologies, and as wireless ISPs (WISPs) are building out across the World to address network access deficiencies, BICSI could take a lead here to produce that standard. AHJs that oversee or finance this infrastructure could then require compliance to ensure a high quality and reliable network is built.

Alright, this is my last shortcoming of Chapter 4: weak coverage of entrance facilities. On page 1-1 of the OSPDRM, it literally states that “BICSI defines OSP as the telecommunications infrastructure that is designed and installed externally to buildings and typically routed into an entrance facility (EF).” It goes on to state on page 6-2 that “OSP systems are not just limited to being external to a building. In many jurisdictions, the OSP designer will also be responsible for the design and provisioning of cabling and pathways to where OSP cable is transitioned to approved inside cabling.” Based on these statements, entrances facilities are a fundamental part of OSP, so designers should be given substantial guidance on working with them, right?

Unfortunately, no. EFs are first discussed briefly in Chapter 4 on pages 252-3 as a sub-header that spans about a page in length and in very generic terms within the Concrete Universal Enclosure (CUE) section. They’re again discussed in Chapter 6 in the context of bonding & grounding for eight pages (starting on 6-34). This is eight times the amount spent on designing and installing them!

New designers will have lots of questions regarding entrance facilities as they start to work on projects, such as:

- How do you enter an older building without existing pathways?
- What do you do if the existing pathways to the EF are either congested or restricted?
- What if there is no proper EF in the building (many old building are like this), just random mechanical spaces that comms were haphazardly run to?
- What are the tradeoffs between aerial and underground pathways to the EF?
- When and how do you transition between OSP and ISP (premises) cabling?
- What are the best practices based on site type? How about a home? A hut? A campus? A data center? A cell site?

Proper entrance facilities into the wide range of buildings from the OSP is a core aspect of design work. EFs are crucial to get right the first time, no matter the site type. Once that plant is passed through to the premises and put into production, you don’t want problems down the road.

Recognizing that risk while I was trying to understand and design EFs, I turned to the [TIA-569 standard on telecommunications pathways and spaces](https://tiaonline.org/standard/tia-569/) for guidance. That’s probably your best resource on entrances facilities at this point. If there’s enough interest, I may do a resource review about it.

Alright, so that was a lot of feedback on Chapter 4! Was it helpful? Please give *me* feedback so I know how much of a deep dive you want in these reviews. Before we move ahead to the next chapter, I want to make note of something that’s come out since the release of the current OSPDRM that hopefully will start to address the shortcomings above.

In 2017, BICSI released the [G1-17, ICT Outside Plant Construction and Installation: General Practices standard](https://www.bicsi.org/standards/available-standards-store/single-purchase/bicsi-g1-17). This was the first of a “series of standards written to provide a common methodology for the construction and installation of telecommunication and data cabling used within the outside plant (OSP) environment, for varying applications, jurisdictions and projects.” I found it pretty vague, unfortunately; it seems more like a draft version, with only outlines in many places.

In 2022, however, two additions to series were released: [G2.1-22, ICT Outside Plant Construction and Installation: Pole Setting, Anchoring, and Guying](https://www.bicsi.org/standards/available-standards-store/single-purchase/bicsi-g2-1-22), and [G2.2-22, ICT Outside Plant Construction and Installation: Aerial Cable Installation](https://www.bicsi.org/standards/available-standards-store/single-purchase/bicsi-g2-2-22). Both are much more comprehensive than the OSPDRM, and I recommend you grab them now that they’re available.

I really like where things are going here, and I see an opportunity for BICSI to address the above shortcomings like microtrenching, long-haul, wireless, and entrance facilities in subsequent standards. So far, I’m impressed with these standards and will be adopting them for my designs. If there’s enough interest in learning more about them, I’ll add these to the resource review queue.

Chapter 5, Splicing Hardware, covers the basics of OSP closures and the twisted pair or optical fiber components and equipment necessary to splice cables together inside of those closures. Now I’m an optical network engineer and don’t deal with any coaxial, fortunately, but I was surprised that there wasn’t any discussion of it here.

In chapters 2 and 3 coaxial cables and hybrid fiber coax were covered, so it should make sense to discuss the related closures and termination components here. I don’t have any recommendations of where else to look, unfortunately, but drop me a comment if you do.

This was the only shortcoming I saw, keeping in mind that this is a broad topic to cover properly, and you’re going to rely mainly on the manufacturers of your materials and equipment for specific guidance. Also, depending on your role, you’ll need to look elsewhere to develop the skills necessary, like splicing, to install them. I have a lot of skill-building certification content coming up, things that helped me get strong on the technician fundamentals, so keep an eye out for that.

Chapter 6, Bonding and Grounding (Earthing) and Electrical Protection, covers one of the most important aspects of designing a network from a life, property, and equipment safety perspective. Your plant needs protective systems against risks like lightning, contact with supply circuits, ground potential rise, and even electromagnetic interference. This chapter covers it all.

Bonding and grounding wasn’t originally something I was familiar with, and not a common part of my daily design work, so it was one of the tougher areas for me on the exam. But this chapter does a great job of covering all the aspects. So whether you have to grab your references every time or are completely comfortable with grounding and bonding concepts, read this chapter carefully and make sure you follow code requirements and best practices for the plant.

Chapter 7, Right-of-Way, gives readers a thorough overview of the considerations when designing plant in the right-of-way. If you’re fortunate enough to focus solely on customer-owned OSP, such as on campuses or at data centers, good for you! Your job should be a lot easier.

For the rest of us, however, you better understand navigating the challenges of obtaining right-of-way to get your plant from here to there from anywhere. As the OSPDRM explains on p. 7-1, “The (right-of-way) acquisition process can be one of the greatest factors that affects a project’s schedule … If one small segment of an OSP route is not properly authorized, then that segment becomes the weakest link and prevents the entire OSP project from proceeding.” You definitely want to be solid on this topic.

Overall, the coverage of right-of-way in the OSPDRM is thorough and introduces the designer to all necessary considerations. You’ll learn what the different types of right-of-way are, how to acquire rights through tools like permits, licenses, or easements, and how to identify and describe the real estate you need access to. Follow the recommendations and you’ll avoid a lot of the pitfalls that exist in this aspect of OSP design.

But there still some shortcomings that I’ve identified from my six years of experience in the field. Here are some of the most important aspects missing from the chapter that I’ve had to deal with.

First up are two of the most common types of right-of-way acquisitions that OSP designers will deal with: pole and conduit agreements, often known as joint use agreements. Unless you fully own all the pathways you use, you’ll often need to ask another facility owner to attach to their poles or enter their conduits. And to do this properly, you’ll need joint use agreements, and permits for individuals pole attachments and linear conduit footage.

Do not install plant on or in third party facilities without properly issued permits; best case you’ll have to pay fines and make ready, and worse case you’ll have to remove the plant and could lose your agreement altogether. Either case puts your design in jeopardy and can cause serious setbacks on your project.

If you have joint use agreements, ensure your permitting accounts for all related facility use, and verify your records regularly with the facility owner. If you don’t have joint use agreements, it could be a lengthy process to get them, so initiate that process early wherever you may need to build out across. Even if you acquire facilities or receive authorization to use existing facilities from a third party, ensure they have permitting in order before proceeding with any project.

A second aspect you need to be clear on is the AHJ for the right-of-way, and the multiple dimensions associated with rights-of-way along any route. There are often multiple, even overlapping rights of way that can surface during a design.

A basic example of this is the right-of-way alongside a state road. In some areas, the municipality will define a right-of-way alongside its streets, but where a state road passes through that municipality, the state AHJ such as the Department of Transportation may have the final authority to issue permits per its regulations.

I’ll give you another example in permitting for what I call complex crossings such as highways, railroads, rivers, or bridges. The OSPDRM does do a good job addressing rail crossings, which can be some of the most difficult permits to get, but in some cases the state PUC may actually be the AHJ there. Here in Pennsylvania that is true, as well as for bridges. In that case, you may already be permitted to attach to the poles that you use to cross the track or dip under the bridge, but here you’ll also need separate state permitting to perform the crossing.

Alright, that’s enough on that. The bottom line is make sure you’re never wrong about the right-of-way, OK?

Chapter 8, Project Design, covers the project management aspect of OSP design—yet another aspect of the work that you as a designer are going to have to master to become successful. OSP projects by their nature are usually quite complicated, and you really don’t want to find your mistakes after the plant has been built. You’ll be relieved to know that the OSPDRM does a very good job of laying out the pitfalls, considerations, checklists, and processes to keep your projects on track.

At this point in the review you’ll probably also be relieved to know that I can’t think of any shortcomings to get into. In fact, I want to heap some more praise on BICSI here because of the well-deserved coverage of geographic information systems (GIS) as an excellent way to perform both your design work as well as the day-to-day O&M activities necessary to keep the plant in production.

Down the road I plan to talk a lot more about OSP design using GIS, and it’s encouraging to have BICSI endorsing the approach as well. Having Python and SQL mentioned in the OSPDRM for OSP automation was a pleasant surprise, and I’ll have a lot to discuss about that in the future.

Chapter 9, Maintenance and Restoration, is a new addition to the sixth edition of the manual, and covers routine maintenance, demand maintenance, emergency restoration, and disaster recovery. As a designer, it’s essential to understand these activities and proactively design the network to facilitate them all whenever required.

Included in each section of the chapter is a general overview and lists of the top considerations and scenarios all designers should be aware of. This includes several processes and procedures for emergency outages and disaster recovery preparation and response, which are risks your plant will unfortunately face every day. It’s best to design with that expectation in mind.

Chapter 10, Other Technologies, adds new material to the manual on the topics of Radio Frequency over Glass (RFoG), Passive Optical Networks (PONs), and fiber optic intrusion detection and alarm systems. Each of these topics could be its own chapter, or more likely its own manual, so consider them to be introductions as you’ll need to seek out other resources.

The section on RFoG is very short, at about half a page, but the PON section is more substantial. Now I have no experience with designing RFoG, but I’m guessing a good place to start for more information would be the [Society of Cable Telecommunications Engineers’ (SCTE)](https://www.scte.org/) website.

PON on the other hand, is something I’ve been designing for years, and I’d recommend checking out the Fiber Broadband Association’s (FBA) [Certified Fiber to the Home Professional (CFHP)](https://www.fiberbroadband.org/page/cfhp-&-service-provider-network-certification) program for that. My next certification review will be this credential, so stay tuned to learn more about this excellent program.

Regarding intrusion detection and alarm systems, I don’t yet have any experience in this, but I would love to monitor attenuation on every route enough to know if someone’s tampering with a hand hole. I think the best place to start here would be the [Fiber Optic Sensing Association (FOSA)](https://www.fiberopticsensing.org/), which was established in 2017 to help promote and advance this exciting optical technology.

## Do You Recommend It?

Alright, that was a pretty long review. If you’re still following along, you’re a die hard OSP designer and must be as passionate about pathways as I am. Or maybe you want to be. In either case, you probably want to know if the OSPDRM is for you. As I’ll probably say each review, every resource excels and falls short in different ways. However, the OSPDRM remains the best overall guide to OSP design, hands down. But let me add some context to that.

Since the first telephone wires were laid across the U.S., OSP has existed as a field, and it’s an essential part of the modern network infrastructure. But for decades the institutional knowledge on it was contained within the telecom companies, and both standards and training manuals were company specific.

When telecom was partially deregulated and large companies were broken up, private OSP engineering and construction firms stepped in, and the BICSI OSPDRM emerged. But there is still a lot of hard-earned wisdom stored up in the the seasoned engineers within the telecom companies, and many of them are now retiring. I was told by someone at a private OSP firm that they used to have a steady stream of retired OSP engineers they could use for projects, but those numbers are starting to decline.

I believe that the OSPDRM must capture that institutional knowledge for next generation of OSP designers who, like myself, entered the field from outside of the traditional telecom engineering path, and equip them with the skills and knowledge necessary to build the next generation of networks. Fortunately the OSPDRM is written by a team of veterans of the trade that volunteer their time to maintain it, so there’s still time to distill that wisdom.

But everything continues to move faster and faster, and the OSPDRM will have to keep pace to fill those gaps and update existing materials. For example, the [2023 National Electrical Safety Code (NESC) standard was released in August of 2022 and goes into effect next February](https://spectrum.ieee.org/2023-national-electrical-safety-code), so the OSPDRM is already outdated on a very important topic that spans multiple chapters. This could be added as errata in the near future, and I’ll be sure to note that here on my blog.

As an OSP designer, you just need to be aware of that issue even with the best resources available to you, and keep current on the rapid changes that, for better or for worse, are part of our industry. OSP is a challenging thing to keep pace with, as the technology accelerates but the resources often lag behind. The OSPDRM will get you started, experience will allow you to grow, and hopefully content like this will help you out along the way.
