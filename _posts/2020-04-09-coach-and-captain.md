---
layout: blogpost
title: "Coach & Captain - a pattern for team leadership"
type: "TEAM"
filename: coach-and-captain
date: May 09, 2020
image: /images/gena-okami-y1lpMk37EnE-unsplash.jpg
image_attribution: Photo by Nick Fewings on Unsplash
---

In our company, Team Lead's were responsible for technical direction, delivery and their direct reports. 
This lead to an incredible work load for the Team Leads, so we decided to experiment with implementing Team and 
Technical leads within the same team to combat the workload. This is how it went (from the Tech Lead's perspective).

There are numerous approaches to handle this growth. In our case, we implemented a Technical Lead role, while
retaining the Team Lead role, on the same team. In addition, for our team, the Team Lead had never worked as
a developer but did have a background in the business of software products. This particular configuration
meant that the Team Lead was able to maintain a higher level view the teams delivery impact on the business, focus 
on team co-ordination and communicate with stakeholders on an almost constant bases. This work, which used to impact
the technical Team Lead, no longer had an impact on the team. The team's productivity was further enhanced by having
a Captain, the Tech Lead, almost always constantly present (I say almost always for both roles because no role a 
human carries out, goes by the code, sometimes these two would overlap especially when one of them went on leave).

I called this Coach and Captain because the Captain played with the team and provided leadership 'in the game' of
code implementation, while the Coach guided our decisions and strategy through the climate of the organisation 
and did everything in their power to ensure this group of developers was functioning as a team.

**The previous role of the Team Lead**

All of our teams had a Team Lead. This was a developer who had moved into a management position. All the developers in a team reported to the Team Lead. This person was not only a line-manager, expected to have regular one-to-ones with everyone in their team, but also was responsible for:
 * Architecture & technical product direction (strategy).
 * Software Product delivery and co-ordination of work across the different products (tactical) - working with Product Managers.
 * Technical mentorship to improve skills & practices
 * Team & Department people-related admin

    
To put this in perspective, the Team Leads were in every meeting about work planning, updates, story creation, team logistics, recruitment, talking with users & clients, researching technology, tools & vendors, the list goes on. There were many scenarios where the Team Lead was simply not available to the team.
We had fairly large teams. My team was between 6-8 people at any time. This was a good size given that we maintained all of our own infrastructure, wrote and deployed all our own code and were on-call for everything we built.
Three Team Leads reached breaking point and resigned within a few weeks of each other.

**Introducing Tech Leads**

Clearly the stress of taking on all that responsibility caused our leaders to burn out.
Leadership made the decision to split the line management and technical responsibilities. 
Each team would have a Technical Lead as well as a Team Lead. The Tech Lead would take on the Technical Strategy & Direction, tooling & practice oversight and, in my team, career-development work.

**Our Coach and Captain**

Our Team Lead was not a coder. They had run their own start-up for a technical product but were not involved in building it. In our team, this role was very much like a Coach of a team. 
The Team Lead participated and guided in the realm of our Software Products and understood helped the products get 
delivered but didn't actually 'play' with the team.
They made sure to  actively listen to each person, helping with and providing advice on personal well-being and 
generally taking care of them within the organisation. They were a good communicator and were also experienced in 
business which helped the team navigate scenarios and understand priorities in the bigger context of the wider business. 
They were also a good mediator and worked with each person to improve their ability to work within a team.
The Tech Lead did 'play on the field' with the team. 
The Tech Lead sat with the team almost all week, was available for reviews, oversight, direction and judgement calls. 
Unlike the previous Team Lead who was bogged down with admin, the Tech Lead was much more available which means 
decisions were made, work unblocked and technical re-direction was able to happen very quickly.

**What did the team think?**

As this Team and Tech Lead worked well together, the team enjoyed the leadership configuration because they felt that their needs as people and technologists were able to be addressed.
The team's motivation and output greatly improved overall. The Tech Lead availability sped up technical work. 
For decisions that were clearly technical or not, it was clear who could assist but for those decisions that were not as clear, sometimes the other Lead needed to be consulted.
It is clear that if there is not trust between the 2 Leads, this configuration could greatly slow a team's delivery speed. Luckily in our case, this trust was in place and the 2 Lead's were highly aligned. 
As time went on, the need for consultancy between the two became less as well.

**What I learned as the Tech Lead**
I've been asked a few times if I would consider a Team Lead position but I haven't wanted to remove myself from the codebase. I very much enjoy still building software, and I'm fully aware that Team Lead roles take you away from the code, at least in a mid-sized company and up (my preferred company sizes).
I've also been inside many teams where a Technical Team Lead could be absent from the team for hours and days and though a Senior Developer is perfectly capable of making a tactical decision, they may be missing context in  overall strategy (either by their choice or due to culture).
Personally I gained a lot of insight from working with someone who had more experience with the other aspects of the business. It was incredibly insightful to get feedback on how what I said was coming across, where I needed to be clearer, what certain situations truly meant (translating 'business speak').
I am a better leader for it.

**Where would you use this?**

Not all organisations would require this set-up. Certainly small organisations could benefit from a coach but your Tech Lead can probably handle Team Lead responsibilities with some training (if they don't have experience).
Mid-size (over 20 developers in my opinion) and up could certainly benefit from this set-up as the technical work demands attention and you're likely to have more associate to mid-level engineers than you are juniors (growth effect).
Also if the technical work is very demanding, it's can be very difficult for a Technical Lead to keep up with Technical Strategy, code quality and a high-level of engagement with each team member.
It's also useful:
        - in difficult teams that are not quite working well together
        - you have a talented Technical Leader but they don't want to line manage.
        - you have immature developers who are technically gifted but need guidance on working within a team and taming their ego.
        
**What about an actual coach or Scrum master**

Having worked with Scrum masters and coaches, the immediate difference here is accountability. 
I know this can be a touchy subject but to make it simple - Scrum masters and technical or process coaches
are there temporarily to improve a way or working, skill set, etc and then leave once some metric has been reached.
The best Scrum masters I've met, have said to me, 
"if I do my job well enough, you won't need me anymore". This is great, sometimes you just need them to get things
back on track. But _this_ coach is not a temporary team member with a short term directive.
They are just as accountable for the team's performance as the actual team is.
Personally this leads to trust with the team - this person is everyone's line manager at the end off the day.

**So they took over all the admin while you did the fun stuff?**

This is feedback I received after presenting this topic in a talk. It amused me because the sentiment was similar 
to the complaints made by the old Team Leads, and other Team Leads I've worked under before. 
But I would warn against thinking about it like this. This distribution of work does not take away from the fact 
that the Tech Lead should be as informed about the teams' overall functionality, progress, delivery, etc as they 
would be if they were also the Team Lead. Visa versa, the Team Lead needs to understand the technical strategy, 
constraints, skill requirements, as well as the Tech Lead does.  

**Why tell people about this**

Computing is still a new industry and continues to grow everyday, even through downturned economies. In the early
day, people entered computing from other industries. These days, people enter Software careers from other industries
by re-training (bootcamps, university, elf-taught etc). We greatly benefit from this as an industry, not only because
we can continue to grow skills in Software which are sorely needed but these folks also bring with them thier experience
of working in other roles. I think Technical Leadership can also benefit from accepting other people into our 
management ranks. Their experience from similar roles in other jobs is extremally valuable, especially for growing
software engineers who will be managers one day. Currently, many developers are often promoted into Leadership
too early, often when they are not ready and before they understand what the reponsibility of the leadership role
they've fallen into and usually with little to no training of what it actually means to be someone's line manager.
We could grow better software leaders by leveraging the experience and coaching of leaders who are not technical.
Some may think this impossible due to the technical experience required for software roles but if we can our ago aside
and realise that others can follow technical work better than what we assume they do, we could open ourselves up to 
learn to be become ont only better technical leaders but better people too.

