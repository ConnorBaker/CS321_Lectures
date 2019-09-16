---
title: Designing for the User
author: [Connor Baker]
date: Compiled on \today\ at \currenttime
subject: September 16, 2019 Lecture on GMU's CS 321
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

+ How are Scrum and XP different?
  + Scrum is focused on management and workflow
  + XP is focused on rituals and practices surrounding programming
+ What are the stages of the Software Development Life Cycle?
  + Specification
  + Design and implementation
  + Validation
  + Evolution
+ Requirements
  + They strike a balance between features and security
  + Capture the expected functionality of the system
  + They address the "what"s levied at a system, not the "how"s
+ Agile really wanted to get away from waterfall
  + That included verbiage
  + That's why they use terms like "feature" instead of "requirement"

## Motivation

+ Limited short-term memory
+ People make mistakes
  + Don't penalize them for it
+ People are different
+ People have different interaction preferences

## Usability

### ISO Definition

Usability is

> the extent to which a system, product or service can be used by specified user to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use
> -- ISO 9241-11

Usability is about the quality of user experience which includes how easy it is to use and how useful that system is.

Usability includes:

+ Easy of learning
+ Efficiency
+ Errors
+ Memorability
+ Satisfaction

## Interaction Design

> The practice of designing interactive digital products, environments, systems, and services
> -- About face 3: The essentials of interaction design, Cooper, Reimann, Cronin, 2007

It is **not** software design. Developing a user interface involves:

+ Interaction component
  + How a user interface works, its "look and feel" and its behavior in response to what a user hears, sees, and does
+ Interface software component
  + Code which implements the interaction component

## Design Issues

+ Two problems must be addressed in the interactive systems design
  + How should information from the user be provided to the computer system?
  + How should information from the computer system be presented to the user?
+ A coherent user interface must integrate user interaction and information presentation

## Design Principles

#### User familiarity

The interface should use terms and concepts which are drawn from the experience of the people who will make most use of the system.

#### Consistency

The interface should be consistent in that, wherever possible, comparable operations should be activated in the same way.

#### Minimal surprise

Users should never be surprised by the behavior of a system.

#### Recoverability

The interface should include mechanisms to allow users to recover from errors.

#### User guidance

The interface should provide meaningful feedback when errors occur and provide context-sensitive user help facilities.

#### User diversity

The interface should provide appropriate interaction facilities for different types of system user.

## Error Messages

Error message design is critically important. Poor error messages can mean that a user rejects rather than accepts a system.

Messages should be polite, concise, consistent, and constructive.

The background and experience of users should be the determining factor in message design.

## Interaction Design Process

+ Interaction design is an iterative process involving close liaisons between users and designers.

The three core activities in this process are:

+ User analysis
  + Understand what the users will do with the system
+ System prototyping
  + Develop a series of prototypes for experiment
+ Interface evaluation
  + Experiment with these prototypes and users

## Ethnography

+ Involves an external observer watching users at work and questioning them in an unscripted way about their work
+ Valuable because many user tasks are intuitive and they find these very difficult to describe and explain
+ Helps to understand the role of social and organizational influences on their work

## User Interface Prototyping

+ The aim of prototyping is to allow users to gain direct experience with the interface
+ Without such direct experience, it is impossible to judge the usability of an interface
+ Prototyping may be a two-stage process:
  + Early in the process, paper prototypes may be used;
  + The design is then refined and increasingly sophisticated automated prototypes are then developed

## Interface Evaluation

Interface evaluation is the process of assessing the usability of an interface and checking that it meets user requirements.

Simple Evaluation Techniques:

+ Questionnaires for user feedback
+ Video recording of system use and subsequent tape evaluation
+ Instrumentation of code to collect information about facility use and user errors
+ The provision of code in the software to collect on-line user feedback

## Other Resources

+ About face 3: The essentials of interaction design, Cooper, Reimann, Cronin, 2007 [Available on Safari Books Online through GMU Library: <https://proquest.safaribooksonline.com/book/web-design-and-development/9780470084113>]
+ <https://www.nngroup.com/articles/>
+ <https://www.youtube.com/watch?v=yY96hTb8WgI>
