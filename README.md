requirement-analysis
Requirement Analysis in Software Development

In every software development project, proper requirements analysis is vital for the successful deployment of the project. This repository serves as a layout for the requirement analysis process in a project.

What is Requirement Analysis?
Requirements analysis is a crucial phase in software development lifecycle (SDLC) where the project gathers, analyzes, and defines the requirements of the software product to be developed.

Why is Requirement Analysis Important?
In the SDLC process, requirements analysis is important as it:

Aids in clarity and understanding of what the stakeholder needs are
Clearly defines the scope of the project, preventing scope creep
Provides a solid foundation for designing and developing systems
Facilitates accurate estimation of project cost, resource, and time
Key Activities in Requirement Analysis
Requirement Gathering - using interviews, surveys, and workshops to collect initial requirements from stakeholders.
Requirement Elicitation - Refining and elaborating on the gathered requirements through brainstorming, focus groups, and prototyping techniques
Requirement Documentation - Using requirement specification documents, user stories, and use cases to capture the requirements in a detailed and structured format.
Requirement Analysis and Modeling - Creating models to visualize and understand requirements
Requirement Validation - The review and validation of the requirements with stakeholders in addition to defining the acceptance criteria to ensure traceability
Types of Requirements
Functional Requirements
Functional requirements describe what the system should do. For the case study provided, these are the functional requirements:

Hotel Management Service - The hotel managers/owners will be using this to manage hotel related information and services
Customer Service (Search + Booking) - Here, customers can search and book a hotel
Property listings/View Booking Service - a customer can view old and current bookings on the app.
Non-functional Requirements
Non-functional requirements describe how the system should perform. FOr the case study provided, these are the non-functional requirements:

Performance and Reliability - Content Delivery Network (CDN) and Message Queue Systems have to work together to provide fast delivery on Internet content
Usability - The CDN app shows the content to customers like nearby hotels, recommendations, and offers
Scalability - Archiving of old data, increasing the database (to handle increased queries) and handling a high volume of data is done with various Database Management Systems
Performance - Through Redis, a caching server, requests made for recent data is readily available reducing the loading time on the app side
Use Case Diagrams
Use case diagrams serve as visual representation of interactions between users and the system. in the diagrams, identity actors such as guests or registered admin users get to interact with several use cases such as searching and booking of the desired properties

Benefits of Use Cases Diagrams:

They provide a clear visual representation of system functionalities
They help in identifying and organizing system reqiurements
They facilitate communication among stakeholders and development team
alx-booking-uc
![442533979-4f16c198-5620-40f6-9797-e67379356041](https://github.com/user-attachments/assets/7867ece0-908f-4705-9174-838dee6454c7)

Acceptance Criteria
Acceptance criteria is needed to establish clear criteria for feature completion. It defines what is referred to as "Done" in a project or in sub-tasks related to a project thereby maintaining quality and meeting user expectations.

An example of acceptance criteria: "In the checkout journey of the booking process, a user must be able to select the arrival and departure dates from a drop-down calendar option. The selected dates should further be displayed on the reservation page and on the order confirmation email."
