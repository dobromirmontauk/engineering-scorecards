<!----- Conversion time: 0.804 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Fri Jul 05 2019 11:53:26 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=17MAjqK2ybnzp4gUSZaVJhez0aH6o-B-tjFXtwlnJ_aU
----->


<h1>Tech Lead Scorecard</h1>


A Tech Leads is the Last Line of Defense for high-quality code and a reliable system. 

Tech Lead roles are designed to provide tension with the [Feature Lead](https://docs.google.com/document/d/1052-6Lt8RXlyRttyIuTmhXAn0-iDLOwL669-IUqMC7U/edit#heading=h.bbuiwspo936x) roles. The most important aspect of a Tech Lead is that they _care deeply about good engineering and the ~1-year maintainability of their system. _Tech Leads do not evaluate their success on a per-project level. Instead, they take _pride_ as the system evolves closer to their _ideal state_ (which they have a strong opinion on!) and they _cry inside_ when ugly complexity is introduced for "business reasons" (though they have the maturity to accept this may be temporarily necessary). A Tech Lead is a meticulous gardener.

Ergo, to be a good tech lead actually requires a particular kind of _personality_ - not every engineer should expect to become a TL as part of their career path.

Tech Lead roles last for 1+ years as it requires a deep understanding of the current state and executing on a long-term vision.

<h2>How to use this scorecard</h2>


To get the most out of this document you should _score yourself_ on each item, and give yourself a min/max/average on each dimension. Then, ask your manager to do the same - and maybe peers too. See if they grade you close to how you grade yourself. The goal is to help you go through the [learning cycle](http://www.cala.fsu.edu/modules/assessing_knowledge): ignorance → declarative → procedural → mastery. 

Make a copy of this [template](https://docs.google.com/spreadsheets/d/1PX61irzc6eCxgl2tzEzE6aKF92l7EoHcVac7Nb1Beko/edit#gid=0) and use the following rating scale:



*   1 - You’re not doing this and aren’t likely to in the future.
*   2 - You have significant areas where you need to improve.
*   3 - You do this well.
*   4 - You do this amazingly — keep it up.
*   5 - OMG how do you do this so well???

<h2>How your manager judges you:</h2>




1. **_Quality: Quality you can taste<sup>®</sup>_**
    1. You have **strong opinions** (loosely held!) about what makes good code and good design. You are comfortable saying "no" to work that doesn't meet your bar. Your codebase looks like it was written by a single person.
    2. You are constantly improving the state of your code and system, making it easier to develop in. This includes (but is not limited to) testing, releasing, debugging tools, documentation, automation, logging, monitoring, and overall system cost in $$$.
    3. You maintain high production quality of your system. It requires little human intervention and provides high signal/noise ratio. You have well-defined and well-communicated SLOs (measured from the customer's perspective) which you always hit.
    4. Feature development on your systems is effortless. Technical debt does not consume a large percentage of your team's time nor does it significantly slow down feature development. Engineers can't imagine an easier way to develop features in your system.
    5. You inspire other engineers on your team to have a higher quality bar through code reviews, design reviews, postmortems, on-call review, etc.
2. **_Expertise: you are the undisputed expert on your system_**
    1. You understand **all the code you own** and the nuances of design tradeoffs taken historically. You understand the inputs and outputs. You can reason through complex scenarios to predict how your system will behave.
    2. You are aware, and approve of, every change going into your system (at the code and design level). Approval can be delegated through people you trust (this is encouraged).
    3. You have a 6+ month plan of how you want your system to evolve.
    4. You understand all the metrics that matter for the system that you are running and you regularly ask insightful questions and find surprising answers.
    5. You use your expertise proactively to help the organization improve designs and avoid expensive mistakes.
3. **_Team: you build and run a high-performing team and continually improve it_**
    1. You realize it's not about you anymore. You put the team first in everything from giving recognition to the sexy projects to the promotion opportunities.
    2. You are an amazing teacher. You effortlessly tie back implementation details to technologies, concepts, and entire thought domains. From 1:1 coaching to blog posts, tech-talks, or conferences, you scale your teaching appropriately. 
    3. Your team runs itself. You are not a SPOF - multiple people can step in and take your role, at least temporarily. Every engineer has an equal voice and is comfortable using it. 
    4. You are a talent magnet. People seek you out to work with you and your team. 
    5. You are an effective partner to your EM for building a [Level 4 Tribe](https://en.wikipedia.org/wiki/Tribal_Leadership): the team has fun, loves what they do, and may be friends forever. 
4. **_Execution/Process: you keep the team executing at peak-performance with minimal (but not too little!) process_**
    1. You are actively contributing code (>50% of your time) and a top producer.
    2. You enact the right amount of process to keep your engineers fully utilized, stakeholders informed, customers happy, risks identified, and commitments met. 
    3. You maximize the overall throughput of your engineering team over ~months. Engineering time is sacred to you and you don't waste it needlessly. Engineers know what work needs to be done and the relative importance of everything in the backlog.
    4. You make visible progress on multi-quarter goals on a monthly basis. 
    5. You wear every hat that is missing in your team/organization. As last-line-of-defense, you sometimes need to be a FL, a PM, an EM, a QA engineer -- temporarily...
5. **_Customer Obsession: you understand your internal customer's needs deeply_**
    1. You know who your customers are and you evangelize their problems, needs, and vocabulary within your team. All members understand the bigger picture and the role of your project/team within it.
    2. You care about your customers. You make weekly, quarterly, and yearly commitments and regularly hit them. 
    3. You understand the problems of your customers better than they do. You regularly solve their problems preemptively.
    4. You know when to accept technical debt for the sake of the customer and you pay it down at the right moment.
    5. You escalate product requirements when they are unclear or not in the _overall _best interest of your customers/users.
6. **_Leadership: _**
    1. You get buy-in from your engineers, EM/PM, and peers for your technical vision.
    2. Your engineers love working with you. You delegate effectively and bring out the best in them by solving the Goldilocks problem: just the right problem for each engineer.
    3. You manage up effectively. You are high signal-to-noise and escalate when appropriate: bad technical decisions, poor work quality, inappropriate workload, unreasonable technical debt, etc.
    4. You maintain healthy peer relationships with other TLs and über-TLs. You keep them aware of the issues in your system and the technical challenges on your team, as well as your plans to deal with them. You know what Feature Leads need from your system in the next year.
    5. You navigate the changing technical tides effectively (both proactively and reactively). You realize your system will not be the best solution, forever, and that past decisions may be the wrong future direction. You don’t let ego or fear prevent you from catching the next wave: you jump in head-first, learn the implementation, technology, concepts, etc - and teach your team to do the same.

Some useful resources:

[https://www.slideshare.net/thekua/tech-lead-skills-for-developers?next_slideshow=1](https://www.slideshare.net/thekua/tech-lead-skills-for-developers?next_slideshow=1)

_Credits: thanks to … for helping put together this scorecard, and to Wade Chambers whose VP of Engineering scorecard inspired me to make this Technical Lead one!_


<!-- Docs to Markdown version 1.0β17 -->
