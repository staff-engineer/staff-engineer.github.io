---
title: "How do you create a system design interview task?"
date: 2023-03-12
tags: [
    "interview",
]
draft: true,
---

In the previous article, we discussed the critical components of conducting an effective system design interview, emphasizing the importance of defining high-level goals and competencies to evaluate. We provided a base skeleton that could be used to design detailed interview questions.

In this article, we will focus on the process of creating an actual interview task, specifically highlighting what to pay attention to and how to prepare without overpreparing. We will define the boundaries of an example problem and use this to create an interview task. Additionally, we will propose a scorecard that can be used to conduct and evaluate the interview.

It's important to remember that interviews are a two-way street. As an interviewer, you're not only evaluating the candidate, but they're also evaluating you and your company. Therefore, it's crucial to create an engaging and challenging interview task that showcases the company's values and culture while also effectively evaluating the candidate's skills and abilities.


# Think about skills you want to evaluate

The first step in creating an effective system design interview task is to define the skills you want to evaluate and the expectations for candidates at different levels of seniority. Creating one interview task that can be used to evaluate both junior and senior+ candidates saves time in preparation and onboarding fellow interviewers. Additionally, it ensures that all candidates are evaluated using the same criteria, making the hiring process more consistent. Based on the candidate's experience, you can provide more or less guidance during the interview, similar to how you would on the job. This approach provides a realistic evaluation of the candidate's abilities and helps assess their potential fit within the team.

As a recap, in the previous article, we discussed several core competencies necessary for a system design interview. hese competencies will serve as the foundation for our example interview task, ensuring that we evaluate candidates based on the necessary skills for the job. The skills we would like to evaluate:
* Problem understanding and communication
* Problem solving
* Distributed systems knowledge
* Technical leadership

These competencies will be used to prepare an example interview task. Let's assume that we are designing an interview task for a typical SaaS company that uses a range of CRUD microservices, SQL databases, and supporting reporting services. This assumption will help us define the interview task's scope.

# Pick the system and problem set

Selecting the appropriate system to design for the interview task is crucial in evaluating the candidate's skills effectively. We recommend choosing a system that you are knowledgeable about and have expertise in. Having a good understanding of the system's architecture and potential bottlenecks, limitations, and resilience issues is essential. With prior experience, it becomes easier to dive deeper into the system's details and evaluate the candidate's thought process.

We advise against using generic problem names such as "design Twitter" or "design Youtube" unless you work for such companies. It's important to be honest with yourself and select a system that is relevant to your company's scale and technical challenges. The interview is also an opportunity to showcase your company and its unique challenges, piquing the candidate's interest. Choosing well-known systems may lead to preconceived solutions based on existing literature, which may not reflect the real-world problems your company faces. Instead, selecting a more relevant system can provide valuable insights into how the candidate approaches real-life technical challenges.

## Example
TODO:
  * budgeting app
  * recipe app
  * image/music generating app


# Establish problem boundries and limits

It's time to establish problem boundries and limits. It's essential to put yourself in the candidate's shoes and brainstorm potential questions they might ask you. This will help you prepare a more comprehensive task and identify areas where the candidate may struggle. Collaborating with colleagues can also help generate a list of relevant questions or ideas. 

To give you some inspiration, here are some high-level questions you can ask yourself while preparing the interview task:
* Who is the target audience of the application?
* What are the expected traffic and usage patterns?
* What is the anticipated growth rate of the system and business?
* What is the current architecture of the system (if any)?
* What technologies are required or preferred for the system?

Once you have the questions and boundaries, plan what information you want to reveal to the candidate and what you want them to discover on their own. It's important to strike a balance based on the candidate's seniority level. Senior engineers are expected to be more independent and able to tackle challenges, while junior engineers may need more guidance to get started.

## Example
TODO

# Outline the interview structure

To ensure an effective system design interview, it's important to encourage candidates to focus on a simple design that can be expanded later. Many candidates may be influenced by literature that emphasizes huge scale at the beginning, so it's important to guide them towards a more realistic and practical approach.

Once you have established the initial high-level design with the candidate, it's time to delve into details. Prepare a list of topics that you want to cover, but also be prepared for candidates to go in different directions. As the interviewer, it's your responsibility to guide them towards the aspects that are most relevant to the task.

It's also important to be understanding of the candidate's expertise and allow them to dive into details they are comfortable with. It's unrealistic to expect every candidate to be an expert in all software engineering branches. For more senior candidates, it's reasonable to expect them to have in-depth knowledge of one or two key areas, while having a decent understanding of the rest.

Lastly, expect the unexpected. There is less structure in a system design interview compared to a coding one, so not everything will go according to plan. Be flexible and adapt to any unexpected turns in the conversation.

# Create detailed scorecards

We're almost ready for the interview. To assess the candidate's performance effectively, interviewers should have a scorecard on hand. This will help in writing constructive feedback and evaluating all the necessary skills. In addition to the scorecard, we recommend creating an interviewer guide that explains the details of the scoring criteria. This can be particularly helpful for onboarding new interviewers.

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

# Final improvments and interviewer guide

In addition to preparing for the interview, it's important to conduct a peer review of the interview task, plan, and scorecards. Collaborate with your colleagues to identify any potential biases and areas for improvement. Once you've identified these areas, create a guide for your fellow interviewers and onboard them to the process. As you continue with the interview process, make any necessary adjustments while maintaining consistency and fairness for all candidates. By reviewing and refining the process, you can ensure that the interview process is effective and unbiased.

# Summary
In this article, we provided a step-by-step guide for creating an effective system design interview task. The first step is to define the skills to be evaluated for different levels of seniority. Next, it is crucial to choose a relevant system to design for the interview task to evaluate the candidate's skills effectively. Establishing problem boundaries and limits is important, followed by outlining the interview structure to ensure that candidates focus on a simple design that can be expanded later. Lastly, detailed scorecards should be created to assess the candidate's performance effectively. The article offers examples and tips to help prepare a comprehensive task and evaluate the candidate's abilities to assess their potential fit within the team.