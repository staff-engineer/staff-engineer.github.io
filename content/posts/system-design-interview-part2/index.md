---
title: "How do you create a system design interview task?"
date: 2023-05-30
tags: [
    "interview",
]
---

In the previous article, we discussed the critical components of conducting an effective system design interview, emphasizing the importance of defining high-level goals and competencies to evaluate. We provided a base skeleton that could be used to design detailed interview questions.

In this article, we will focus on the **process of creating an actual interview task**, specifically highlighting what to pay attention to and how to prepare without overpreparing. Additionally, we will **propose a scorecard** that can be used to conduct and evaluate the interview.

It's important to remember that interviews are a two-way street. As an interviewer, you're not only evaluating the candidate, but they're also evaluating you and your company. Therefore, it's crucial to create an **engaging and challenging** interview task that showcases the company's values and culture.

![Interview](./interview.png)

# Think about skills you want to evaluate

The first step in creating an effective system design interview task is to define the skills you want to evaluate and the expectations for candidates at different levels of seniority. Creating one interview task that can be used to evaluate both junior and senior+ candidates saves time in preparation and onboarding fellow interviewers. Additionally, it ensures that **all candidates are evaluated using the same criteria**, making the hiring process consistent. Based on the candidate's experience, you can provide more or less guidance during the interview, similar to how you would on the job. This approach provides a **realistic evaluation of the candidate's abilities** and helps assess their potential fit for the team.

As a recap, in the [previous article]({{< ref "/posts/system-desing-interview-part1/index.md" >}}), we discussed several core competencies necessary for a system design interview:
* *Problem understanding and communication*
* *Problem-solving*
* *Distributed systems knowledge*
* *Technical leadership*

# Pick the system and the problem set

Choose a system that you are **knowledgeable about and have expertise** in. It’s easier to dive into details when you have a good understanding of the system's architecture and potential bottlenecks, limitations, and resilience issues. It helps to evaluate candidates’ thought process more accurately.

We advise against using classic problems such as "design Twitter" or "design Youtube" unless you work for those companies. It's important to be honest with yourself and select a system that is relevant to your company's scale and technical challenges. **The interview is also an opportunity to showcase your company and its unique challenges, piquing the candidate's interest**. Well-known problems may lead to preconceived solutions based on existing literature, which may not reflect the real-world candidate’s experience.

Instead of providing a granular description of the task - **keep it concise and underdefined**. This encourages stronger candidates to proactively discover the domain by collaborating with the interviewers from the very beginning.

## Example
*Let’s imagine we’re a small startup. We would like to create a simple budgeting application, that allows tracking expenses. How would you design such a system?*
![Example interview task](./interview_example.jpg)

# Establish problem boundaries and limits

It's time to establish problem boundaries and limits. It's essential to **put yourself in the candidate's shoes** and **brainstorm potential questions** they might ask you. This will help you prepare a more comprehensive task and identify areas where the candidate may struggle. Collaborating with colleagues can also help generate a list of relevant questions or ideas. 

To give you some inspiration, here are some high-level questions you can ask yourself while preparing for the interview task:
* *Who is the target audience of the application?*
* *What are the expected traffic and usage patterns?*
* *What is the anticipated growth rate of the system and business?*
* *What is the current architecture of the system (if any)?*
* *What technologies are required or preferred for the system?*

Once you have the questions and boundaries, plan what information you want to reveal to the candidate and what you want them to discover on their own. It's important to strike a balance based on the candidate's seniority level. Senior engineers are expected to be more independent, while junior engineers may need more guidance to get started.

## Example
![Example task plan](./interview_map.jpg)

# Expect the buy-in design

To ensure an effective system design interview, it's important to encourage candidates to focus on a simple design that can be expanded later. Many candidates may be influenced by literature that emphasizes a huge scale at the beginning. Guide them toward a more realistic and practical approach. The easiest way to achieve so is by answering their questions in a way that is the most convenient and simplistic. For example:
*Q: Should I add support for multiple currencies for budgeting?*
*A: It’s okay for us to support USD only.*

Once you have established the initial high-level design with the candidate, it's time to delve into details. Prepare a list of topics that you want to cover, but also be prepared for candidates to go in different directions. As the interviewer, it's **your responsibility to guide them toward the aspects that are most relevant to the task**.

