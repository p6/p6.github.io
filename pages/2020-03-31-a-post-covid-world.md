---
title: A post COVID world. Some visions & fancies
layout: page
permalink: "post-covid-world-visions-fancies"
date: 2020-03-31
---


# A Post-Covid world: Some visions & fancies


# Synopsis

Mar 2020 will go down in the collective memory of civilization as the timeline of one of the events that changed the course of the world. To all those alive today, this is an unprecedented crisis that has constituted impact on everyday things ranging from global economy (and the bloodbath thereof) to personal hygiene (fun fact to see how much of this has translated into a hand washing OCD) to mental anxiety; 

Ticking close to a million affected globally, it remains to be seen how far the Covid-19 outbreak will go and when or whether this will cool off. At this point, a timely vaccination seems to be the only hope or we are left with the nasty option of gaining herd immunity; There isn’t really a winning cost negotiation on the latter.

One thing is for certain - that this will be a pivotal event (ala 9/11 for the lack of something within a millennial timeline of memory) - and its consequences will be far reaching. How we deal with this will be interesting to observe in the near future. The rest of this post discusses a few thoughts for the future. 

For the discerning technocrat reader, some of these may come across as familiar metaphors & idioms in distributed systems or modern software architectures. Given that real life problems are being solved more and more within the domain of their digital models (aka, digital twins; perhaps parallel digital universes could also be appropriate) - it is useful to look ahead into some possibilities of how this will pan out.


# #1: Global travel needs an overhaul

First, global mobility will largely come at the cost of a lot of paranoia and risk, and for good reason. After all, while SARS & MERS  were timebombs that were proverbially defused in the nick of time, we’ve all come to experience an occurrence that has actually exploded in everybody’s faces.

While we cannot shake off the fact that the root cause lies in some questionable dietary habits of certain populations in parts of the world (not restricted to, but quite obviously centric to China and even Africa for that matter), we must acknowledge that this is not a factor we can control.

What we can indeed control are the vectors of infection transmission and the obvious one that force multiplies local epidemics from being local into going global is Air travel.


## Lesson 1: Learnings in zero trust & multi-layered security & enforcement at the edges;

To prevent future outbreaks of massive proportions, airports MUST screen passengers. This may take invasive dimensions (if necessary) beyond routine temperature screening and other questionable heuristics.



*   Airports may need to run full health screening & diagnostic facilities; Fit to fly certificates will need to become the norm; In other words, the future comprises health-screening (and full fledged medical workers thereof), just like security
    *   Like everything, screening may need to be risk driven (such as travel history), but given how generic some symptoms are, one may need to screen broadly
    *   This applies to both parts of entry as well as ports of exit
*   In many ways, the infrastructure already exists - most airports are increasingly equipped with full body scanners. It is not difficult to imagine that software defined diagnostic tools maybe plugged in to enrich diagnostics of passenger health
    *   Passenger health data will increasingly scope into the travel domain
    *   This isn’t without nuance around privacy concerns; However, if one thing Covid has made obvious to the world is that individual liberty may need to give in the face of collective good
*   For respiratory diseases (such as Covid) in particular, antibody or swab tests may need to become the norm. We can assume at this point that testing kits that can produce results within minutes are increasingly becoming viable
    *   We may seen an advent of global, distributed virology databases, risk & screen factors including perhaps software defined diagnosis (admittedly a little futuristic)
    *   We can also hypothesize that airplane attire may change. It would be a good idea to assume masks are almost mandatory. We can speculate seating plans in economy may have to become less crammed. Airlines will have to create SOPs to deal with passengers who may (even for innocuous reasons) be a little under the weather)


# Urban planning needs to adapt & adapt quickly

If the outbreak has made one thing obvious, it is the magnitude of draconian responses nations have had to make in order to contain the spread  locally. While China’s lockdown of Wuhan and the entire Hubei province seemed rather drastic at that point, most others have had to conclude the hard way, the unreasonable effectiveness of this action (maybe coupled with less drastic maneouvres such as social distancing);


## Lesson 2: Learnings in circuit breaking & fault domain isolation



*   High risk urban areas with population density may need to be re-imagined for exercising the ability to isolate and isolate effectively. Where isolation specifically means, being cut off from the rest of the healthy world; 
*   This crucially includes defining locality boundaries, roads & other accesses, modes of transport amongst other things. In the event of a shut down, and when people’s movements need to be restricted, obviously it is essential to localize these to the smallest defined unit of locality possible so the blast radius can be contained
*   Static stability becomes a design constraint; We cannot obviously envision cities without external shared services, but it is imminent that food security & local healthcare be scoped in
    *   It may or may not be possible to stand up isolation facilities everywhere, but triaging, detection & treatment of minor cases could certainly be localized. In this effect, China’s model of fever clinics maybe a thing to emulate
*   Controlling any epidemic will increasingly be about surveillance of those infected. While Covid was quite contagious (R0 between 2 - 4, going by existing literature), it isn’t as high as for example, the airborne Measles. There is obviously no assurance that future epidemics will be sparing in nature. 
    *   Contact tracing can become unviable as R0, scale of undetected spread and reaction latency increases. 
    *   While this may be uncomfortable to some, location based services (Telcos, Mapping providers, Wearables) and data will constitute comprehensive surveillance, tracing & quarantining capabilities. 
    *   Detective & diagnostic controls may become necessary for large social gatherings of all kinds - from schools to malls to conferences.
*   Lastly, the urban reality of migrants to cities & economic hubs may not necessarily go away for good (although it could) - hence the ability to drain recovered or healthy citizens & families from epicenters of infection is a necessary capability to develop


# Workplaces & businesses will evolve

Covid has quite obviously exposed the inherent fragility in economic models concerning supply chains or dependencies on essential goods externally. Most have been designed to optimize for costs and political conveniences over resilience in the face of unexpected events. Net result is the cascading failure 


## Lesson 3: A business continuity plan is no longer a document you advertise reactively in times of a crisis. At the heart of continuity is eliminating dependencies and ensuring continuity of people, processes & tools that constitute the workforce.



*   Redundancy forms the baseline risk mitigation. No longer can we have a single factory for the world; We will need several;
    *   Disaster Recovery SOPs shall be defined at all levels
*   Essential services, logistics & supply chains will need to be designed to be incredibly resilient
*   Ways of working and cargo-cult models thereof will back off in the face of much more digital friendly ways of (remote) working. 
*   Digitally enabled workplaces may become the norm. We can say this with a seasoning of caution, but perhaps there is a viability of the failed WeWork’s failed Workplace as a Service model, albeit in a different flavour
    *   By this experience at least, anybody who can support working from home (read digitally empowered workplaces, governments included and perhaps the broad spectrum of all white collar work), can and will support working from home;
    *   Those who can’t may do so out of specific compulsions - security, compliance, networking needs, telepresence infrastructure, machinery & equipment and so on. 
    *   Workplaces may become places to meet your local cluster of team mates not expressly with the intent of working, but perhaps socialization; The future workplace may no longer be special economic zones externalised from the cities, but rather functional facilities in the cities defined by these essential characteristics (connectivity, location, etc)
    *   This should also have the good side-effect of reducing sprawl within cities and the burden on public transport & infrastructure

