# Skill ladder for developers


## Level table

### Required sublevels 

| scope/level    | Level 0 | Level 1 | Level 2 | Level 3 | Level 4 |
|----------------|---------|---------|---------|---------|---------|
| delivery CODE  |   0-1   |    1    |    2    |    3    |    4    |
| delivery CI/CD |   0-1   |    1    |   1-2   |   2-3   |   3-4   |
| delivery QA    |   0-1   |    1    |   1-2   |   2-3   |   3-4   |
| contribution   |   0-1   |   0-1   |   1-2   |   2-4   |   3-4   |
| leadership     |   0-1   |   0-1   |   0-2   |   1-3   |   2-4   |
| communication  |   0-1   |    1    |   1-2   |   2-3   |   3-4   |
| **min SUM**    |  **2**  |  **5**  |  **8**  |  **14** |  **20** |

- sum calculation:

```javascript
// for level 1:
let scopes = [
 { min: 1, max: 1}, 
 { min: 1, max: 1},  
 { min: 1, max: 1}, 
 { min: 0, max: 1}, 
 { min: 0, max: 1},
 { min: 1, max: 1}
];
let sum = Math.round(scopes.reduce((total, scope) => total + scope.min + (scope.max - scope.min)/4,0));
```

### Sum boosts (perks)

* every perk adds to the total sum

- meetup talks: +1
- conference talks: +2
- regular duty person: +1
- hackaton organizer: +1

### Must-have requirements

| resp/level    | Level 0 | Level 1 | Level 2 | Level 3 | Level 4 |
|---------------|---------|---------|---------|---------|---------|
| value delivery|   no    |   yes   |   yes   |   yes   |   yes   |
| code review   |   no    |   no    |   yes   |   yes   |   yes   |
| AC analysis   |   no    |   no    |   yes   |   yes   |   yes   |
| mentoring     |   no    |   no    |   no    |   yes   |   yes   |
| tech research |   no    |   no    |   no    |   yes   |   yes   |
| processes     |   no    |   no    |   no    |   no    |   yes   |


## Responsibilities

### Level 0

#### Description
* A person who is constantly reinventing, learning and improving in order to be able to work on the product and start deliver values

#### Essential skills
* Basic knowledge of software engineering
* Writing of a readable/testable code
* Continuous learning
* Measurable progress
* Learning from mistakes

#### Nice-to-have skills
* Good communication
* Thirst for knowledge

#### Setbacks
* No significant progress
* No motivation
* Poor code quality

### Level 1

#### Description
* Developer who works on the product and delivers value

#### Essential skills
* Core knowledge of software engineering
* Core knowledge of the stack and the product
* Writing of an efficient code and tests
* Pointing out setbacks in meetings
* Reaching goals specified in education plan

#### Nice-to-have skills
* Good organizing skills
* Good collaboration with a team
* Reviewing other engineers' code
* Providing constructive feedback
* Proactive in meetings

#### Setbacks
* Many stories returned from QA
* Often asks for guidance

### Level 2

#### Description
* Developer who delivers high-quality value and reaches sprint goals

#### Essential skills
* Advanced knowledge of software engineering
* Deep knowledge of the stack and the product
* Very good collaboration with a team
* Contribution to user-story ACs
* Reviewing other engineers' code
* Reaches sprint goals

#### Nice-to-have skills
* Community involvement
* Provides guidance to junior developers
* Dives into new areas and suggests innovations

#### Setbacks
* Poor communication with a team
* Not active in problem-solving

### Level 3

#### Description
* Developer who knows his stuff and is a good resource for help and guidance

#### Essential skills
* Deep knowledge of software engineering
* Very good knowledge of the stack and the product
* Presented with projects of increasing complexity over time across multiple areas or domains of the code/product
* Dives into new areas and suggests innovations
* Provides guidance to junior developers
* Keeps the codebase healthy

#### Nice-to-have skills
* Monitor the outcomes of team’s actions
* Ability to make changes that affect larger architecture
* Participates in frequent code/design/architecture reviews
* Interview prospective candidates and provide thoughtful evaluations and feedback

#### Setbacks
* Fails to identify or communicate big roadblocks
* Underestimates timelines
* Doesn’t take operational excellence seriously


### Level 4

#### Description
* Save-the-day person who has a significant impact on the product, the team, the community, and keeps the wheel going by participating on innovations, newbies guidance and important architectural decisions

#### Essential skills
* Very good knowledge of software engineering, design patterns and solution architecture
* Is accountable for keeping codebase aligned with best practices
* Ability to make changes that affect larger architecture
* Reviews technical, leadership and team fit assessments
* Strategic initiative in a value stream

#### Nice-to-have skills
* Support, advocate, and sponsor for others to take leadership
* Works with senior managers & directors to ensure engineering effort is focussed on the most impactful areas for their value stream
* Tracks feature progress across the value stream
* Interview prospective candidates and provide thoughtful evaluations and feedback
* Acts as a mentor to other senior and staff engineers who are developing their own mentees

#### Setbacks
* Crunch time in the team
* Enforce his views on solution
* Doesn't maintain asshole-free environment

