---
marp: true
title: MVP & User Stories
paginate: true
---

<!-- _paginate: false -->

# 🚀 MVP & User Stories

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

<!-- _paginate: false -->

# 🚀 MVP - Minimal Viable Product

---

MVP is the first iteration of your app that is complete in itself.

Most minimal app you can create that follows your idea.

<!-- What is the smallest app that is still useful to the customers -->
<!-- ideally the most important / worthwhile feature -->

---

> the minimum viable product is that version of a new product which allows a team to collect the maximum amount of validated learning about customers with the least effort.
*- Eric Ries*

<!-- http://www.startuplessonslearned.com/2009/08/minimum-viable-product-guide.html -->
<!-- https://www.agilealliance.org/glossary/mvp -->

---
# MVP: Focus

- Reduce your ideas to a MVP solution!
- Ask yourself: What is really important?
- Examples:
  - Styles? It works with minimal styling!
  - Routing? Everything can be on one page!
  - Database? Maybe state or localstorage is enough!
  - Login? Maybe it works for a single user!
  - Images? Most likely not extremely important!

<!-- what is the MOST important? -->
<!-- for the customer -->

---

# MVP: Goal

- Create a working app
- With the most important feature(s)
- From here on:
  - always have a running app
  - build small self-contained features (increments) on top to improve

<!-- you should _always_ have a running app on *main* -->

---

# MVP: Completeness

When MVP is reached, your app is complete.

- No preparing for future implementation
- No placeholders for future ideas
- No empty pages

<!-- no dangling buttons or features -->
<!-- no optimizations or wrong abstractions -->

---

<!-- _paginate: false -->

# 🚀 User Stories

---

# User stories are for everyone

- They are preparation, planning and documentation
- All information about a feature should be there (or linked)
  - Everything should be understood by the Development Team
- Use the language of your customers (Ubiquitous Language)
- No technical details
  - Only use technical terms in the `Tasks` section
- The reason should never be *because it's possible*.

<!-- we want to communicate primarily what our customers needs are -->
<!-- avoid tautology -->

---

# Structure: Title

- Short and precise
- More of a reminder what it is about

---

# Structure: Value proposition

- As a `<ROLE>`
- I want to `<ACTIVITY>`
- So that `<DESIRED GOAL>`

<!-- ROLE: User, Author, or as Persona -->
<!-- ACTIVITY: how do we get there -->
<!-- DESIRED GOAL: what is the actual goal that they want to achieve -->
<!-- do the goals align with the activity? -->
<!-- is there a better way? -->

---

# Structure: Description

- Scribble / Mockups / Wireframes / Design or Textdescription
- precise, no unnecessary information

<!-- dont write prose -->
<!-- the team needs a common understanding that they keep in mind during implementation -->
<!-- some tasks are beyyer left open and undefined, because a mature team knows the domain and tech -->

---

# Structure: Acceptance criteria

Describe every scenario in detail (Customer Journeys)

- Describe all possible user interactions
- Describe all possible states
- Describe all eventualities
- Describe all(?) possible errors

<!-- ideally usually not complete -->
<!-- team has understanding of the problem -->
<!-- the more mature the less need for completeness -->
<!-- can also include technical acceptance criteria -->
<!-- often basis for e2e tests -->
<!-- Akzeptanzkriterien können beispielsweise gesetzliche Anforderungen, technische Anforderungen und Normen, funktionelle Anforderungen, Sicherheitsanforderungen oder auch ästhetische Anforderungen (z. B. Corporate Design) abbilden. -->

---

# Structure: Tasks

Technical explanations: by developers - for developers

- List the tasks that need to be performend within the dev team
- Checkboxes: try to check as you work on it
  - List Components
  - Storybook, Tests
  - Add to app, Global styles

<!-- usually identified during sprint planning -->
<!-- not a concern of the product owner, but of the dev team -->

---

# Complexity Estimation

- Complexity is more important to measure than time
- Relative values assigned in comparison to the "average work complexity" 
- T-Shirt sizes:
  - XS, S, M, L, XL

<!-- arbitrary values, often fibbonaci -->
<!-- no absolute value -->
<!-- only applicable to the team -->
<!-- changes over time -->
<!-- changes depending on team composition -->

---

# Writing good User Stories

- As slim as possible!
- Whenever you can cut something out
  - Do it!
  - Write another User Story
- Testable
  - Write tests for all `Acceptance Criteria`

<!-- maybe strive to achieve the goal of good test coverage -->

---

# Your first User Stories

- Name the most important features of your app
- Sort them by priority
- Pulled in order of Backlog

<!-- Priority: customer value + complexity -->
<!-- Product owner decides order -->
<!-- product backlog vs sprint backlog -->

---

# Examples

- Display important details of a single product
- List products
- Add product
- See details of a category
- List categories
- Create a category
- Display categories per product

<!-- not all features can be completely independent, still cut them as small and isolated as possible -->

---

# User Stories at the bootcamp

- Learn how to work with user stories
- Slack Channel `#user-stories`
  - Post all your stories here
  - Get approval _before_ you start working

<!-- The first sprint / week we plan together -->

---

# Repo & Project Board in Github

- Create a repo for your capstone project
- Create a project for your capstone project
- Switch to view "board"
- Create columns: Backlog, Sprint Backlog, In Progress, Code Review, Quality Assurance, Review, Done
- Create drafts for user stories
- Convert them to issues within your repository

---

# 😵‍💫 Questions?