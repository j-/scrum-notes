# Scrum notes

## Useful Links

* [The Scrum Guide](http://www.scrumguides.org/scrum-guide.html)
    - [2016 PDF version](http://www.scrumguides.org/docs/scrumguide/v2016/2016-Scrum-Guide-US.pdf)
* [Scrum Glossary](https://www.scrum.org/Resources/Scrum-Glossary)
* [PSM I Assessment](http://www.scrum.org/Assessments/Professional-Scrum-Master-Assessments/PSM-I-Assessment)
* [Open Assessments](https://www.scrum.org/Assessments/Open-Assessments)
* [Mikhail Lapshin's PSM I Quiz](http://mlapshin.com/index.php/psm-quiz/)
    - [Learning Mode](http://mlapshin.com/index.php/psm-quiz/learning-mode/)
    - [Read Mode](http://mlapshin.com/index.php/psm-quiz/real-mode/)

These notes are heavily based off of Mikhail Lapshin's quiz.

## Assessment Details

From the [PSM I Assessment](http://www.scrum.org/Assessments/Professional-Scrum-Master-Assessments/PSM-I-Assessment) page:

* Fee: $150 per attempt
* Passing score: 85%
* Time limit: 60 minutes
* Number of Questions: 80
* Format: Multiple Choice, Multiple Answer and True/False
* Difficulty: Intermediate
* Language: English only
* [PSM Subject Areas](https://www.scrum.org/Courses/Professional-Scrum-Master/* PSM-Subject-Areas)
* Required course: None
* Recommended courses: [Professional Scrum Foundations](https://www.scrum.org/Courses/Professional-Scrum-Foundations) or [Professional Scrum Master](https://www.scrum.org/Courses/Professional-Scrum-Master)
* Practice Assessment: [Scrum Open](https://www.classmarker.com/online-test/start/?quiz=vek54a6ec10658ef)
* Passwords have no expiration date, but are valid for one attempt only

**Note**:
* 80 questions and 85% passing score means **68** or more questions must be answered correctly to pass.
* 80 questions and 60 minutes means **45 seconds** per question
* The assessment is online and therefore 'open book'

## Scrum Theory

### Scrum

* Founded on *empiricism*

* Comprised of
    - [Scrum Teams](#scrum-team)
    - [Roles](#scrum-roles)
    - Rules
    - [Events](#scrum-events)
    - [Artifacts](#scrum-artifacts)

* Pillars that uphold Scrum
    - Transparency
    - Inspection
    - Adaption

* Opportunities to Inspect and Adapt
    - [Sprint Planning](#sprint-planning)
    - [Daily Scrum](#daily-scrum)
    - [Sprint Review](#sprint-review)
    - [Sprint Retrospective](#sprint-retrospective)

* Burn-down Charts show how much work remains till the end of the Sprint.

* Cone of Uncertainty shows how much is known about the Product over time

* Each component within the Scrum framework serves a specific purpose and is essential to Scrum’s success and usage.

* Scrum is not a process or a technique for building products. It is a framework within which you can employ various processes and techniques. It does not describe agile processes and techniques.

* If an inspector determines that one or more aspects of a process deviate outside acceptable limits, and that the resulting product will be unacceptable, the process or the material being processed must be adjusted. An adjustment must be made as soon as possible to minimize further deviation.

### Sprint

* Scrum does not require having aligned Sprints for multiple teams.

* Can be cancelled by *only* the [Product Owner](#product-owner)
    - Any completed and Product Backlog Items are reviewed
    - If part of the work is releasable the Product Owner accepts it
    - Incomplete Product Backlog Items are re-estimated and put back on the Product Backlog
    - The Sprint is cancelled only if the [Sprint Goal](#sprint-goal) becomes obsolete

* During the Sprint
    - No changes are made that would endanger the [Sprint Goal](#sprint-goal)
    - Quality goals do not decrease
    - Scope may be clarified and re-negotiated between the Product Owner and [Development Team](#development-team) as more is learned

* Development Teams deliver an Increment of Product functionality every Sprint
    - This Increment is usable so a Product Owner may choose to immediately release it
    - Each Increment only contains "Done" functionality that could be released immediately
    - It is not normal to have a "hardening" Sprint to remove technical debt and prepare the Product for upcoming release

### Sprint Goal

* Provides guidance to the [Development Team](#development-team) on why it is building the Increment.

* The [Sprint Goal](#sprint-goal) is an objective set for the Sprint that can be met through the implementation of Product Backlog.

* After the [Development Team](#development-team) forecasts the Product Backlog items it will deliver in the Sprint, the [Scrum Team](#scrum-team) crafts a [Sprint Goal](#sprint-goal).

* If the [Sprint Goal](#sprint-goal) becomes obsolete the Sprint may be cancelled.

## Scrum Artifacts

* Scrum users must frequently inspect Scrum artifacts and progress toward a [Sprint Goal](#sprint-goal) to detect undesirable variances. Their inspection should not be so frequent that inspection gets in the way of the work. Inspections are most beneficial when diligently performed by skilled inspectors at the point of work.

### Sprint Backlog

* The Product Backlog items selected for this Sprint plus the plan for delivering them.

* Created at the [Sprint Planning](#sprint-planning).

* Belongs solely to the [Development Team](#development-team).

* The [Development Team](#development-team) modifies the Sprint Backlog throughout the Sprint
    - The [Development Team](#development-team) may learn more about the work needed to achieve the [Sprint Goal](#sprint-goal)
    - As new work is required the [Development Team](#development-team) adds it to the Sprint Backlog
    - Only the [Development Team](#development-team) may change the Sprint Backlog

* If an item in the Sprint Backlog cannot be finished by the end of the Sprint it should be renegotiated between the Product Owner and [Development Team](#development-team).
    - The Sprint is not cancelled in this case

### Product Backlog

* Is an ordered list of everything that might be needed in the product and is the single source of requirements for any changes to be made to the product
    - Product Backlog Items are ordered with most valuable and clear items at the top

* Used to describe the upcoming work on the product
    - All [Development Teams](#development-team) working together on the same product should be using the same Product Backlog

* Is managed by the Product Owner
    - The Product Owner is the sole person responsible for the Product Backlog
    - The Product Owner can delegate some work related to Product Backlog management to the [Development Team](#development-team)
    - The Product Owner is responsible for the content, availability and ordering of the Product Backlog

* Product Backlog refinement consumes no more than 10% of the capacity of the [Development Team](#development-team).

* Features of a Product Backlog
    - Never complete
    - Evolves as the product and the environment in which it will be used evolves
    - Dynamic -- constantly changes to identify what the product needs to be appropriate, competitive, and useful
    - As long as a product exists, its Product Backlog also exists

* Product Backlog management includes
    - Clearly expressing Product Backlog items
    - Ordering the items in the Product Backlog to best achieve goals and missions
    - Optimizing the value of the work the [Development Team](#development-team) performs
    - Ensuring that the Product Backlog is visible, transparent, and clear to all, and shows what the [Scrum Team](#scrum-team) will work on next
    - Ensuring the [Development Team](#development-team) understands items in the Product Backlog to the level needed

### Increment

* The Increment is the sum of all the Product Backlog Items completed during the Sprint *and* the value of the increments of all previous Sprints.

* Only members of the [Development Team](#development-team) create the Increment.

## Scrum Roles

### Scrum Team

* The [Scrum Team](#scrum-team) consists of
    - A [Product Owner](#product-owner)
    - The [Development Team](#development-team)
    - A Scrum Master

* [Scrum Teams](#scrum-team) are self-organizing
    - Choose how to best accomplish their work rather than being directed by others outside the team

* [Scrum Teams](#scrum-team) are cross-functional
    - Have all competencies needed to accomplish the work without depending on others not part of the team

* There are three main qualities the [Scrum Team](#scrum-team) is designed to optimize
    - Flexibility
    - Creativity
    - Productivity

#### Product Owner

* Characteristics of the [Product Owner](#product-owner)
    - Product value maximizer
    - Lead facilitator of key stakeholder involvement
    - Product marketplace expert

* Is responsible for managing the Product Backlog
    - Maintains the content, availability and ordering of Product Backlog Items
    - Can delegate some work related to Product Backlog management to the [Development Team](#development-team)
    - Most valuable and clear items are placed at the top of the Product Backlog

* Is responsible for the monitoring of the remaining work towards the Project Goal
    - Tracks total work remaining at least every [Sprint Review](#sprint-review)
    - Compares this amount with work remaining at previous [Sprint Reviews](#sprint-review) to assess progress toward completing projected work by the desired time for the goal
    - This information is made transparent to all stakeholders.

* Has the authority to cancel the sprint
    - *Only* the [Product Owner](#product-owner) has this authority

* May be part of the [Development Team](#development-team) if they are also executing the work of the Sprint Backlog.

* There is only one [Product Owner](#product-owner) in a [Scrum Team](#scrum-team)
    - The [Product Owner](#product-owner) is one person
    - They may represent the interests of a committee

#### Development Team

* The optimal [Development Team](#development-team) size is between 3 and 9 people.

* [Product Owner](#product-owner) and Scrum Master may be part of the [Development Team](#development-team) if they are also executing the work of the Sprint Backlog.

* Responsible for all estimates in the Product Backlog.
    - The [Product Owner](#product-owner) may influence the [Development Team](#development-team) by helping it understand and select trade-offs, but the people who will perform the work make the final estimate.

* Creates the Increment.

* By the end of the [Sprint Planning](#sprint-planning), the [Development Team](#development-team) should be able to explain to the [Product Owner](#product-owner) and Scrum Master how it intends to work as a self-organizing team to accomplish the [Sprint Goal](#sprint-goal) and create the anticipated Increment.

* Responsible for tracking the total work remaining in the Sprint Backlog and the likelihood of achieving the [Sprint Goal](#sprint-goal).

* Allowed to change the Sprint Backlog during the sprint
    - Only the [Development Team](#development-team) can change its Sprint Backlog during a Sprint. The Sprint Backlog is a highly visible, real-time picture of the work that the [Development Team](#development-team) plans to accomplish during the Sprint, and it belongs solely to the [Development Team](#development-team).

* Can be allowed to make changes to the Product Backlog if delegated by the [Product Owner](#product-owner)

* [Development Teams](#development-team) have the following characteristics
    - They are self-organizing. No one (not even the Scrum Master) tells the [Development Team](#development-team) how to turn Product Backlog into Increments of potentially releasable functionality
    - [Development Teams](#development-team) are cross-functional, with all of the skills as a team necessary to create a product Increment
    - Scrum recognizes no titles for [Development Team](#development-team) members other than Developer, regardless of the work being performed by the person; there are no exceptions to this rule
    - Scrum recognizes no sub-teams in the [Development Team](#development-team), regardless of particular domains that need to be addressed like testing or business analysis; there are no exceptions to this rule
    - Individual [Development Team](#development-team) members may have specialized skills and areas of focus, but accountability belongs to the [Development Team](#development-team) as a whole

#### Scrum Master

* Serves the [Development Team](#development-team) by
    - Helping the [Development Team](#development-team) to create high-value products
    - Coaching the [Development Team](#development-team) in self-organization and cross-functionality
    - Removing impediments to the [Development Team](#development-team)’s progress

* May be part of the [Development Team](#development-team) if they are also executing the work of the Sprint Backlog.

* Serves the organization by
    - Planning Scrum implementations within the organization
    - Leading and coaching the organization in its Scrum adoption
    - Working with other Scrum Masters to increase the effectiveness of the application of Scrum in the organization

* Does the following regarding the [Daily Scrum](#daily-scrum)
    - Ensures that the [Development Team](#development-team) has the meeting, but the [Development Team](#development-team) is responsible for conducting the [Daily Scrum](#daily-scrum)
    - Teaches the [Development Team](#development-team) to keep the [Daily Scrum](#daily-scrum) within the 15 minute time-box
    - Enforces the rule that only [Development Team](#development-team) members participate in the [Daily Scrum](#daily-scrum)

* Is a servant-leader for the [Scrum Team](#scrum-team)
    - Helps those outside the [Scrum Team](#scrum-team) understand which of their interactions with the [Scrum Team](#scrum-team) are helpful and which aren't
    - Helps everyone change these interactions to maximize the value created by the [Scrum Team](#scrum-team)

* Responsible for coping with incomplete artifact transparency.

* Serves the [Product Owner](#product-owner) in several ways
    - Finding techniques for effective Product Backlog management
    - Helping the [Scrum Team](#scrum-team) understand the need for clear and concise Product Backlog Items
    - Understanding product planning in an empirical environment
    - Ensuring the [Product Owner](#product-owner) knows how to arrange the Product Backlog to maximize value
    - Understanding and practicing agility
    - Facilitating Scrum events as requested or needed

### Non-Scrum Roles

* Only two meetings in which people outside the [Scrum Team](#scrum-team) are allowed to participate
    - [Sprint Planning](#sprint-planning)
        + The [Development Team](#development-team) may invite other people to attend the [Sprint Planning](#sprint-planning) in order to provide technical or domain advice.
    - [Sprint Review](#sprint-review)
        + The [Product Owner](#product-owner) is responsible for inviting the Key Stakeholders to the [Sprint Review](#sprint-review) meeting

#### Key Stakeholders

* Allowed to participate in the [Sprint Review](#sprint-review) meeting
    - Not allowed to participate in any other Scrum events

## Scrum Events

### Sprint Planning

* Time-boxed to a maximum of 8 hours for 1 month Sprints
    - For shorter Sprints the event is usually shorter

* Attended by the entire [Scrum Team](#scrum-team)
    - [Product Owner](#product-owner), [Development Team](#development-team) and Scrum Master all attend
    - Other people may be invited to attend in order to provide technical or domain advice

* Answers
    - How will the work needed to deliver the Increment be achieved?
    - What can be delivered in the Increment resulting from the upcoming Sprint?

* Does not answer
    - Who will be responsible for each item in the Sprint Backlog?
    - What new technologies could be used to speed up the [Development Team](#development-team) velocity?
    - What is the size of the Technical Debt and how it could be removed?

* Inputs to the [Sprint Planning](#sprint-planning) are
    - The Product Backlog
    - The latest product Increment
    - Projected capacity of the [Development Team](#development-team) during the Sprint
    - Past performance of the [Development Team](#development-team)

* Only work planned for the first days of the Sprint is required to be decomposed to units of one day or less.
    - The [Development Team](#development-team) should be able to explain to the [Product Owner](#product-owner) and Scrum Master how it indends to work as a self-organizing team to accomplish the [Sprint Goal](#sprint-goal) and create the anticipated Increment

### Daily Scrum

* Time-boxed to 15 minutes
    - No matter the size of the [Development Team](#development-team)

* Only the [Development Team](#development-team) can participate
    - Other people could attend but cannot participate

* Cannot be skipped

* Opportunity for the [Development Team](#development-team) to synchronize activities and create a plan for the next 24 hours

* Three main questions each member of the [Development Team](#development-team) should answer
    - What did I do yesterday that helped the [Development Team](#development-team) meet the [Sprint Goal](#sprint-goal)?
    - What will I do today to help the [Development Team](#development-team) meet the [Sprint Goal](#sprint-goal)?
    - Do I see any impediment that prevents me or the [Development Team](#development-team) from meeting the [Sprint Goal](#sprint-goal)?

### Sprint Review

* Time-boxed to a 4 hour meeting for 1 month Sprints
    - For shorter sprints hte event is usually shorter

* Attended by
    - The [Scrum Team](#scrum-team)
        + The [Product Owner](#product-owner)
        + The [Development Team](#development-team)
        + The Scrum Master
    - Key Stakeholders

* The result of the [Sprint Review](#sprint-review) is a revised Product Backlog that defines the probable Product Backlog items for the next Sprint.

### Sprint Retrospective

* Time-boxed to a 4 hour meeting for 1 month Sprints
    - For shorter Sprints the event is usually shorter

* The [Sprint Retrospective](#sprint-retrospective) is an opportunity for the [Scrum Team](#scrum-team) to inspect itself and create a plan for improvements to be enacted during the next Sprint.

* The purpose of the [Sprint Retrospective](#sprint-retrospective) is to
    - Inspect how the last Sprint went with regards to people, relationships, process, and tools
    - Identify and order the major items that went well and potential improvements
    - Create a plan for implementing improvements to the way the [Scrum Team](#scrum-team) does its work

* During each [Sprint Retrospective](#sprint-retrospective), the [Scrum Team](#scrum-team) plans ways to increase product quality by adapting the definition of "Done" as appropriate.

## Definition of "Done"

* The [Development Team](#development-team) is responsible for the creation of the Definition of "Done"
    - If the Definition of "Done" for an increment is part of the conventions, standards or guidelines of the development organization, all [Scrum Teams](#scrum-team) must follow it as a minimum.
    - If "done" for an increment is not a convention of the development organization, the [Development Team](#development-team) of the [Scrum Teams](#scrum-team) must define a Definition of "Done" appropriate for the product.
    - If there are multiple [Scrum Teams](#scrum-team) working on the system or product release, the [Development Teams](#development-team) on all of the [Scrum Teams](#scrum-team) must mutually define the Definition of "Done."

* Helps the [Scrum Team](#scrum-team)
    - DoD is used to assess when work is complete on the product Increment
    - Guides the [Development Team](#development-team) in knowing how many Product Backlog items it can select during a [Sprint Planning](#sprint-planning)
    - DoD ensures artifact transparency

* Accounts for
    - Conventions, standards and guidelines of the Organization
    - Definition of "Done" of other [Scrum Teams](#scrum-team) working on the same Product

* Does not account for
    - Definition of "Done" of other [Scrum Teams](#scrum-team) working on other products
    - Experience of the [Product Owner](#product-owner)
    - Advice of the Scrum Master

* During each [Sprint Retrospective](#sprint-retrospective), the [Scrum Team](#scrum-team) plans ways to increase product quality by adapting the definition of "Done" as appropriate.
