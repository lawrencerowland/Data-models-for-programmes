# Data-models-for-programmes

# Purpose 
Applying graph databases to programmes of projects

For a fuller background and description, see https://lawrencerowland.github.io/2020/05/07/Data-models-for-Project-Portfolios.html

![](https://github.com/lawrencerowland/Data-models-for-programmes/blob/master/images/Digital-Transformation-Programme-Education-pared%20back-ego-graph.jpg)

# Example

This is a toy model. Upfront and ongoing discussion with stakeholders. Only then does it become a useful model.

- This model tries to ask the question about how to get the Programme Team, the Operations team, and the Strategy team to work separately and jointly on ensuring that a digital programme delivers what all parties expect

- Origin: Modelled around a Digital Transformation Programme, planned for University of East London. Based on public material on their website, particularly their Annual report. Some items like typical projects and services have been guessed where the report does not identify details.

- Instances: 150 nodes and 236 links that fall under a data schema with 13 node types and 14 link types.

- Each node and each link has the following properties: name, id.

- The data sits within a graph database (Neo4j) and therefore extra properties can be added

- This has been populated by cypher query (see cypher folder- it is very easy to run a Neo4jsandbox in the browser (after creating a free account) and copying this cypher query in and pressing the play button. 

- I use the desktop version of Neo4j, and does not require account and which is free, but sandbox gets you started. You
can run queries on the data from the database.

# Data model from a Business Operations perspective
IMAGE TITLES:
images/Data-model-from-Operations-perspective.png
																															
This is the corresponding consultation sheet for reviewing with the various operations teams
images/Sample-consultation-sheet-for-particular-operations-teams.png

Data model from the strategy perspective
images/Data-model-from-the-strategy-perspective.png

Sample consultation sheet for Strategy team
Sample-consultation-sheet-for-Strategy-team.png

Project view
images/project-view.png

Sample consultation sheet for particular projects
images/Sample-consultation-sheet-for-particular-projects.png

Full model blue print
images/Full-programme-data-model.png
https://www.yworks.com/yed-live/?file=https://gist.githubusercontent.com/lawrencerowland/35320891b44b07317cb008526bf08618/raw/2019 12 UEL full graph from Neo4j

Data model from Operations perspective

![](name//media/image1.png)![](name//media/image2.png)

Sample consultation sheet for particular operations teams

Data model from the strategy perspective

Sample consultation sheet for Strategy te![](name//media/image3.png)![](name//media/image4.png)![](name//media/image5.png)![](name//media/image6.png)am

Project view

Sample consultation sheet for particular projects

Full model blue print https://www.yworks.com/yed-live/?file=https://gist.githubuserconte![](name//media/image7.png)nt.com/lawrencerowland/35320891b44b07317cb008526bf08618/raw/2019 12 UEL full graph from Neo4j

The graph contains all the particular relationships relevant to the IT Programme.

These can be queried from the graph for presenting to the senior team, when making decisions

For instance

ACCOUNTABLE GROUPS

Board of Governors

Audit & Risk committee

Strategic Projects Team

CIO

New Groups aligned to risk areas (2019)

STRATEGIES

Vision 2028

2015 20 Management Plan

a new strategic planning framework (2019)

2018 2019 Management Plan for returning to surplus

Corporate Risk Mgt framework

People (staff) strategy

OBJECTIVES

1 Learning by doing

2 Creating and disseminating knowledge

3 Connecting to students, staff, communities

4 Developing our infrastructure

“Technology related business change”

Returning to surplus

Student recruitment activity

Improved student retention

Operating efficiencies

Likely challenges

REGULATORY CHANGE

TEF OFS regulatory compliance

UEL new strategic framework underway

2020 planned audits

BROADER UEL CONTEXT

Strategic risk management is weak

Margin pressure on future budgets

Boundary with the Digital 1st programme

Boundary between digital and non digital

COMMON DIGITAL PROGRAMME CHALLENGES

Digital transformation is poorly understood

Vague project scopes

Finalisation of cloud strategy

Existing team capability gaps

Single most important aspect of approach

This is a toy model

Upfront and ongoing discussion with you and stakeholders

Only then does it become a real approach

SUGGEST, LISTEN, CHANGE

Regularly reset Programme Outcomes

Build in Organisational change management

Agree Agile / Waterfall type per project

Use UEL faculty and research

Involve Business change managers early

Link strategy with programme with product with Operations

SYSTEMATIC APPROACH TO RISK & REGS

Build business analysis approach to regulation

Programme schedule to include assurance dates

Understand UEL’s new Risk protocols

Define cross Programme governance

Refresh ITIL compliance

APPROPRIATE PROJECT APPRAISAL

Identify which projects are essential

Have different criteria for approving proofs of concept

Review existing bottom up project ideas

Clearly link with enterprise and solution architectures

Most of the approach elements managed within a suitable work-package of the Programme

| Operations                           | Services           | Consumers                      |
| ------------------------------------ | ------------------ | ------------------------------ |
| Infrastructure                       | Amazon Educate I   | Staff                          |
| IT Applications                      | Office 365         | Students                       |
| IT Services                          | Ebooks             | Community                      |
| IT Service Support                   | Lecture capture    | Applied Health College         |
| Academic & employer Partner office   | Moodle             | Professional Services College  |
| Academic Registry                    | Password           | Graduation School college      |
| Centre for Student Succcess          | Print centre       | Arts Tech & Innovation college |
| Conference & Meeting Room hire       | LinkedIn learning  | Research                       |
| Estates & facilities                 | Software centre    | KTPs                           |
| External relations                   | Windows 10         | Sustainability Institute       |
| Finance                              | Wifi               | IHHD                           |
| Health & Safety                      | Print copy & scan  | Centre for Prof. Policing      |
| HR Services                          | ITrent             | Continuum centre               |
| Learn, Teaching & Student Experience | Windows Active Dir |                                |
| Library & learning services          | MS Dynamics 365    |                                |

| Programme approach                                      | Description                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Suggest, listen, change                                 | Of course I have no idea how UEL's  specific Digital Transformation should be run  I am answering the interview ‘exam question’ but most of this will be wrong  What will be crucial will be to  suggest ideas, but then to listen over time to stakeholders that know the Organisation  and change the approach accordingly   |
| Build business analysis approach to regulation          | Build a robust , specific business analysis approach to regulatory capture                                                                                                                                                                                                                                                     |
| Programme schedule to include assurance dates           | Programme schedule anticipates assurance and audit dates as well as delivery milestones (IPA consequential assurance framework)                                                                                                                                                                                                |
| Understand UEL’s new Risk protocols                     | Work early with Strategic Projects Team to understand emerging Risk protocols                                                                                                                                                                                                                                                  |
| Identify which projects are essential                   | From the start, be clear which projects are essential, and which can be delivered in other ways                                                                                                                                                                                                                                |
| Regularly reset Programme Outcomes                      | Plan for regular reassessments of Programme Outcomes and Benefits with main stakeholders                                                                                                                                                                                                                                       |
| Have different criteria for approving proofs of concept | Have a small separate budget for high risk, high reward proofs of concept and experiments that are not yet core to UEL business and have lower risk hurdle rates for accepting lower experiment budgets (see Deloitte 2012)                                                                                                    |
| define cross Programme governance                       | Use Portfolio Management best practice to define cross Programme governance early                                                                                                                                                                                                                                              |
| Build in Organisational change management               | Flexibility is inevitable so build in Organisational change management work package from the start, so that behaviours and culture can lead governance, rather than the other way round  This can include the use of the excellent Open Group Digital Practitioner framework for Digital Transformations                       |
| Review existing bottom up project ideas                 | Review existing bottom up project ideas and proposals to meet top down Digital Transformation objectives i e  there are likely to be good ideas already in development from the IT and other Departments,                                                                                                                      |
| Clearly link with enterprise and solution architectures | Clearly link enterprise and solution architectures to programme archite, e.g. by applying the IT4IT data model                                                                                                                                                                                                                 |

| Programme Challenges                        | Programme approach                                        |
| ------------------------------------------- | --------------------------------------------------------- |
| Digital transformation is poorly understood | Suggest, listen, change                                   |
| TEF   OFS regulatory compliance             | Build business analysis approach to regulation            |
| UEL new strategic framework underway        |                                                           |
| 2020 planned audits                         | Programme schedule to include assurance dates             |
| Strategic risk management is weak           | Understand UEL’s new Risk protocols                       |
| Margin pressure on future budgets           | Identify which projects are essential                     |
|                                             | Regularly reset Programme Outcomes                        |
|                                             | Have different criteria for approving proofs of concept   |
| Boundary with the Digital 1st programme     | define cross Programme governance                         |
| Boundary between digital and non digital    | Build in Organisational change management                 |
| Vague project scopes                        | Review existing bottom up project ideas                   |
|                                             | Clearly link with enterprise and solution architectures   |
| Finalisation of cloud strategy              | Link strategy with programme with product with Operations |
|                                             | Agree Agile Waterfall type per project                    |
| Existing team capability gaps               | Use UEL faculty and research                              |
|                                             | Involve Business change managers early                    |
|                                             | Refresh ITIL compliance                                   |

| Relevant Work-package             |                                                           |
| --------------------------------- | --------------------------------------------------------- |
|                                   | Programme Challenges                                      |
| IT dept interface mgt             | Regularly reset Programme Outcomes                        |
| Project selection                 | Have different criteria for approving proofs of concept   |
| Govenance arrangements            | define cross Programme governance                         |
| Project Definition                | Build in Organisational change management                 |
| Project innovation                | Review existing bottom up project ideas                   |
| Enterprise architecture alignment | Clearly link with enterprise and solution architectures   |
| Programme approach                | Link strategy with programme with product with Operations |
|                                   | Agree Agile Waterfall type per project                    |
| Programme collaboration           | Use UEL faculty and research                              |
| Business & transition management  | Involve Business change managers early                    |
| IT dept interface mgt             | Refresh ITIL compliance                                   |
