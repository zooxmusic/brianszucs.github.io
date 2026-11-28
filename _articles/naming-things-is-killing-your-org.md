---
layout: article
title:  "Naming Things Is Killing Your Engineering Org—and You Don’t Even Know It"
tagline: "Bad naming doesn’t show up in your logs. It doesn’t crash production. It doesn’t get flagged in code review."
date:   2021-11-17
categories: responsibility  
author:  Brian Szucs
image: /assets/img/namingcomic.jpeg
---
```
    > I’ve wasted 20% of my career because of bad naming.
    > Not bad tech. Not bad people. Just bad names.
```
##### And if you’re an engineer, you probably have too

#### The Invisible Tax

* Bad naming doesn’t show up in your logs. It doesn’t crash production. It doesn’t get flagged in code review.
* Instead, it bleeds you dry silently.
* Every time you see a class like HandlerManagerFactory, or a function like processData(), your brain has to pause and say
* “What does this actually do?”
* That pause? That’s cognitive overhead. That’s technical debt in disguise.

#### Real Examples I’ve Fought in the Wild

* Utils.java – a dumping ground for “we gave up”
* Flag, data, temp, obj – I dare you to onboard a new dev with that
* ManagerService – is it managing services or servicing managers?
* Controller that writes to S3, hits Redis, and triggers 3 retries via Kafka

##### You might think

 “Well, the team knows what it means.”

### Bullshit

* The moment anyone leaves—or joins—that tribal knowledge dies. And your code becomes a maze.
* Naming Isn’t Cosmetic. It’s Architecture.
* You can't name what you don't understand
* If you struggle to name something, it usually means:
* The responsibility is unclear
* The boundaries are wrong
* You're stuffing too much into one place

#### Naming isn’t a cherry on top. It’s the X-ray of your system’s design

### How to Fight Back

* If you want to be elite, you need to treat naming like a core skill:
* 🔪 Rename ruthlessly—don't let vague abstractions survive
* 🧭 Name by behavior, not implementation—RetryQueuePublisher, not Handler
* 🗂️ Establish vocabularies—for domains, for systems, for cross-team clarity
* 💬 Review naming in PRs—not just logic
* And stop tolerating “temp”, “final”, “foo”, and “legacy-v2”.

### Final Word

* If you want your team to move faster, think clearer, and stop bleeding hours into Slack threads about what doIt() does—fix your names.
* You don’t need a new framework.
* You need a new standard of clarity.
* 🧠 Developer Experience: #SoftwareEngineering #CleanCode #Refactoring
* 💣 Invisible Problems That Hurt Velocity: #TechnicalDebt

---
> Written by: Brian Szucs,
> Senior Backend Java Developer | Java/Spring + Spring AI| Modernizing legacy systems across regulated industries | Writing on architecture, leadership, and meditation

##### June 12, 2025
---


#sofwaredevelopment #agile #management 
