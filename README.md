[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15236613&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software Engineering is the process of developing, testing, maintaining and deploying computer applications products like websites and apps.

What is software engineering, and how does it differ from traditional programming?
Software engineering is the process of designing, developing, testing, and maintaining computer applications. This involves a broader set of activities such as systematic design, development, testing, and maintenance of software system, unlike traditional programming where it primarily involves writing code to create software applications or to solve specific problem. Basically, programming is the process of translating algorithms into a programming language that a computer can understand and execute by focusing on coding and debugging.
Software Development Life Cycle (SDLC):
SDLC is a structured process that encompasses several phases required to build a high-quality, low-cost software that meets and exceeds all customer expectations in the shortest possible production time.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
There are several phases involved in SDLC.The phases are:
1. Initiation: This is the first phase and it involves defining projec goals and objectives, conducting feasibility studies(done to determine software's technical and commercial viability), Identifying stakeholders and developing the project charter.
2. Planning: At these phase you develop a project management plan. This is where you define the scope of the project, schedule and the budget. The engineer also plan resources to be used during the entire project, the means and ways of communication for smooth and seamless operation and also developing the risk management that will be esential incase faced with a setback during the development.
3. Execution: This is a crucial phase where the real work of developing softwares takes place. Here, you assign tasks on who will do what during the project timeline. You also implement project plans; could be in stages. The engineer also manages the team members(UI/UX team, database team, legal team, etc) and communication. Lastly, you have to ensure quality assurance process are followed by the team so as to deliver a software that meets and exceeds client's expectations and demand.
4. Monitoring and controlling: This phase involves tracking the progress of the project, perfoming quality control, managing changes to scope, schedules, and costs. It also imperative to report perfomance to stakeholders.
5. Closure: After following the above phases we come to the final phase where you finalize all project activities, obtain a formal acceptance of deliverables from the assigned teams, release project resources(since you no longer need them) and lastly, document lessons learned and archive project documents.
Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
 Both agile and waterfall are project management methodologies.
 a. Agile: This model follows an iterative and incremental approach to project management and software development. In this model, testing is done after each step/stage thus emphasizing on flexibility, collaboration, and customer feedback. 
 The advantages of this model include quick response to changes, regular customer feedback which contributes highly to the overall project goals.
 The disadvantages are less predictability and requires a lot of customer involvement which can cause too much repetition of processes delaying the whole timeline or rather taking longer than expected.
 b. Waterfall: This particular model follows a linear and sequential approach to software development where one phase has to be completed before moving to the next phase. Testing is done at a later time which can be disadvantageous because if something wrong was done in a particular phase you will have to go back and redo the whole thing and by the time everything is in place the whole project might already be outdated and no longer needed.
 The merits associated with this model is clear structure and documentation and easy management due to its rigidty.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirement engineering is a process that involves identifying, documenting, and managing the needs and requirements of stakeholders for a software system.This is a crucial process as it ensures the final software product meets the expectations of our customers.
The process of requirement engineering is:
1. Elicitation: This involves taking interviews and workshops with the stakeholders to gather their needs and discuss their requirements. It also involves using surveys/questionnares in collecting requirements from a pool of users.
2. Analysis: At this process we focus on key factors such as conflict resolution, requirement prioritization and feasibility studies by addressing the requirements from different stakeholders that conflict with one another, determining the essence of the different requirements and assessing whether the requirements fall within the stated budget, time and technology.
3. Specification: Documentation is the key factor here where detailed description of the system is written down while using visually representations such as case diagrams, gantt charts to represent the requirements.
4. Validation and verification: At this step, approval from the stakeholders is needed. This can be achieved by presenting the requirements to stakeholders and creating prototypes of the system to validate with the stakeholders.
5. Management: At this stage, tracking the requirements and its implementation across the development cycle is imperative.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity is a principle in software design that involves breaking down the software system into smaller manageable units called modules where each module is associated with a particular functionality that makes up part of the whole system functionality
Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
1. Unit testing: This is a type of isolation testing  done to test individual components or units of code to verify that each unit perfoms as expected using tools such as JUnit, TestNG
2. Intergration testing: Tests the interaction between the units or components that form the complete system. This is done to ensure that all the units work together as one to achieve the common functionality.
3. System testing: This type of testing tests the completed intergrated  system as a whole to validate the system's compliance with the specified requirements.
4. Acceptance testing: Tests the system's readiness to deliver as designed and its acceptance by the end users.This is done to make sure system meets the its business goals and is ready to be deployed.
 Testing is crucial in software development as it helps ensure the software meets and exceed the expectations leading to user's satisfaction while lowering the long-term costs.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control system(VCS) is a tool that helps manage changes to source code from developers and other collection of files intergral to development over time. VCS tracks any modifications, contains a history book of logs and allows multiple developers to collaborately work on projects efficiently. VCS are important as they enhance collaboration, ensuring code quality and providing a robust framework for managing the complexity of software development.
The most popular VCS include:
1. Perfoce helix core: 
      a. File locking - supports locking files to prevent certain conflicts in workflows such as accidental modifications and deletion.
      b. Centralized vcs - Because of its central repository, it scales well for large team of collaborating developers and related projects.
      Fine grained access control - Needs authorization to control access at various levels.
2. Git:Git is a VCS that stores code in a repository and organizes projects in a portfolio. Features include;
      a. Distributed vcs - Every developer has a local copy of the entire history of the project
      b. Branching and merging - Allows creation of branches different but can also relate to the main branch which can be later merged into the original branch.
      c. Stagin area - Allows holding of changes before commiting them.
      d. Community - Has an extensive support from a large number of users intergrated with numerous tools and services.
3. Subversion(SVN): Is a cetralized  VCS designed to manage changes to files and directories over time. Features include:
      a. Centralized repository - All files are stored in a central location facilitating collaboration by providing accessible to all team members.
      b. Atomic commits - Ensures the commits are either complete or empty preventing partial updates and maintaining intergrity of the highest order.
      c. Branching and tagging - Supports creation of lightweight branches that intergrates effectively with the repository structure. It also tags specific points and entries such as releases.
4. Mercurial: This is a distributed VCS designed to handle large projects. Features include:
      a. Distributed VCS - Every developer has a complete copy of the repository enabling one to work offline.
      b. Simple and intuitive commands - Due to its straight forwad command line, it is user friendly and easy to interact with it.
      c. Intergrated web interface - Has a built in web server for browsing repositories and tracking project's history.  
Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
A software project manager(SPM) oversess the planning, execution, and closing of software projects ensuring they meet the specified requirements and stay within the budget. Basically, a software project manager ensures successful delivery of software projects.
The responsibilities of software project manager are, but not limited to the following:
1. Project planning: The roles of SPM under project planning are;
       a. Scope definition - Establishing of project's scope, goals, deliverables.
       b. Sheduling - Creating a detailed project timeline, including milestones and constraints
       c. Resource allocation - Determining resources i.e human, financial and technical required and assigning tasks to teams.
2. Risk management : Identifying risks associated with the project and ways of mitigating them by developing strategies to handle the risks
3. Budget management: setting up a budget that lies within the scope and monitoring the expenditures to ensure it remains within the proposed budget.
4. Stakeholder management: Identifying all the parties involved and keeping them up-to date with the progress of the entire project.
5. Quality assurance: Defining quality standards and ensuring the final product meets the required standards.
Challenges faced include:
1. Uncontrolled changes or continous growth in project's scope.
2. Time management where delays are experienced due to project timeline not balancing with task durations
3. Challenge in ensuring optimal resource allocation and utilization.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software maintenace is perfomed after deployment and it involves modifying and updating software applications to correct faults and improved perfomance aimed at meeting the ever-evolving user's needs.
The different types of maintenance activities include:
1. Corrective maintenance - Involves debugging, error correction to ensure the software function as intended and any issue is resolved.
2. Adaptive maintenance - Involves adjusting the software to work in a new or changed environment so as to remain funtional when external conditions are changed.
3. Perfective maintenance - Involves enhancing the software to improve perfomance or add new features.
4. Preventive maintenance - Proactive changes perfomed to prevent future problems and extend the software's life.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Some of the common ethical issues that software engineers face include:
1. Biasness and fairness - Biasness in algorithms that discriminate based on race, marginalized groups or other factors that raises unfairness concerns. A good example is creating AI systems that discriminate people based on their skin color or complexion thus not benefiting a certain group of people.
2. Privacy and data security - Colleting more data than the required and selling that to data mining companies poses a great privacy issue because you dont know how the confidential data is going to be used by the third party companies.What if it falls in the hands of scammers puting users into risks of being scammed.
3. Quality and safety - Some systems might cause harm to the users. agood example is a software system developed with photosensitive capabilities which can cause photosensitive epilepsy in some users.
4. User autonomy - Developing a system that manipulates users into making decisions that are against their best interests.

Software engineers can make sure they adhere to ethical standards in the following ways:
1. Creating awareness and increase their knowledge ny attending workshops and seminars to stay informed.
2. Adopting established ethical frameworks such as the IEEE
3. Maintaining transparency in developing the system by stating reasons behind certain sudden changes and choices.
4. Adhering to legal and regulatory compliances such as the HIPAA which is guides on healthcare systems
5. 

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
