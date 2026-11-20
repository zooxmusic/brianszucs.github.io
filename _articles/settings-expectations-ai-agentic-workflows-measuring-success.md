---
layout: "article"
title:  "Setting Expectations: AI Agentic Workflows, Platforms, Models, and Measuring Success"
tagline: "Artificial intelligence is changing software development at a remarkable pace. Organizations are investing in AI platforms, adopting agentic workflows, and incorporating AI into their engineering processes.s"
date:   2026-11-19 
categories: ai 
author:  Brian Szucs
image: /assets/img/ai-agentic-workflows.png
---

The difference between adopting AI and knowing how to work with it

🤖 Artificial intelligence is changing software development at a remarkable pace. Organizations are investing in AI platforms, adopting agentic workflows, and incorporating AI into their engineering processes.

But there's a growing problem: the expectations surrounding AI adoption are advancing faster than organizational understanding of the technology itself.

Executives hear impressive demonstrations and ambitious productivity claims. Those claims become strategic initiatives, new job requirements, and expectations placed on engineering teams.

What often gets overlooked is everything required to turn AI capabilities into reliable engineering outcomes.

Adopting AI is relatively easy. Learning to use it effectively is an entirely different undertaking.

This article explores the distinctions between models, platforms, and agentic workflows, how organizations can introduce them responsibly, and how to measure whether they're actually delivering value.

 

🧠 1. Understanding the AI Landscape

One of the first mistakes organizations make is treating AI as a single capability.

There are several distinct components, each with its own responsibilities and limitations.

Models

A model is the underlying intelligence responsible for interpreting information and generating responses.

Different models demonstrate different strengths in areas such as:

•	Code generation and analysis.
•	Reasoning and problem-solving.
•	Information retrieval and synthesis.
•	Instruction following.
•	Structured output generation.
•	Multimodal processing.

No single model is necessarily best at everything.

Just as organizations recognize specialization among human employees, they should recognize that different models can offer different strengths.

AI Platforms

An AI platform provides the environment in which models are accessed and used.

Depending on the platform, capabilities may include:

•	Model selection and configuration.
•	Context and memory management.
•	Tool integration.
•	Agent creation and orchestration.
•	Workflow execution.
•	Security and access controls.
•	Monitoring and evaluation.

Purchasing access to a model does not automatically provide an effective agentic development environment.

Agents

An agent is an AI-driven component assigned a responsibility or objective.

Agents may have access to tools, instructions, knowledge sources, and other agents.

Their effectiveness depends on much more than the underlying model. Their responsibilities, context, permissions, and available capabilities all matter.

Workflows

A workflow describes how work moves through one or more components.

It might involve a single agent, multiple agents, human approval, external systems, or a combination of these.

Understanding these distinctions is essential before deciding how an organization should adopt AI.

 

⚙️ 2. Agentic Workflows Aren't Magic

The term agentic has become increasingly popular, but organizations need to understand what they're actually introducing.

An agentic workflow can involve:

•	Task decomposition.
•	Delegation.
•	Specialized agents.
•	Tool execution.
•	Information retrieval.
•	Validation.
•	Human review.
•	Error handling and recovery.

Consider a software development workflow.

One agent might analyze requirements, another might propose an implementation, and another might review the resulting code.

That sounds attractive, but introducing additional agents also introduces additional complexity.

The coordination problem

More agents do not automatically mean more productivity.

Each additional component creates potential challenges involving:

•	Context transfer.
•	Conflicting recommendations.
•	Inconsistent assumptions.
•	Communication overhead.
•	Failure propagation.
•	Verification of intermediate results.

A poorly designed multi-agent workflow can be less effective than a single capable agent working with an experienced developer.

🚧 The objective should be to introduce agents where specialization provides measurable value, not simply to maximize the number of agents involved.

Human oversight also remains important. Delegating work does not eliminate responsibility for the outcome.

 

🎯 3. Setting Realistic Expectations

This is where organizations need to spend considerably more time.

AI can accomplish impressive things, but demonstrations frequently omit the preparation, context, iteration, and human judgment that made the demonstration successful.

Consider some common assumptions:

Expectation
What actually needs to happen
AI can write the application
Requirements, architecture, implementation, and verification are still necessary
AI understands our codebase
It needs sufficient context and must identify what it doesn't know
AI can design architecture
Architectural decisions require constraints, trade-off analysis, and engineering judgment
AI can write tests
Test coverage and correctness still require evaluation
Agents can work autonomously
Permissions, coordination, monitoring, and recovery must be designed
AI makes developers faster
Productivity gains depend on the task, experience, and workflow


Context is not optional

An AI system cannot reliably make decisions based on information it hasn't received or cannot retrieve.

Providing meaningful context is one of the most important skills in effective AI collaboration.

That includes:

•	Project requirements.
•	Architectural constraints.
•	Existing implementation details.
•	Coding standards.
•	Domain terminology.
•	Expected behavior.
•	Acceptance criteria.

A capable model working with inadequate context can produce an impressive answer that is completely wrong for the application.

Specifications change the equation

Specification-driven development is particularly interesting because it establishes expectations before implementation begins.

Rather than asking an AI to build something based on a few sentences, the developer establishes the intended behavior, constraints, and acceptance criteria.

This gives both the human and AI a shared reference point.

It also creates something that can be independently evaluated.

 

📈 4. Introducing AI Progressively

Organizations shouldn't expect developers to become proficient in agentic engineering simply because they have been given access to an AI platform.

Proficiency develops through experience.

A progressive adoption strategy allows individuals and teams to develop their skills without introducing unnecessary complexity prematurely.

A practical progression