It's also important to be understanding of the candidate's expertise and allow them to dive into details they are comfortable with. It's unrealistic to expect every candidate to be an expert in all software engineering branches. For more senior candidates, it's reasonable to expect them to have **in-depth knowledge of one or two key areas** while having a **decent understanding of the rest**.

Lastly, **expect the unexpected**. There is less structure in a system design interview compared to a coding one, so not everything will go according to plan. Be **flexible and adapt** to any unexpected turns in the conversation.

# Create detailed scorecards

We're almost ready for the interview. To assess the candidate's performance effectively, interviewers should have a scorecard at hand. This will help in writing constructive feedback and evaluating all the necessary skills. In addition to the scorecard, we recommend creating an interviewer guide that explains the details of the scoring criteria. This can be particularly helpful for onboarding new interviewers.
## Example
An example scorecard, which we could use for our interview task.

| Competency                                                        | Category                                | Level  |
|-------------------------------------------------------------------|-----------------------------------------|--------|
| Clearly articulates thoughts and ideas                            | Problem understanding and communication | Mid    |
| Establishes clear problem boundaries and asks relevant questions  | Problem understanding and communication | Mid    |
| Communicates assumptions and works to validate all requirements   | Problem understanding and communication | Senior |
| Avoids making unfounded assumptions                               | Problem understanding and communication | Staff+ |
| Develops a working solution for simple problems                   | Problem-solving                         | Mid    |
| Extends solutions to meet new and complex requirements            | Problem-solving                         | Senior |
| Identifies trade-offs and can make pragmatic decisions            | Problem-solving                         | Senior |
| Designs highly scalable and flexible solutions                    | Problem-solving                         | Staff+ |
| Possesses basic knowledge of distributed systems                  | Distributed systems knowledge           | Mid    |
| Can explain the benefits and drawbacks of different architectures | Distributed systems knowledge           | Mid    |
| Demonstrates broad knowledge of distributed systems               | Distributed systems knowledge           | Senior |
| Can handle system failures and identify their causes	            | Distributed systems knowledge           | Senior |
| Ability to reason about performance and latency tradeoffs	        | Distributed systems knowledge           | Senior |
| Exhibits deep expertise in at least 1-2 key areas                 | Distributed systems knowledge           | Staff+ |
| Accurately predicts bottlenecks and resiliency issues             | Distributed systems knowledge           | Staff+ |
| Balances system performance and developer's experience            | Distributed systems knowledge           | Staff+ |
| Identifies trade-offs and can make decisions	                    | Technical leadership                    | Senior |
| Considers security and privacy concerns		                    | Technical leadership                    | Senior |
| Utilizes tools and technologies to solve business problems        | Technical leadership                    | Senior |
| Considers deployment and maintenance aspects                      | Technical leadership                    | Senior |
| Designs solutions with the customer in mind                       | Technical leadership                    | Staff+ |
| Considers impact of decisions on engineering team                 | Technical leadership                    | Staff+ |
| Ability to identify and prioritize technical debt	                | Technical leadership	                  | Staff+ |
| Can lead design discussions and solicit feedback	                | Technical leadership	                  | Staff+ |

# Final improvements and interviewer guide

In addition to preparing for the interview, it's important to **conduct a peer review** of the interview task, plan, and scorecards. Collaborate with your colleagues to **identify any potential biases** and **areas for improvement**. Once you've identified these areas, create a guide for your fellow interviewers and onboard them to the process. As you continue with the interview process, make any necessary adjustments while maintaining consistency and fairness for all candidates. By **reviewing and refining the process**, you can ensure that the interview process is effective and unbiased.

# Summary
In this article, we provided a step-by-step guide for creating an **effective system design interview task**. The first step is to define the skills to be evaluated for different levels of seniority. Next, it is crucial to choose a relevant system to design for the interview task to evaluate the candidate's skills effectively. **Establishing problem boundaries** and limits is important, followed by outlining the interview structure to ensure that candidates focus on a simple design that can be expanded later. Lastly, **detailed scorecards** should be created to assess the candidate's performance effectively. The article offers examples and tips to help prepare a comprehensive task and evaluate the candidate's abilities to assess their potential fit within the team.