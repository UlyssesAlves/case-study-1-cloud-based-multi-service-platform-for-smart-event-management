## 1 Overview
This *technical design document* describes in detail all the aspects related to the **Cloud-Based Multi-Service Platform for Smart Event Management** software development case study project.

It begins stating the purpose of the project and what are its target audiences.

Then it provides a summary for this case-study project, describing its scope, constraints, key requirements and primary features.

A high level system architecture is also included, followed by lower level software design specifications for the data, components, interfaces and user interfaces that will be required to build this system.

Towards the end of this document there's a section discussing the assumptions and dependencies that were pondered when putting this project together.

The document ends with a glossary of technical terms which are relevant for facilitating the understanding of everyone involved in this project.
## 2 Purpose
The information here presented is essential for anyone interested in learning more about this case study goals and the benefits it can bring to those who take their time to work on it.
## 3 Target Audience
- Software developers, software engineering students and people in general who want to: 
	- learn and evolve their skills through working on software development tasks that are glued together in the context of a case study of real world proportions and complexity.
	- learn and practice new programming languages in order to match a higher number of job openings technical requirements.
	- integrate multiple technologies, skills, tools and programming languages to build a solution that is more robust, complete and complex than the average examples and exercises you may find elsewhere.
	- learn each one of the technologies selected to build this case-study software development project.
## 4 Project Summary

### 4.1 Scope [^2][^3]

#### 4.1.1 Name
**_Cloud-Based Multi-Service Platform for Smart Event Management_**
#### 4.1.2 Description
The system is a **cloud-native platform** for managing large-scale events (conferences, concerts, workshops) with real-time analytics, ticketing, and personalized recommendations. It will integrate multiple services, each implemented in different languages, and leverage AI tools for development and intelligent features.
#### 4.1.3 Goals
Serve as a didactic, cloud-based, feature rich, multi-service and multi-platform system which presents to its implementers a great and unique opportunity to learn a diverse and multifaced set of technologies, programming languages and concepts that will prepare them for working on real word projects of similar or higher level of complexity.
#### 4.1.4 Deadline
This is a long term case-study project, which at this time does not have a planned deadline of when it should be finished.
#### 4.1.5 Manager
This project was conceived by *Ulysses Alves (https://www.linkedin.com/in/ulysses-alves/)* and is managed by him.
#### 4.1.6 Deliverables
- Free software engineering and programming lectures in the context of this project's content and development. Subscribe to [Zoe Psomí Software Engineering's channel in YouTube](https://www.youtube.com/@zoepsomi) to receive updates on those lectures.
- Artifacts related to this project development (documentation, architecture, planning, source code, test plan, deployment plan, release plan, etc). This items will be made available in the public GitHub repository https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management as soon as they are created.
- Full and functional system, implemented according to its documented requirements, architecture, goals and plan.
#### 4.1.7 Tasks and Activities
- The video lectures related to this project will be [hosted on YouTube](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV) to demo the implemented features, technologies used and the processes followed to implement the proposed case-study system.
- The tasks and activities required to implement this project are organized as issues, deadlines and other planning related items on the [project public GitHub repository](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management). 
	- Interested people may open issues and write comments on existing issues, in order to improve their understanding and learning.
- The actual implementation of the system will take place as time allows. Refer to the Constraints section of this document for more information.
	- You may decide to try and implement your own version of this case-study system specification. This would be the most effective and recommended way for you to take full advantage of all of the learning material that we will be providing in this[ project video lessons](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV).
#### 4.1.8 Exclusions (Not In Scope)
- This is **not a commercial product**, but rather a learning endeavor and didactic opportunity to learn and grow as software developers.
- This project will not accept pull requests.
	- All the implementation will be taken care of by its owner. 
	- If you wish, you may clone its public repository to study the source code and to run it in your own environment.
- There will be no support support team responsible for helping users to operate this system.
	- Following the [video lectures](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV) should be enough for learning both how to develop and how to operate the case-study system.
#### 4.1.9 Constraints
##### 4.1.9.1 Budgets
- If you wish to financially contribute to this project, in benefit of the software development community, donations are welcome and are being accepted through PayPal at Zoe Psomí company's donations page.
##### 4.1.9.2 Timelines
- There are no deadlines defined for this project.
- The project will evolve at a pace that depends on how much free time Ulysses will be able to get to work on it.
- Current progress and scheduled/planned tasks can be viewed on the [project's public repository at GitHub](https://github.com/users/UlyssesAlves/projects/4).
##### 4.1.9.3 Resources
- This is a [voluntary project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management) run by [Ulysses Alves](https://www.linkedin.com/in/ulysses-alves/).
- He is basically doing all the technical work involved, including:
	- Documentation
	- Architecture
	- Planning
	- Implementation
	- Test
	- Deploy
	- Release
- [Ulysses](https://www.linkedin.com/in/ulysses-alves/) is also the person working on: 
	- recording and editing the [video lessons/lectures/demos related to this project](https://www.youtube.com/watch?v=C4tE1kZNrX4&list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV).
	- marketing and promoting the project for reaching out as many people as possible, who might be interested in learning more about software development through [this project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management).
		- We would appreciate any marketing contributions to [this project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management). 
		- Simple acts like sharing the [video lectures, subscribing to our channel, liking the videos and writing comments](https://www.youtube.com/watch?v=C4tE1kZNrX4&list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV) would be tremendously helpful and highly appreciated.
		- [Starring our repository, watching it, forking it](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management) and interacting with us in any way would let us know that [the project](https://github.com/users/UlyssesAlves/projects/4) is reaching its main goals. 
		- So, please let us know how to better serve you and the community as we work to give life to this project and to keep it alive.
#### 4.1.10 Key Requirements
- User Management Service
- Event Management Service
- Ticketing Service
- Recommendation Engine
- Frontend
#### 4.1.11 Primary Features
- Web application for users (React + Node.js)
- Backend microservices (C#, Python, Go)
- AI-powered recommendation engine
- CI/CD pipelines for automated deployment
- Hosted on a major cloud (AWS, Azure, or GCP)