---
title: "We need to talk about data ethics, Australia"
layout: post
date: 2017-01-11 12:00
image: false
headerImage: true
tag:
- ethics
blog: true
hidden: false
author: ellenbroad
description: Reflecting on emerging data ethics debates around the world, in light of recent Centrelink data matching developments in Australia
---

Over Christmas I went offline and caught up on some reading.

One of the books on my reading pile was [Weapons of Math Destruction, by Cathy O’Neil](https://www.amazon.com/Weapons-Math-Destruction-Increases-Inequality/dp/0553418815 "Buy Weapons of Math Destruction by Cathy O Neil"). O’Neil, a mathematician turned quant turned data scientist, writes about the bad data models increasingly being used to make decisions that affect our lives.

It was while I was reading Weapons of Math Destruction that news emerged of issues with Centrelink’s automated data matching program in Australia.  

![Centrelink Australia](/assets/images/centrelink.jpeg)
<figcaption class="caption">Photo by Tracey Neamy AAP</figcaption>


In 2016 the Department for Human Services [automated its processes for matching welfare recipients’ reported income](http://www.abc.net.au/news/2017-01-04/centrelink-debt-recovery-system-designed-by-dunderhead-wilkie/8160990 “debt recovery system not working”), as part of government efforts to reduce overpayments to welfare recipients and recover debt.

Since July last year the automated system has produced around 169,000 debt notices, of which one in five have been confirmed to have been sent in error. News broke over Christmas and into early January this year of people receiving erroneous debt notices, for amounts sometimes in the thousands of dollars.

Reading Weapons of Math Destruction as the Centrelink stories emerged has me thinking about how we identify ‘bad’ data models, what ‘bad’ means, and how we mitigate unfairness - stress, damage, errors and inaccuracies - to the people they affect.

In this blog, I ask what role data ethics might play in the design of data models which stand to impact on peoples' lives.

I haven’t seen ethics come up yet in the context of Centrelink data developments, which has surprised me. How could taking an ethics-based approach to data projects help to mitigate harm? What ethical frameworks exist for government departments in Australia undertaking data projects like this?

## Weapons of Math Destruction
There are different ways in which a data model can be ‘bad’. It might be overly simplistic. It might be based on limited, inaccurate or old data. Its design might incorporate human bias, reinforcing existing stereotypes and skewing outcomes.

A simply bad data model spirals into a weapon of math destruction when it’s used en masse, is difficult to question and damages people's lives. O’Neil’s book is dedicated to examples of weapons of math destruction in banking, education, employment, the justice system and more. Peter Martin summarises O’Neil’s book in his article [here](http://www.smh.com.au/comment/how-centrelink-unleashed-a-weapon-of-math-destruction-20170105-gtmsnz.html “Centrelink unleashes weapon of math destruction”).

To some extent, we’re all exposed to data models making assumptions about us - targeting ads to us online, assessing our insurance premiums and our polling preferences.

But weapons of math destruction tend to hurt vulnerable people most. They might build on existing biases (e.g. [because you are black](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) you are more likely to reoffend, or [because you have a bad credit rating you will be more likely to have car accidents](http://www.consumerreports.org/cro/car-insurance/credit-scores-affect-auto-insurance-rates/index.htm “credit scores affect car insurance”)). Errors in the model might have starker consequences for people without a social safety net. And some people are likely to find it harder to question and challenge the data model making decisions about them.  

O’Neil’s book shows how bad data models can become weapons of math destruction. It doesn’t spend much time, though, on ways in which these weapons of math destruction can be prevented and mitigated.

Data matching and data-driven decision making is only going to increase over time. Centrelink isn’t alone in moving to automate processes, and recovering debt is a perfectly legitimate government objective. (In the UK, the May government is close to introducing a [new data sharing power](http://www.publications.parliament.uk/pa/bills/lbill/2016-2017/0080/lbill_2016-20170080_en_1.htm “Digital economy bill”) for recovering debt owed to the public sector as part of the Digital Economy Bill).  

The premise of a data model may not be ‘bad’; but issues can arise in how it is designed, its capacity for error and bias, and how badly people could be impacted by that error or bias.

## Helping organisations make good data-driven decisions
We need more ways to help data scientists and policymakers navigate the complexities of data projects that involve personal data, and which can impact on people's’ lives. Regulation has a role to play. Data protection laws are being reviewed and updated around the world (in Australia, the [draft Productivity Commission report on data sharing and use](https://medium.com/@ellenbroad/early-thoughts-on-the-australian-productivity-commissions-draft-data-sharing-report-c77637ca0fa5 “early thoughts on productivity commission data sharing report”) recommends the introduction of new ‘consumer rights’ over their personal data). And bodies like the Office of the Information Commissioner help organisations understand if they’re treating personal data in compliance with personal data principles, and promote best practice.

Guidelines are also being produced to help organisations be more transparent and accountable in how they use data to make decisions. The Open Data Institute in the UK has developed [openness principles for organisations managing personal data](https://theodi.org/guides/openness-principles-for-organisations-handling-personal-data “open data institute openness principles”), designed to build trust in how that data is stored and used. Algorithmic transparency is being contemplated as part of the EU Free Flow of Data Initiative, and has become a [focus of academic study](https://theconversation.com/we-need-to-know-the-algorithms-the-government-uses-to-make-important-decisions-about-us-57869 “we need to know about algorithms the government uses for decisions”) in the US.

**But a data project can be legal, its processes transparent and accountable, and still be a ‘bad’ data model.**

There could be known errors in a model that, if left unaddressed, cause real harm to people. An organisation's normal appeal processes might not be accessible or suitable for certain people who could be harmed by a model, e.g. the elderly, infirm, and those with limited literacy.  It could be a data model within a sensitive policy area, where a higher duty of care exists to ensure data models do not reflect bias.  

Ethics can help to bridge the gap between compliance and evolving societal expectations of what ‘fair’ and reasonable data usage is. In Weapons of Math Destruction, Cathy O’Neil describes data models as “opinions put down in maths”. Taking an ethics-based approach to data-driven decision making helps us confront those ‘opinions’ head on.

## Data ethics frameworks are gaining traction. Australia needs to get on board.
Last year the UK Government accepted a [recommendation](http://www.computerweekly.com/news/4500272963/House-of-Commons-Science-and-Technology-Committee-calls-for-Data-Ethics-Council “calls for a data ethics council”) of the House of Commons Science & Technology Committee that a Council of Data Ethics be established. The UK’s Alan Turing Institute, founded by government to lead on data science, is expected to house the Council of Data Ethics and has begun [exploring data ethics in earnest](https://www.turing.ac.uk/events/the-ethics-of-data-science-the-landscape-for-the-alan-turing-institute/ “event on the ethics of data science”).

The Cabinet Office released its first iteration of a [Data Science Ethical Framework for Government](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/524298/Data_science_ethics_framework_v1.0_for_publication__1_.pdf) in May 2016. And around the same time in the US, the White House published its [report on big data, civil rights and ethics](https://www.whitehouse.gov/blog/2016/05/04/big-risks-big-opportunities-intersection-big-data-and-civil-rights).

In the research and statistics professions, varying codes of ethics relating to data and information already exist. The Australian National Data Service has published [ethics, consent and data sharing guidance for researchers](http://www.ands.org.au/guides/ethics-consent-and-data-sharing “guide for researchers on data sharing, consent and ethics”).

But data ethics doesn’t seem to have yet found its way into Australian government policy debates. There’s no ethical framework per se for government data projects, or an ethics council or committee to review potential high impact data projects.

Not all data projects require ethical review. And it's important to note that ethics can encompass more than compliance with data protection principles and licence terms of use.

A data project might be tagged as ‘high impact’, and its model design subject to ethical review, if it stands to directly impact on more than x percent of the population. And by ‘directly’, I mean alter their day-to-day life.

Ethics frameworks can help us to put a data model in context and assess its relative strengths and weaknesses. Ethics can bring to the forefront how **people** might be affected by design choices made in the course of building a data model.

An ethics-based approach to data-driven decision making might have data science teams not only ask questions like,

* are we **compliant** with the relevant laws and regulation?
* do **people understand** how a decision is being made?
* do they have **some control** over how their data is used?
* do they have **mechanisms to appeal** a decision made?

But also

* in this context, **who** will be affected by the data model?
* can the **people affected make use of those appeal mechanisms**?
* have we taken steps to ensure as much as possible that **errors, inaccuracies, bias in our data model have been removed**?
* what **scale of impact** could potential errors or inaccuracies have on people **if included in the model**? What is an acceptable margin of error?
* have we clearly defined how this model will be used, and what **decisions it can and can’t support**?

What is the 'duty of care' of a data scientist? Is 'duty of care' a concept that is readily applicable in data science? What would a data scientist's 'duty of care' consist of?

There’s no baseline of debate right now to help us understand the parameters of reasonable and acceptable data model design. What's considered ‘ethical’ changes over time, as we change, as technologies evolve and new opportunities (and consequences) emerge.

Ethics is messy and hard to pin down, which is why it can seem counterproductive to people who work with data every day.  But I think a data ethics debate is worth having.

Bringing data ethics into data science reminds us that we’re human, that our data models reflect design choices we make, and which have the potential to affect peoples’ lives - in good and bad ways.
