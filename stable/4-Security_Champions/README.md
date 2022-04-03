---
  
layout: col-document
title: OWASP Security Culture
tags:

---
{% include breadcrumb.html %}
# Security Champions

It can be hard to introduce security across the development team using
the security team alone. Information Security people do not scale across
teams of developers. A good way to scale security and distribute
security across the development teams is by using Security Champions.

Security Champions act as a single point of contact in regards to
security for their team. The Security Champion is in contact with a
member of the security team to ask for guidance. The Security Champion
can monitor security best practices, and help the security team run and
promote security uplift activities such as a CTF (Capture the Flag)
event.

Security Champions help to improve the communication between the
development teams and the security team. A Security Champion will know
the pain points of their teammates\' code bases and culture, they are
then in a good position to present security in a way that directly
connects with them. Security Champions are a key element of improving
application security maturity as referenced in maturity frameworks such
as [OWASP SAMM](https://owaspsamm.org/model/governance/education-and-guidance/stream-b/).

It is important to have management buyin for the implementation of the
Security Champions program. A Security Champion will need to have a
percentage of time set aside from their regular position to spend on
fulfilling this new role. A Security Champion will dedicate time to
security initiatives, such that they have less time to spend on
development. This time spent on security is worthwhile when weighed
against the cost of not spending time on security, resulting in costly
security issues to fix. When planning on implementing a Security
Champions program, it may be beneficial to start with a proof of concept
consisting of one or two Security Champions. When the program has been
proven successful it can be rolled out across all development teams.

A large organisation that has a mature Security Champions program may
next look towards establishing a [Community of
Practice](https://www.mitre.org/publications/systems-engineering-guide/enterprise-engineering/enterprise-governance/communities-of-interest-andor-community-of-practice)
for security.

The following section will describe the steps defined in the [OWASP
Security Champions Playbook](https://github.com/c0rdis/security-champions-playbook)

### 1. Identify teams

Identify the teams involved that you want to add Security Champions to
and how they work.

**Identify team structure:** In the initial step, the organisational
structure is mapped to understand the teams that will be involved
and their structure. For example, a team may consist of 5 engineers,
1 product owner, 1 QA and 1 team lead.

**Identify technologies used:** Identify what technologies are used in
each team, such as programming language and framework.

**Identify current security state:** understand the existing security
posture, so as to establish a baseline to use to measure
improvement. This could describe any code reviews that are performed
or automated security testing implemented.

**Identify processes:** Identify any existing communication channels,
and what process is used to report a security issue and assign it to
a team member.

### 2. Define the role

Define the developer participation requirements as a Security Champion,
and clearly define the role. The responsibilities for a Security
Champion depend on what the organisation\'s application security goals
are and what the security team would like to embed into the Security
Champion program. Refer to the identified current security state and
detail what you would like to improve.

The Security Champion role may include:

**Evangelise security:** promoting security best practice in their team,
imparting security knowledge and helping to uplift security awareness
in their team

**Contribute to security standards:** provide input into organisational
security standards and procedures

**Help run activities:** promote and run activities such as Capture the
Flag (CTF) events, see [Activities chapter](../5-Activities/index.md#activities)

**Conduct threat modelling:** threat modelling consists of a security
review on a product in the design phase, see [Threat modelling chapter](../6-Threat_Modelling/index.md#threat-modelling)

**Perform [secure code
reviews](https://owasp.org/www-project-code-review-guide/):** raise
issues of risk in the code base

**Use security testing tools:** conduct or verify automated security
scanning and provide support to their team for the use of security
testing tools, see [Security testing chapter](../7-Security_Testing/index.md#security-testing)

See examples of what roles can contain at [Security Champions session,
OWASP summit
2017](https://github.com/OWASP/owasp-summit-2017/blob/master/Outcomes/Security-Champions/Security-Champions.md).

### 3. Nominate Champions

A Security Champion may be a developer, operations or QA role. Security
Champions should be nominated, rather than assigned.

**Management buyin:** get agreement from management on the defined role
responsibilities and time commitment of a Security Champion, such as
20% of their role.

**Scale:** 1 security staff member may support 5 Security Champions, who
each support their team.

**Assign to relevant team:** It is useful to add Security Champions by
technology platform, so that their specific technical skills can be
used. For example, frontend; backend; mobile.

**Converse with team manager and nominated team member:** discuss with
the team manager about possible Security Champion candidates.
Nominations may come from the team manager as well as having a call
for interested candidates. Then discuss with the candidates about
the role and its benefits to see if they are a good fit. Discuss the
benefits of learning application security and how it can help their
career and stand out.

**Present the Security Champions to the organisation:** once the
champions have been nominated, communicate the Security Champion
program and its members to the organisation.

### 4. Set up communication channels

Establish a communication channel for all Security Champion members and
their security team contact and organise periodic meetings.

**Establish communication channel:** create a communication channel that
the Security Champions and their security contact can use. This can
be whatever is appropriate for the organisation, such as a messaging
chat application channel or email group.

**Organise periodic meetings:** periodic meetings are useful to discuss
with the Security Champions on any issues they are having, and
adjust goals as needed.

### 5. Build solid knowledge base

Establishing a knowledge base can help to have a single place to refer
to for application security guidance.

A knowledge base may contain:

**Organisation\'s security policy and procedures:** links to relevant
    application security procedures such as the password policy, which
    cryptographic algorithms to use, and secure development procedures
    like how to conduct a code review or a particular library to use to
    escape output.

**Reference material:** useful external reference material can include [OWASP Code Review
    Guide](https://owasp.org/www-project-code-review-guide/) and [OWASP Cheat Sheets](https://owasp.org/www-project-cheat-sheets/).
    Security checklists can also be useful, such as [OWASP Top
    Ten](https://owasp.org/www-project-top-ten/) and [OWASP
    Application Security Verification Standard
    (ASVS)](https://owasp.org/www-project-application-security-verification-standard/).

Creating a training program for Security Champions is also useful for
building knowledge and skills in application security. The training
format can range from references in the knowledge base to hands on labs.
A training program can consist of different levels, each building on the
previous one. Initial levels can contain broad security topics and
expand out to specific platforms, such as mobile security.

### 6. Maintain interest

Keep the Security Champions motivated and engaged to ensure they can
continue to enthusiastically promote security in their assigned team.
Use activities such as Capture the Flag events to promote security.
Recognise the work done by Security Champions and communicate their
achievements to the wider organisation.

**Activities:** Security Champions can attend conferences together and a
conference calendar can be created that contains relevant upcoming
conferences. Security Champions can organise events such as Capture
the Flag (CTF) and hackathons. Gamification can be used to help
drive engagement - such as the use of a scoreboard during a CTF
event, and the awarding of prizes like branded clothing or stickers.
See [Activities chapter](../5-Activities/index.md#activities).

**Recognise and reward:** It is important to recognise the achievements
by the Security Champions, such as providing updates on progress in
regular newsletters. Gamification can be used to indicate progress
for the Security Champion, through the use of levels. This can help
the Security Champion to have something to work towards and mark
their success in their security journey. An organisation may
formalise a Security Champion position with their HR department to
help motivate individuals to join.

**Measure progress:** Security Champions can have goals to achieve, such
as security Objectives and Key Results (OKR). For example, to close
a percentage of critical and high vulnerabilities; conduct a certain
number of threat modelling activities; complete security training
modules. Defined maturity levels can be used to mark progress of
individual Security Champions and the overall program. For example 
[OWASP Top 10 Maturity Categories for Security
Champions](https://github.com/cvlucian/owasp_top_10_maturity_categories_for_security_champions).