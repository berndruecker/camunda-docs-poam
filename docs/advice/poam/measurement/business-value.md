---
title: Business Value
description: "..."
---

For almost any action taken in an organization it should be possible to point to its benefit, the contribution to the business outcome, or its business value for short. Process orchestration is no exception.

The typical challenge is, that while process orchestration delivers a lot of very clear and concrete technical advantages, is is often hard to tie this to concrete business outcomes. This is by the way very much connected to the general problem to show business value around software, pretty known to most IT managers or CIOs.

Let's elaborate. The main technical advantages of using a proven process orchestration platform are:

- **Reduced time to value**: The improved collaboration of business and IT via graphical, easy to comprehend, but directly executable models is very powerful. While this can lead to more discussions upfront, it means that chances are higher to build the right thing and reduce unecessery iterations or costly refactorings, saving a lot of time and development effort in the end. Due to an improved understandability of the solution, it is also easier to adjust it later on, enabling an incremental approach to further make sure to build the right things and course correct early on.
- **Time and effort savings**: The nature of long running processes requires certain functionality to be built in software, especially around state handling, escalation or monitoring. And as end-to-end processes typically need to integrate a lot of endpoints, there can be pre-built functionality around this. All of those features will save time and effort during development. A good process orchestration platform can further facilitate reuse within projects, for example by allowing to distribute reusable connectors, model snippets (think maker-checker), and more.
- **Allowing for continous improvement**: Visual process models make it easy to understand how a process is implemented and thus to design and implement possible changes. Process intelligence (e.g. Optimize) help to find or validate bottlenecks and assess changes afterwards.
- **Increased resilience, performance, and scalability**: Using a proven platform makes sure, certain hard problems around like state handling at scale or setting up geo-redundant data centers, are covered by the vendor and don't need to be solved within development teams. This not only saves immense efforts, but makes sure the solution runs well in production.

In a nutshell you could say, that with a process orchestration platform, you can develop a better software solution faster, with less problems in production.

This is a great value proposition and well appreciated by IT stakeholders like developers, architects, and IT managers. Still, it is under the cover of building a software solution and can be persceived as "just another" software engineering tool, which actually leaves a lot of strategic potential on the table.

So what you want to do, is to tie thise benefits to the strategic imperatives, all organizations have to some extend:

- **Customer experience**: This is around customer satisfaction (often measured as NPS), expansion revenue, retention rates or net new revenue
- **Operational excellence**: Get a good productivity ration, reduce expenses, increase employee satisfaction
- **Risk and compliance**: Be ready for audits, regulatory compliance,

An important exercise for every process orchestration project is to discover the real business outcomes, unlocked by the above technical advantages, and tie them to the strategic imperatives.

Business outcomes can be either generic:

- **Time savings**: Adding automation will generally reduce cycle times and avoid that instances are forgotten or dropped for any reason. This improves _operational excellence_.
- **Cost reduction**: Orchestrated processes allow to automate tasks within those processes removing manual work. Also the general coordination of processes does not need humans any more (which were sending around emails or spreadsheets before). More visibility can lead to insights to remove costly activities or focus them on a smaller number of cases. For example, a customer found, that they invoked a scoring service too early in a process for too many of those instances, leading to unnecessary fees about thousands of dollars per month, which was very easy to fix. This relates to _operational excellence_ as well.
- **Agility & scalability**: Having the orchestration process clearly described in its own artifact instead of burried in spagethi-integration code, enables you to make changes which were otherwise impossible, expensive, and risky. A good example are experiments with AI, that can be asily hooked into orchestrated processes, quickly and easily (relating _operational excellence_). Another examples are omnichannel customer experiences, that often require changes in core processes, which are hard to do in spaghetti (relating to _customer experience_).

Additionally to those generic metrics, there should be business process related metics that can be expressed, for example:

- **Dropped onboardings**: Due to slow onboarding of new customers, 32% of applicants dropped. By reducing those wait times, the drop-out rate could be reduced to 12%. This relates to _customer experience_.
- **Reduced fines**: In a regulated environment certain closing notifications must be sent within the same business day, which was a challenge for the spreadsheet and email based process. Regularly certain notes were delayed, leading to multiple million dollar fines per year. Introducing a process with strict deadline management and pro-active escalation could save those fines completly. This relates to _risk and compliance_.
- **Number of claims/employee**: In one scenario, an insurance wanted to extend their customer base, but without adding headcount. They focused to remove manual work so much, that they finally could handle more claims with the same staff. This relates _operational excellence_.

![poam-overview](assets/value-framework.png)

## Transform with EASE

- **Efficiency** // eliminate redundant work // risk mitigation
  - Measure: Risk mitigation through process observability (default risk, compliance, loss prevention, data quality)
  - Measure: Cost savings (Reduction in IT spend, Reduction in BU spend)
  - Measure: Time savings (time on-board new devs, removal of repetitive manual tasks, reuse)
  - Measure: Employee Satisfaction through better productivity (NPS or happiness)
- **Agility** // Business Agility including Change Management
  - Measure: Amount of changes and features to production in each cycle through faster development and collaboration
  - Measure: Opportunities identified through process observability
  - Measure: Savings or revenue through adaptability in production (ability to make changes in production through configuration)
- **Speed** // Faster time-to-initial-value
  - Measure: Time to MVP through business/developer collaboration and streamlined setup
  - Measure: Reduction of release cycle time through faster development and collaboration
- **Experience** // Our Customer’s Customer Experience
  - Measure: Customer Satisfaction (NPS, Survey, Engagement, Peer Reviews – how does your customer measure satisfaction)
  - Measure: Expansion Revenue (existing customer’s experience leads to additional spend or buying more goods/services)
  - Measure: Retention Rate (existing customer’s experience leads to improved retention)
  - Measure: Net New Revenue (new offerings are made available by automation or prospects are impressed and becomes customers faster through better experiences)
