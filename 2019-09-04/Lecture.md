---
title: An Introduction to Project Management
author: [Connor Baker]
date: Compiled on \today\ at \currenttime
subject: September 4, 2019 Lecture on GMU's CS 321
keywords: [GMU, Fall, 2019, CS, 321]
subtitle: GMU Fall 2019 CS 321
logo: images/GMU-CS-BLUE.png
logo-width: 273 # Size at which the logo is centered
lang: en
titlepage: true
titlepage-color: FFFFFF
titlepage-text-color: 0d47a1
titlepage-rule-color: 0d47a1
titlepage-rule-height: 2
papersize: letter
fontsize: 10pt
listings-disable-line-numbers: false
table-use-row-colors: true
footer-right: \thepage\ of \pageref{LastPage}
header-right: \today
header-includes:
 - \setcounter{page}{0} # So that the titlepage is the zeroth page
 - \usepackage{datetime}
 - \settimeformat{ampmtime}
 - \usepackage{lastpage}
---

## Review of Previous Class

### Software Development Life Cycle

The Software Development Life Cycle (SLDC) is independent of the process model used
  + However, the process model used influences the order an duration of the phases of the SLDC

SLDC is a set of 4-9 stages. We define them as

+ Specification
+ Design and implementation
+ Validation
+ Evolution

### Architecture and Design

Architecture is differentiated from Design by its lack of implementation details. In general:

+ Architecture is very high level and doesn't concern itself with the technologies used
  + Think blueprints and arrangement of components
+ Design begins to worry about implementation details like tooling
  + Thing class diagrams and CRC cards

### Verification and Validation

They're different
+ Verification refers to a solution's ability to conform to specifications and requirements
+ Validation refers to a solution's ability to appease the customer's expectations

### Types of Testing

+ Development or component testing
  + Unit testing
  + Coupling units together to create components
  + Testing the emergent behavior of the joined components
+ System testing
  + Generally black-box/smoke/stress/load testing
+ Acceptance testing
  + Customer and user work with the system and accept or reject it
  + Also provides an opportunity for the vendor to defend their work

### Operations and Maintenance

Why should we care about Operations and Maintenance (O&M)?

+ Very rarely does technical debt outweigh the cost of new software
+ About 80% of the budget goes to O&M

A note: usually, Maintenance and Evolution are used interchangeably. However, in practice, Maintenance usually refers to work done that does not involve an extensive rewrite. Anything that involves more work than adding a feature or providing bug-fixes is defined as Evolution.

## Software Project Management

When talking about Software Project Management (PM) we are largely concerned with the activities involved in ensuring that software is

+ delivered on time,
+ within budge, and
+ in accordance with the requirements of the organizations developing and procuring the software

We need PM because Software Development is always subject to budget and schedule constraints that are set by the organization developing the software.

## Success Criteria

+ Deliver the software to the customer within the agree time frame
+ Keep costs within budget
+ Deliver software which meets the customer's expectations
+ Maintain a coherent and high-functioning development team

## Factors Influencing Project Management

These factors mean that project managers in different organizations may work in very different ways.

+ Company size
+ Software customers
+ Software size
+ Software type
+ Organizational culture
+ Software development processes

## Management Activities

+ Project planning
+ Reporting
+ Risk management
+ Managing people
+ Writing proposals

## HealthCare.gov

A case study in poor management / development practices.

+ What were the issues surrounding HealthCare.gov?
  + While released on time, the product delivered was essentially non-functional.
+ How can we avoid them?
  + There are number of steps that could have been taken to avoid such a disastrous launch:
    + Have the right people in the room
    + Double down on Subject Matter Experts
    + Dog-food it to employees
    + Have a rolling release

## Managing People

We learned through the RSA Animate video that, perhaps surprisingly, money as a motivational tool cripples knowledge workers. Largely, there are three things which motivate knowledge workers:

+ Autonomy
+ Mastery
+ Purpose

## Top Five People Management Skills

1. Organizational
   + Coordination of tasks
   + Goal setting
   + Handling details
2. Management
   + Teaching
   + Leading
   + Executive decision making
3. Communication
   + Writing
   + Speaking
   + Listening
4. Interpersonal
   + Cooperation
   + Motivating others
   + Supporting others
5. Planning
   + Problem solving
   + Analyzing issues
   + Developing strategies
