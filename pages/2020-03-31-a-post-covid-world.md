---
title: A post COVID world. Some visions & fancies
layout: page
permalink: "post-covid-world-visions-fancies"
date: 2020-03-31
---


# Synopsis

Mar 2020 will go down in the collective memory of civilization as the timeline of one of the events that changed the course of the world. To all those alive today, this is an unprecedented crisis that has constituted impact on everyday things ranging from global economy (and the bloodbath thereof) to personal hygiene (many may have gained a handwashing OCD for life) and mental anxiety [^1] (Covid-19 trends keepying you awake at 0300); 

[^1]: https://twitter.com/jaredbkeller/status/1243739646430973954

Ticking close to a million affected globally (forecasted by Apr 3 2020) [^2], it remains to be seen how far the Covid-19 outbreak will go and when or whether this will cool off. At this point, a timely vaccination seems to be the only hope or we are left with, sparing the nasty option of gaining herd immunity. There isn’t really a winning cost negotiation for the latter, although it may be a strategy for some, though not for the mostly sensible.

[^2]: https://coronavirus.jhu.edu/map.html

Looking back at the last 3 months, one can say that enough people saw it coming, given the abundance of data in this age, except they were all the wrong people. Given how the US and Europe have completely reeled, and how developing nations in Asia have gone all out to take extreme economic stress, it is obvious that this is a fight for survival and coming out with as few bruises as possible. Statistics can model CFRs and while these may dampen the alarms of apocalypse, the fat tailed risk profile of the unknown is an equally rational & compelling reason to elicit an overwhelmingly conservative responses from most governments.

One thing is for certain: that this will be a pivotal event (ala 9/11 perhaps, for the lack of something within a millennial timeline of memory) and its consequences will be far reaching. How we deal with this will be interesting to observe in the near future. The rest of this post discusses a few thoughts with some fanciful pondering into how we should be dealing with another Covid like pandemic in the years to come. 

For the discerning technocrat reader, some of these may come across as familiar metaphors & idioms in distributed systems or modern software architectures. Given that real life problems are being solved more and more within the domain of their digital models [^3], it is useful to think ahead into some possibilities of how this will pan out.

[^3]: https://en.wikipedia.org/wiki/Digital_twin

# Prevention is better than cure; Global travel needs an overhaul

First, global mobility in the future will largely come at the cost of a lot of paranoia and risk, and for good reason. After all, while SARS & MERS  were timebombs that were defused in the proverbial nick of time, In Covid, we’ve all come to experience a first hand occurrence that has actually exploded in everybody’s faces.

While we cannot shrug off the fact that the root cause lies in some questionable dietary habits of certain populations in parts of the world (not restricted to, but quite obviously centric to China and even Africa for that matter), we must acknowledge that this is not a factor we can control.

What we can indeed control are the vectors of infection transmission and the obvious one that force multiplies local epidemics from being local into going global is Air travel.


## Lesson 1: Zero trust, threat-aware, multi-layered security & enforcement at the edges [^4];

[^4]: https://en.wikipedia.org/wiki/Zero_Trust

To prevent future outbreaks of massive proportions, airports must become accountable for screening passengers & averting catastrophes. This may take invasive dimensions (if necessary) beyond routine temperature screening and other questionable heuristics.

Given the unique nature of the present crisis, we may note with the full 20:20 vision of hindsight that the travel ecosystem failed to take cognizance of 2nd (and higher) order effects of the initial spread in China, which was controlled with rather naive measures. Ofcourse, those measures would no longer be effective thanks to complacency on the part of Italy & Iran, which have both amplified the network effects to an overwhelmingly global scale.

It is fair to belive that airports & air travel (and perhaps others) will need to change ways perhaps in more drastic magnitude than they did in the face of 9/11.

*   Airports may need to run full health screening & diagnostic facilities; Fit to fly certificates will need to become the norm; In other words, the future comprises health-screening (and full fledged medical facilities, therefore), just like airport security; Clearly, this isn't a free lunch, so the struggling airline industry will need to pass this cost to the flyer
    *   Like everything, screening may need to be risk driven (such as travel history), but given how generic some symptoms are, one may need to screen broadly
    *   This applies to both parts of entry as well as ports of exit
*   In many ways, the infrastructure already exists - most airports are increasingly equipped with full body scanners. It is not difficult to imagine that software defined diagnostic tools maybe plugged in to enrich diagnostics of passenger health
    *   Passenger health data will increasingly scope into the travel domain
    *   This isn’t without nuance around privacy concerns; However, if one thing Covid has made obvious to the world is that individual liberty may need to give in the face of collective good
*   For respiratory diseases (such as Covid) in particular, antibody or swab tests may need to become the norm. We can assume at this point that testing kits that can produce results within minutes are increasingly becoming viable [^5]
    *   We may seen an advent of global, distributed virology databases [^6], risk & screen factors including perhaps software defined diagnosis (admittedly a little futuristic)
    *   We can also hypothesize that airplane attire may change. It would be a good idea to assume masks are almost mandatory. We can speculate seating plans in economy may have to allow healthier ergonomy. Airlines will have to create SOPs to deal with passengers who may (even for innocuous reasons) be a little under the weather

[^5]: https://economictimes.indiatimes.com/industry/healthcare/biotech/healthcare/pune-based-mylab-becomes-first-indian-co-to-get-its-covid-19-test-kits-validated/articleshow/74785575.cms?from=mdr
[^6]: https://www.gisaid.org/