1. Exposure and experimentation

🧪 Let developers experiment with AI on real, bounded tasks.

Learn what it does well, where it struggles, and how different models behave.

2. AI-assisted development

💻 Introduce AI into everyday development activities such as debugging, code explanations, test generation, and implementation assistance.

3. Human–AI collaboration

🤝 Develop effective pair-programming practices.

Learn to provide context, challenge assumptions, evaluate suggestions, and refine results.

4. Structured collaboration

📋 Introduce specifications, architectural constraints, persistent project context, and repeatable workflows.

5. Agentic workflows

🤖 Introduce specialized agents, delegation, orchestration, and automated processes where they provide demonstrable benefits.

6. Organizational integration

🏢 Establish governance, security requirements, training, accountability, and measurable performance expectations.

Not every developer needs to become an expert in multi-agent orchestration.

An engineer who uses AI exceptionally well for debugging, testing, and problem-solving can provide substantial value without building an agent workforce.

The goal is proficiency, not complexity.

 

📊 5. Measuring Success

This may be the most important part of AI adoption.

Organizations frequently measure adoption by counting subscriptions, licenses, generated code, or the number of employees using AI.

These measurements tell us very little about whether the organization is actually benefiting.

Activity is not the same thing as productivity. Productivity is not the same thing as business value.

Organizations need meaningful measurements.

Engineering performance

Measurement
What it tells us
Delivery lead time
Are changes reaching production faster?
Rework
How much correction is required?
Defect rates
Is software quality being maintained?
Deployment frequency
Are teams delivering more effectively?
Change failure rate
Are faster deliveries creating additional risk?
Maintainability
Are we creating future engineering problems?


Financial performance

💰 AI adoption has costs beyond licensing.

Organizations should account for:

•	Model and platform expenses.
•	Infrastructure.
•	Training.
•	Human review.
•	Integration work.
•	Rework.
•	Maintenance.
•	Security and governance.

The relevant question isn't how much code AI generated.

It's whether the total cost of delivering and maintaining quality software has improved.

Developer experience

❤️ This is an area organizations should not overlook.

Developers are directly affected by changes to their workflows and expectations.

Consider measuring:

•	Developer satisfaction.
•	Perceived workload.
•	Confidence in AI-generated results.
•	Time spent correcting AI output.
•	Training effectiveness.
•	Burnout and retention.

An organization that improves apparent productivity while exhausting its engineering teams has not necessarily achieved a sustainable improvement.

Establish a baseline

Measurements should be collected before and after introducing AI.

Where possible, compare similar tasks, teams, and projects while accounting for differences in complexity and experience.

Without a baseline, organizations risk attributing improvements to AI that may have resulted from other changes.

 

🚧 6. The Organizational Risk of Getting It Wrong

There is a particularly dangerous possibility when management adopts expectations based on incomplete information.

Imagine the following sequence:

1.	Management expects substantial productivity gains from AI.
2.	Developers are required to adopt unfamiliar tools and workflows.
3.	Expectations increase before proficiency develops.
4.	Delivery slows because developers are learning, correcting, and verifying AI output.
5.	Management interprets declining productivity as resistance to change.
6.	Pressure increases.

This can create a negative feedback loop.

Developers become overwhelmed, morale deteriorates, and experienced engineers may eventually leave.

The organization then loses precisely the people whose expertise it needs to make AI adoption successful.

The company may mistakenly conclude that its employees weren't embracing AI enthusiastically enough.

In reality, the adoption strategy may have been the problem.

Management has responsibilities too

Managers need to understand:

•	What AI capabilities actually exist.
•	What skills are required to use them effectively.
•	How much training is necessary.
•	What productivity improvements are realistic.
•	How quality and security will be maintained.
•	How performance should be evaluated during adoption.

Requiring employees to use AI does not automatically make those employees proficient in AI-assisted engineering.

Organizations must create the conditions for successful adoption.

 

🧭 7. A Better Way Forward

AI adoption shouldn't be treated as a race to implement the greatest number of tools or automate the largest number of tasks.

It should be approached as an organizational learning process.

A sustainable strategy includes:

Education: Develop an understanding of models, platforms, agents, and workflows.

Experimentation: Give teams opportunities to discover capabilities and limitations.

Progression: Introduce more sophisticated workflows as experience develops.

Accountability: Maintain clear responsibility for engineering outcomes.

Evaluation: Measure actual improvements rather than relying on marketing claims.

Adaptation: Reassess practices as models, platforms, and organizational experience evolve.

Most importantly, organizations should remain willing to change their approach when the evidence suggests something isn't working.

 

💡 Conclusion: Adoption Is Not Proficiency

AI represents a significant opportunity for software engineering and business operations.

But realizing that opportunity requires more than purchasing access to models, deploying agents, or announcing an AI-first strategy.

It requires people who understand the technology, organizations willing to invest in developing that understanding, and management capable of establishing realistic expectations.

AI can make experienced developers more effective. It can help less experienced developers learn. It can automate repetitive work and enable entirely new approaches to problem-solving.

But none of those outcomes is guaranteed simply by introducing the technology.

The organizations that benefit most will likely be those that invest as much effort in understanding and developing their people as they do in acquiring AI capabilities.

The objective isn't to adopt AI as quickly as possible. It's to learn how to use it effectively, responsibly, and sustainably.

🤝 Better collaboration. Better engineering. Better outcomes.

---
Written by: Brian Szucs
Senior Backend Java Developer | Java/Spring + Spring AI| Modernizing legacy systems across regulated industries | Writing on architecture, leadership, and meditation

April 12, 2025
---

#sofwaredevelopment #agile #management 