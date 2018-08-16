---
weight: 2
title: "Mill Control Systems Upgrade | Rob Hogarth"
description: "The new infrstrcture significantly reduced the risk of system failure which was upwards of $2m per day of lost revenue"
nav_heading: "Mill Upgrade Case Study"
thumbnail: "360.jpg"
case_short_title: "Mill Control Systems"
case_title: "Peak Gold Mines Mill Control System"
case_subtitle: "Infrastructure Upgrade"
case_description: "Peak Mill Control Systems Infrastructure required a complete overhaul and replacement.  I was able to introduce new infrastructure to resolve a number of highlighted risks"
case_feature_img: "featured-360.jpg"
case_summary: "I designed completely new infrastructure to run the Peak Gold Mines mill control systems.  This included new networking, server and power management components.  This reduced risk of expensive downtime through multiple layers of redundancy."
date: 2017-10-15T03:29:08-07:00
draft: false
---

# The Challenge

Risk analysis showed that the mill control system at Peak Gold Mines was amoung the oldest systems onsite.  The servers were in fact repurposed desktop machines, which were long out of warranty.  They contained no inbuilt redundancy such as RAID, redundant power supplies.  The OS was Windows 7 and not a server OS.  Due to the desktop OS version, backups were not compatible with the onsite backup systems, and were done Ad-Hoc.  Analysis showed security concerns due to the reuse of service accounts between systems, and the spread of passwords between maintenance groups.  The network had some redundancy but had no capacity for any speed upgrades and had limited ports available.  While there were multiple power feeds available in the mill, they were not utilised for use within the IT space.  A UPS was present but it had limited life and no monitoring capability or auto-system shutdown setup inconjunction with the servers.

There was a ongoing issue around total system ownership.  The Mill maintenance teams maitained the Control System software, and the associated PLCs.  They had at one point had some control of the network, but no expertise to maintain it, or any of the IT infrastructure.  The IT team had the capability to maintain the infrastructure but did not have the capacity to mainain the application layer.

Loss of control systems meant a complete stoppage of the mill which was priced around $100k per hour.

The maintenance teams had been reluctant to make any changes or upgrades, as things were seen to be running fine, although there were complaints about systems being slow.  As part of the IT team I felt the infrastructure was completely unacceptable, and a catostropic failure was imenant.  I felt that a close collaboration with the mill teams to design and implement a system that would be possible and if guided through the process the mill teams would be accepting of the change.

![](//localhost:1313/mill/img/20170801_040308503_iOS.jpg)

.

# Contextual Inquiry

To begin our systems analysis, we conducted site visits to 360 Pro. What we did was to get to know their process as much as possible and map out the actual data flows that happen. After interviewing their member coordinator and coaches, we discovered all the documents they use for a workout program for any athlete to begin. A more important issue was that Chappy was the only one using the performance framework, because they simply "didn't get it" using the iPad Numbers document. It was a relatively new system and there was no way they would be able to grasp it right away.

At this point, we knew that the solution was making the performance system more accessible to all coaches at the gym, and create a system that is possibly scalable across future branches of the gym.

# Feature Prioritization

I've done research on how personas and user stories might carry too many assumptions and have loopholes. I came across [job stories](https://blog.intercom.com/using-job-stories-design-features-ui-ux/)
some time before and I wanted my team to implement it. According to Paul Adams of Intercom, "Job Stories are a different way of thinking about defining features, UI, and UX." And so, being adventurous and a bit skeptical, we came up with our own. I think it helped us figure out the features we needed even more.

![](//localhost:1313/360pro/img/jobstories.jpg)

This was very early on in the process and it helped my team empathize with our primary users. This wasn't really required by our instructor, we just went ahead and did it. The result was great for us, because we decided as a team on the design components we wanted to roll out: the performance testing core functionality, a leaderboard, a digital version of the gym's Workout of the Week whiteboard, and general athlete user management.

# Field Immersion

![](//localhost:1313/360pro/img/field.jpg)

I learned about field immersion during my visit to UX Singapore 2016. I wanted to try out the idea for our project so I invited my teammates to actually try a gym session out, just to go to an extra level of empathy. Jacob Chua and I underwent the trial program, and we tried out best to empathize with the coach who was teaching us what to do. At that point, I was thinking of the possible ways I could make the system of testing easier, considering the situation we faced. I tried to create a mental model for the coach embedded into my subconscious.

# Systems Analysis

We created a lot of data flow diagrams for the project, considering each process very carefully. We asked ourselves, how could we would create a usable and delightful product for the end-users, considering all these data flows? How would it actually translate to the product design? Considering the feature sets we decided on, what will be the best way to design them?

We also created logic models, use case diagrams and other documentation. This was all bulk of the coursework we were required to do, and I was more than excited to create the screens after all the prep work we were doing. During this process however, I felt that we could have done more user research really geared towards understanding the user more, like a usability test using low-fi prototypes.

# Design Decisions

![](//localhost:1313/360pro/img/testing.png)

**Making Testing Easier**
<br>Since testing was the main problem, we concentrated on designing that experience first. Using exercise cards that automatically compute pro score based on raw data while also considering gender norms, we focus the experience on actually just filling out information easily for the primary user. We wanted to eliminate cognitive load as much as possible.

**Testing Summaries**
<br>The summaries should indicate whether an athlete has improved his pro score. We used a variety of visual design communication techniques to convey this.

![](//localhost:1313/360pro/img/starttest.png)

**Tracking Performance**
<br>Leaderboards and member dashboards will fulfill this aspect of the product. Search definitely plays a major role in the user experience of the app, and almost always populates all design components.

# Next Steps

I will have to create a FramerJS prototype to simulate microinteractions. Though that might not be useful anymore since we can go straight to development. Another challenge is using the right front-end and back-end frameworks to build the platform.

The gym uses an iPad for testing so further refining the responsiveness of the designs, and also optimizing for tablets would be a good idea. We will probably conduct more usability research for the project and iterate on whatever current mockups we have.