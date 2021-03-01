# Copilot Evolution Project
This ideation challenge is part of a project code-named: copilot evolution. 

# Challenge Summary
Topcoder wants to evolve the role of copilots from its current form with fixed payments and no growth path, into a role with flexible payments and multiple growth paths. They want a copilot that acquires additional skills or displays capacity to assume additional responsibilities, to be rewarded accordingly, with a more senior role and accompanying compensation that is commensurate with their contribution to the platform. 

The evolution will make the role of copilots within the Topcoder community bear a lot of similarities to more conventional roles outside of Topcoder (i.e. salaried positions), but there will be a number of differences, due to the pecularities of the Topcoder platform. There is the expectation that at the end of the evolution effort, Topcoder will be able to use conventional job adverts to hire people into the copilot role.

# Challenge Introduction
To increase the chances of success for the evolution effort, Topcoder is exploring two different approaches.

The first approach is being explored via a separate challenge [Topcoder Copilot Evolution Ideation Challenge Series Part 1 - Hierarchical levels](https://www.topcoder.com/challenges/cf15e634-251d-48cb-bf92-8b72e66c9246) that asks members to offer proposals based on a grade-based or hierarchical system with 5 levels. In this approach, a newcomer to the copilot role would start from level 1 and slowly work their way up to level 5.

The second approach, which will be explored in this challenge, will explore the use of a skill-based framework.

# Challenge Objective
Using a skill-based framework, we would like you to generate ideas and prepare a proposal that can be used to evolve the copilot role.

To properly understand what this evolution project is about, it is important to review what role copilots currently play at Topcoder, and contrast it with what is obtainable in the technology industry. Please refer to sections 1.0 - 3.0 below.

# Challenge Requirements
The [first challenge](https://www.topcoder.com/challenges/cf15e634-251d-48cb-bf92-8b72e66c9246) mentions a tentative system with 5 levels, with the entry level being level 1 (Junior Copilot) and the final level being level 5, where the role title will either be a Project Manager or a Technical Architect:
- Junior Copilot
- Medior Copilot
- Senior Copilot
- Lead Copilot
- Architect / Project Manager

In this challenge, we want you to group copilot skills into meaningful buckets, then map each skill to an appropriate role, for example:

Management skills:
- Management Level 1: Proven Skills X Y Z
- Management Level 2: Proven Skills P Q R
- Management Level 3: Proven Skills A B C

Technical skills:
- Technical Level 1: Topcoder Rating X
- Technical Level 2: Topcoder Rating Y
- Technical Level 3: Topcoder Rating Z

Non-technical skills:
- Non-technical Level 1: Design Criteria J
- Non-technical Level 2: Design Criteria K
- Non-technical Level 3: Design Criteria L
 
The idea here is that, instead of moving between levels directly (i.e. in a sequence) you would determine the minimum set of skills required to attain a role.
 
In other words, you would be creating a system that maps a minimum set of skills necessary to qualify for each role:
- Junior Copilot - Technical Level 1
- Medior Copilot - Technical Level 1 + Management Level 1 + ... + Level 1
- Senior Copilot - (Technical Level 1 + Management Level 2) or (Technical Level 2 + Management Level 1) + ... + Level 1 + Level 2
- Lead Copilot - Technical Level 2 + Management Level 2 + etc Level 2 or etc Level 2
- Project Manager - Technical Level 2 + Management Level 3 + etc…
- Architect - Technical Level 3 + Management Level 2 + etc
 
So, different combinations can be used to climb the scale of responsibility and remuneration.

# Challenge Deliverables
We are looking for innovative ideas! We expect to receive a lot of submissions in this challenge, so it is important to structure your ideas so they are clear and easy to understand. In your proposal, please be sure to follow the format suggested below:

* Title: A short and clear title for your proposal
* Abstract: High-level overview of your proposal in one or two sentences
* Details: The proposal itself. Diagrams and sketches or even clickable prototypes that will better explain your proposal are encouraged.

Please submit your proposal in MS Word, PDF, HTML, or Markdown format.
If you create any diagrams, please sure to include the original source files (in Adobe PS, AI, XD, Sketch, Figma, etc).




## 1.0. Background
The role that is currently referred to as a "copilot" within the Topcoder community, is roughly equivalent to the "technical lead" or "tech lead" (or sometimes "dev lead") designation used in the technology industry.

### 1.1. What is a tech lead?
Indeed [1], a job site with over 250 million unique visitors every month, defines [1b] a technical lead as:

> A technical lead is a professional who oversees a team of technical personnel at a software or technology company. They often lead software development or software engineering teams and troubleshoot technical issues that involve software development, engineering tasks and product releases.

> A technical lead needs to have a great deal of professional experience in software development and a deep understanding of technology, but they should also be personable and capable enough to effectively lead a team and collaborate with others.

Now that we have an idea of what a tech lead is, we need to situate their role in the context of an organization with several members. In other words, even though tech leads often work with developers, they usually have to collaborate with other roles like engineering managers, project managers etc.

### 1.2. Where does a tech lead function?
The [Engineering Ladders](http://www.engineeringladders.com/) website, which is open source and maintained on GitHub, contains a framework that will help us properly contextualize the role of a tech lead in a large organization. They introduce the concept of a [career ladder](https://github.com/jorgef/engineeringladders/blob/539288966a16019f894b05b024db2ab6eaa310fe/README.md#career-ladders) consisting of four (4) rungs:

* _Developer: role also known as programmer or software engineer, requires a deep level of technical expertise_
* _Tech Lead: role also known as dev lead, is the owner of the system and requires a unique balance between hands-on development, architecture knowledge and production support_
* _Technical Program Manager: role responsible for coordinating and driving to completion initiatives that expand multiple teams_
* _Engineering Manager: role also known as dev manager, is responsible for the consistent delivery, career growth and level of happiness of the team_

### 1.3. What separates a tech lead from an engineering manager?
In small organizations, the same person might perform the role of a tech lead and engineering manager, but this is often impractical in large organizations like Topcoder. 
They offer the following explanation that clearly distinguishes a tech lead from an engineering manager in large organizations [2]:

_It is very common for companies to mix the Tech Lead and Engineering Manager roles. Although both roles have some overlap, their focus is different: the Tech Lead is in charge of the System while the Engineering Manager is in charge of the People._

Now that we understand that tech leads focus more on technology than people, while engineering managers focus more on people than technology, let's turn our sights to the Topcoder community and the role of tech leads within it.

### 1.4. How do Topcoder tech leads differ from the norm?
To properly understand the role of tech leads within the Topcoder community, let's quickly go on a detour of the Topcoder platform, which the community is built upon.


## 2.0. Topcoder Platform
Topcoder was founded in 2001 by Jack Hughes and it was premised on a fairly simple idea: the design, development and delivery of (complex) software "through online tournaments" [3]. The only repeatable way for Topcoder to deliver on this promise of using tournaments to develop software is by cultivating a _diverse_ community around their business. 

In other words, one of the factors that makes a tournament interesting is that it is a huge magnet for drawing in a diverse set of participants. People take part in tournaments not just for the prize money alone, they compete because tournaments afford them the opportunity to benchmark their skills against other people that are:
- less skilled than they are or;
- about as skilled as they are or; 
- more skilled than they are. 

## 2.1. Tournaments
Tournaments afford participants (and its organizers) access to a diverse pool of fellow participants, colloquially referred to as "the crowd". 
"Crowds" that exhibit this trait i.e. the relative differences between competing individuals is very uneven, are hard to recreate in a traditional workplace. 

Although this model of using "crowds" to accomplish challenging tasks is now what is widely known as "crowd-sourcing" today, the underlying concept has been studied extensively by economists, starting with a 1981 paper titled: Rank-Order Tournaments as Optimum Labor Contracts [4a]. It is known as Tournament theory [4b] in personnel economics and below is an excerpt from its Wikipedia entry: 

> Tournament theory is the theory in personnel economics used to describe certain situations where wage differences are based not on marginal productivity but instead upon relative differences between the individuals.

The Wikipedia entry offers us [pros and cons](https://en.wikipedia.org/wiki/Tournament_theory#Pros_and_Cons_of_Workplace_Tournaments) that should be familiar to anyone who has spent a considerable amount of time participating in Topcoder challenges:

* Pro - Incentivizing Performance: Tournaments can be very powerful at incentivising performance. Empirical research in economics and managements have shown that tournament-like incentive structure increases the individual performance or workers and managers in the workplace.
* Pro - Matching workers and jobs: Tournaments play an important function in matching workers with jobs that are relevant/appropriate. The theoretical prediction in the literature is that higher-skilled individuals would be sorted into jobs that offer higher potential returns.
* Con - Inequalities in the workplace: Tournaments have the potential to create large inequalities in payoffs. Incentive based tournaments are organised in such a way that some winners are created at the expense of many losers. Thus, by design there are likely to be high inequalities in payoffs in the workplace under a tournament structure. 
* Con - Selfish and Unethical Behaviour: A major issue with tournaments is that individuals are incentivised to view others as competitors, thus encouraging selfish behaviour. This means that participants in a tournament structured workplace would be less likely to help each other and are discourage from knowledge sharing more so than in other incentive schemes. Further, tournaments may also encourage unethical behaviour in participants such as cheating or collusion in competitive sports or plagiarism in the academic field. 


The pros succinctly summarize people's motivations for taking part in challenges, which we have already been covered above. We will go over the cons in a bit more detail. 

### 2.1.1. Con: Inequalities in the workplace
Members that compete in Topcoder challenges are not full-time employees (FTEs) of Topcoder. This important distinction means that the issue of workplace inequality is non-existent, therefore, this con doesn't really apply to Topcoder because their business model relies on independent contractors, rather than FTEs.

### 2.1.2. Con: Selfish and Unethical Behaviour
Topcoder uses a mechanism called "community member roles" [7] to mitigiate the effects of selfish and unethical behaviour. To maintain the integrity of challenges, Topcoder relies on pool of trusted members, selected from its large community to administer the *publicly visible* aspects of all challenges run on the platform. 

To be selected as a community member, a member must demonstrate a good understanding of how the Topcoder platform works, and must not have any history of unprofessional conduct that carries the penalty of a (permanent) ban. To determine whether a member meets the first quality, Topcoder uses a proxy that it calls "qualification requirements" or "eligibility requirements". 

## 2.2. Qualification Requirements
Topcoder community member roles fall into two broad categories:
* a reviewier [5][6] and;
* a copilot [5][6] (Topcoder's patents use the term "facilitator");

so a consequence of this is that, Topcoder maintains two kinds of eligibility requirements documents, one for each role:
* [Reviewer Qualification Requirements](https://www.topcoder.com/thrive/articles/Reviewer%20Qualification%20Requirements);
* [Copilot Eligibility Requirements](https://topcoderinc.github.io/Corona2/topcoder/copilotsResponsiblites/#eligibility-requirements); 

but you will only be reviewing the eligibility requirements for copilots in this challenge.

## 2.3. Training Requirements
To ensure that trusted community members stay current with the latest processes/rules etc on the platform, Topcoder maintains another document called the [Copilot & Reviewer Certification Program](https://www.topcoder.com/thrive/articles/Copilot%20&%20Reviewer%20Certification%20Program), where new and existing community members can update their knowledge of the platform.

The document can be broadly grouped into three (3) sections:
* an Eligibility Requirements section - listing the minimum criteria that must be met to become a Development, Design or Data Science copilot;
* a Training Program section - that will link to a unique set of training materials necessary to become a copilot, or to remain in good standing;
* a Certification Program section - to provide clear expectations of the [roles and responsibilities](https://www.topcoder.com/thrive/articles/Copilot%20Playbook) of a copilot.


## 3.0. Additional Reading
1. [Indeed](https://www.indeed.com/)

1b. https://www.indeed.com/career-advice/finding-a-job/technical-lead

2. http://www.engineeringladders.com/TechLead-EngineeringManager.html 

3. Lakhani, Karim R., David A. Garvin, and Eric Lonstein. "[TopCoder (A): Developing Software through Crowdsourcing.](https://www.hbs.edu/faculty/Pages/item.aspx?num=38356 )" Harvard Business School Case 610-032, January 2010. (Revised May 2012.)

4a. [Rank-Order Tournaments as Optimum Labor Contracts](http://faculty.smu.edu/Millimet/classes/eco7321/papers/lazear%20rosen%201981.pdf)

4b. [Tournament theory](https://en.wikipedia.org/wiki/Tournament_theory)

5. Topcoder development track patent: [Systems and methods for software development](https://patents.justia.com/patent/7778866), Jan 14, 2005 - Topcoder, Inc. 

6. Topcoder design track patent: [Systems and methods for graphic design development](https://patents.justia.com/patent/8209238), Jun 23, 2010 - TopCoder, Inc. 

7. In this Topcoder patent, "community member" was termed "contest administrator": [Systems and methods for screening submissions in production competitions](https://patents.justia.com/patent/10783458), May 1, 2006 - TopCoder, Inc. 