# The world can't afford to stop for weeks: Urban planning needs to adapt & adapt quickly

If the outbreak has made one thing obvious, it is the magnitude of draconian responses nations have had to make in order to contain the spread  locally. While China’s lockdown of Wuhan and the entire Hubei province seemed rather drastic at that point, most others have had to conclude the hard way, the unreasonable effectiveness of this action (maybe coupled with less drastic maneouvres such as social distancing);


## Lesson 2: Learnings in compartmentalization [^7], circuit breaking [^8] & fault domain isolation [^9]

[^7]: https://en.wikipedia.org/wiki/Compartmentalization_(fire_protection)
[^8]: https://en.wikipedia.org/wiki/Circuit_breaker_design_pattern
[^9]: https://en.wikipedia.org/wiki/Fault_detection_and_isolation

*   High risk urban areas with population density may need to be re-imagined for exercising the ability to isolate and isolate effectively. Where isolation specifically means, an infected locality being cut off from the rest of the healthy world; 
*   This crucially includes defining locality boundaries and granularity, roads & other accesses, modes of transport amongst other things. In the event of a shut down, and when people’s movements need to be restricted, obviously it is essential to localize these to the smallest defined unit of locality possible so the blast radius can be contained
*   Static stability becomes a design constraint [^10]; We cannot obviously envision cities without external shared services, but it is imminent that food security & local healthcare be scoped in to the impact zone
    *   It may or may not be possible to stand up isolation facilities everywhere, but triaging, detection & treatment of minor cases could certainly be localized. In this effect, China’s model of fever clinics [^11] maybe a thing to emulate
*   Controlling any epidemic will increasingly be about surveillance of those infected. While Covid was quite contagious (R0 between 2 - 4, going by existing literature), it isn’t as high as for example, the airborne Measles. There is obviously no assurance that future epidemics will be sparing in nature. 
    *   Contact tracing can become unviable as R0 [^12], scale of undetected spread and reaction latency increases. 
    *   While this may be uncomfortable to some, location based services [^13] (Telcos, Mapping providers, Wearables) and data will constitute comprehensive surveillance, tracing & quarantining capabilities. 
    *   Detective & diagnostic controls may become necessary for large social gatherings of all kinds - from schools to malls to conferences.
*   Lastly, the urban reality of migration and migrants to cities & economic hubs may not necessarily go away for good (although it could) - hence the ability to drain [^14] recovered or healthy citizens & families from epicenters of infection is a necessary capability to develop

[^10]: https://www.allthingsdistributed.com/2018/03/ten-years-of-aws-compartimentalization.html
[^11]: https://www.businessinsider.in/science/news/11-extreme-measures-china-took-to-contain-the-coronavirus-show-the-rest-of-the-world-is-unprepared-for-covid-19/articleshow/74660747.cms
[^12]: https://en.wikipedia.org/wiki/Basic_reproduction_number
[^13]: https://www.cnbc.com/2020/03/27/coronavirus-surveillance-used-by-governments-to-fight-pandemic-privacy-concerns.html
[^14]: https://www.usenix.org/conference/osdi18/presentation/veeraraghavan

# Business Strategy & ways of working will need to evolve

Covid has quite obviously exposed the inherent fragility in economic models concerning supply chains and external dependencies thereof [^15]. Most have been designed to optimize for costs and political conveniences over resilience in the face of unexpected events. Net result is a cascading failure [^16] in the face of catastrophic events

[^15]: https://www2.deloitte.com/global/en/pages/risk/articles/covid-19-managing-supply-chain-risk-and-disruption.html
[^16]: https://en.wikipedia.org/wiki/Cascading_failure

## Lesson 3: A BCP is no longer a document you advertise reactively in times of a crisis. Digitally enabled workplace & workforce is no longer a utility, but rather a necessity 


*   Redundancy forms the baseline risk mitigation. No longer can we have a single factory or centralized supply chain for the world's needs; We will need several;
    *   Disaster Recovery SOPs shall be defined at all levels
    *   Leaders will need to pick up nuances in numeracy (beyond modelling spreadsheets) & literacy around crisis management to handle war like situations [^17]
*   Essential services, logistics & supply chains will need to be designed to be incredibly resilient
*   Ways of working and cargo-cult models thereof will back off in the face of much more digital friendly ways of (remote) working. 
*   Digitally enabled, telecommute workplaces [^18] may become the norm, where possible. We can say this with a sprinkling of caution, but perhaps there is a viability of the failed workplace as a ervice model, albeit in a different flavour
    *   By this experience at least, anybody who can support working from home (read tech, BPO, industry 4.0, banks, governments (!) and perhaps the broad spectrum of all white collar work), can and must support working from anywhere;
    *   Those who can’t may do so out of specific, but perhaps negotiable compulsions - security, compliance, networking needs, telepresence infrastructure, machinery & equipment and so on; These maybe concerns local workplace hubs may solve, as opposed to massive SEZs and centralized workplace models of the current
    *   This should also have the good side-effect of reducing urban sprawl easing the burden on public transport & infrastructure
    *   It remains to be seen how alternative models to foster coaching & mentorship in pyramid shaped organizations as well as the social aspects of work adapt. We can only guess that digitalization will usher creativity into conventional L&D as well as social collaboration. Perhaps we could also speculate that a modern form of apprenticeship could arise

[^17]: https://www.forbes.com/sites/sap/2020/03/23/wartime-ceo/#32b6b41d6452
[^18]: https://en.wikipedia.org/wiki/Virtual_workplace

