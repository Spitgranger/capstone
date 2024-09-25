
## Problem Statement and Goals

### Team 15, SyncMasters
  
Mitchell Hynes\
Akshit Gulia\
Richard Fan\
Kyle D'Souza\
Rafeed Iqbal

Table 1: Revision History
| **Date**  | **Developer(s)** |  **Change**|
|---------- | ------------------ | ------------------------ |
|  17/09/2024 |  Whole team  |  Initial Review and formatting of problem statement |
|      |       |   |
  
# 1 Problem Statement

## 1.1 Problem

The City of Hamilton, Water Division requires an application to assist in the management and security of their water and wastewater stations.
Stations are visited by internal staff and external contractors regularly, but no electronic log of their visit to site exists to confirm work that was performed.
This makes it difficult to verify work completion and accurate invoicing.
Each station has many documents associated with it (such as entry protocols, hazard assessments, etc) which are frequently updated and need to be effortlessly redistributed to relevant parties as required.
This is currently completed manually and is very time consuming for the stakeholder and prone to human error.
Many stations have site specific information, which is difficult to capture in a single document.
Instead, a dynamic application which displays only information relevant to that station as it is needed would be advantageous.
Information needs to be easily accessible to authorized site visitors.

Many documents require signing, and currently it is a manual process to distribute and collect routine signatures. 
This functionality currently requires the stakeholder to use multiple applications. The stakeholder also currently has many different computer applications for documentation storage. 
Each has a different standard for storing and managing that information. This leads to duplication and outdated documents in many locations, rather than a single source of truth.
The stakeholder requries contract management tools including syncing of contract files to the application and automatic alerts when documents, training, or signatures are set to expire.

Directly related to station access is a management system for contractors. This includes the ability to collect and distribute contract documentation, contact information, training, and other records.
A key control management subsystem would be beneficial to view key distribution in real time, as this is currently managed in a separate application.
A system to authenticate users at stations prior to access would improve visibility and protection.
A digital key system should control access and entry to the station approved from a work order generated in the work order system.

## 1.2 Inputs and Outputs

### Inputs 
* User login information for staff, internal contractors, and visitors.
* Uploading of documents.
* Signing of documents.
* Completion of training.
* Verification of arrivals and departures from the plant for contractors and internal staff.
* Adding of new staff and contractors.

### Outputs 
* Station documentation and documentation authors.
* Station maps and access protocol information.
* Station forms.
* Site contact information.
* Information on projects.

## 1.3 Stakeholders

The stakeholder for this project is the City of Hamilton, Water Division. 
Primary stakeholders with the City are the Facilities team, SCADA (Supervisory Control and Data Acquisition) team, and Corporate Security. 
Depending on what is decided during the requirements gathering process, other stakeholders from the City may need to be included in the project, such as City IT.
* City of Hamilton, Water Division. Primary stakeholder and client for the project.
* Facilities Team. Subdivision of the primary stakeholder.
* SCADA (Supervisory Control and Data Acquisition). Subdivision of the primary stakeholder.
* Corporate Security. A stakeholder with an interest regarding Hamilton Water station security.

## 1.4 Environment

* Software: Windows 10 operating system, android, iOS.
* Hardware: Laptop computers, tablets, smartphones.

# 2 Goals
| Goals | Rationale |
| --- | --- |
| The system enables the synchronization of files across distributed consumers | This is a basic goal that must be achieved for the proposed system to be useful. This involves both file synchronization and conflict resolution. |
| Intuitive GUI with high learnability. | The interface of the system should be easy to understand for first-time users as many of them will be contractors logging in for the first time. |
| Safety of Client Documents | The application should ensure that the client’s internal documentation is secure. |
| Accurate verification of users at stations | The application should be able to accurately verify that a user is at a specific station. This will provide visibility into who is at what station. |
| Should integrate with current business practices of client. | The project aims to assist the stakeholders and provide value as a more efficient and secure method of completing existing tasks. It should not interfere with current business processes or create additional workload. |

# 3 Stretch Goals
| Goals | Rationale |
| --- | --- |
| Demonstrate the advantage of a single centralized platform instead of multiple disconnected platforms.| Hamilton Water has applications which do not communicate between each other. Loss of information and working in “silos” is common as a result. Demonstrating the benefits of a platform which integrates the features of separate applications into one would be advantageous. |
|Expand the platform to be a contract management system, capable of having contract management tools accessible to authenticated project managers. |This would enable a greater integration of station and contractor documentation directly into the projects that utilize this information. |
| | |
# 4 Challenge Level and Extras

The challenge level for this project is a general challenge level. This designation was decided because we do not believe there will be a research element required.
The extras for this project will be conducting user testing and developing a user manual. These extras are a good choice for this project as it is being developed for a real client, with the objective of creating a usable tool.
Extensive user testing and documentation will be critical for its long term use and maintenance by the client.

# Appendix --- Reflection

The purpose of reflection questions is to give you a chance to assess
your own learning and that of your group as a whole, and to find ways to
improve in the future. Reflection is an important part of the learning
process. Reflection is also an essential component of a successful
software development process.

Reflections are most interesting and useful when they're honest, even if
the stories they tell are imperfect. You will be marked based on your
depth of thought and analysis, and not based on the content of the
reflections themselves. Thus, for full marks we encourage you to answer
openly and honestly and to avoid simply writing "what you think the
evaluator wants to hear."

Please answer the following questions. Some questions can be answered on
the team level, but where appropriate, each team member should write
their own response:

1.  What went well while writing this deliverable?

Mitchell: 
We had great and open communication with the City during this deliverable which greatly aided us in developing the problem statement.
Our team effectively documented the actions we took and helped eachother learn how to use the git workflow for developing our project.

2.  What pain points did you experience during this deliverable, and how
    did you resolve them?

3.  How did you and your team adjust the scope of your goals to ensure
    they are suitable for a Capstone project (not overly ambitious but
    also of appropriate complexity for a senior design project)?
