# Requirement Analysis in Software Development
A repository that explains requirement analysis in web development. A lesson taught from ALX-PRO Front End Development.
# What is Requirement Analysis?
Requirement Analysis: is the process of **identifying, gathering, analyzing, and documenting** the needs and expectations of stakeholders for a new or modified software system.
It helps ensure that the software developed will meet user needs, business goals, and technical feasibility.

In simpler terms, it’s the foundation phase where developers and clients agree on *what the system should do* before any actual coding begins.

  *Purpose of Requirement Analysis*

The main goal of requirement analysis is to ensure that:

* The software project has **clear, complete, and accurate requirements**.
* There is a **common understanding** between developers, clients, and users.
* The final product will **satisfy user needs** and function as expected.


  *Steps Involved in Requirement Analysis*

1.  *Requirement Gathering*

   * Collect information from users, clients, and stakeholders.
   * Techniques include interviews, surveys, brainstorming sessions, observations, and document analysis.

2.  *Requirement Elicitation*

   * Clarify and refine the gathered information to understand what users truly need (not just what they say they want).
   * Example: Discussing use cases and workflows to uncover hidden or implicit needs.

3.  *Requirement Analysis and Modeling*

   * Examine the collected data to detect conflicts, redundancies, or feasibility issues.
   * Create models such as data flow diagrams (DFD), use case diagrams, or entity-relationship diagrams (ERD) to visualize requirements.

4.  *Requirement Specification*

   * Document all approved requirements clearly and systematically in a **Software Requirement Specification (SRS)** document.
   * This serves as a formal agreement between stakeholders and the development team.

5.  *Requirement Validation*

   * Verify that all requirements are correct, complete, consistent, and aligned with business objectives.
   * Conduct reviews, walkthroughs, and prototypes to confirm understanding.

6.  *Requirement Management*

   * Track, update, and manage changes to requirements throughout the project’s lifecycle.
   * Prevents scope creep and ensures version control.

  *Types of Requirements*

1. *Functional Requirements:*

   * Define *what* the system should do.
   * Example: “The system should allow users to log in using an email and password.”

2. *Non-Functional Requirements:*

   * Define *how* the system performs.
   * Example: “The system should respond to user actions within 2 seconds.”

3. *User Requirements:*

   * Expressed in natural language from the end user’s perspective.
   * Example: “Teachers should be able to upload student grades easily.”

4. *System Requirements:*

   * Technical and detailed specifications that guide developers.
   * Example: “The database must support 10,000 concurrent users.”

  *Importance of Requirement Analysis in SDLC*

Requirement Analysis plays a **crucial role** in every phase of the Software Development Life Cycle (SDLC):

| **SDLC Phase**                 | **How Requirement Analysis Helps**                                                      |
| ------------------------------ | --------------------------------------------------------------------------------------- |
| **1. Planning**                | Provides a clear understanding of the project scope, time, and cost estimation.         |
| **2. Design**                  | Guides system architecture, database, and user interface design based on defined needs. |
| **3. Implementation (Coding)** | Acts as a blueprint for developers to follow when writing code.                         |
| **4. Testing**                 | Helps testers design test cases based on specified requirements.                        |
| **5. Deployment**              | Ensures the system delivered aligns with what the client requested.                     |
| **6. Maintenance**             | Makes it easier to manage changes and updates by referring to documented requirements.  |


# Why is Requirement Analysis Important?

1. *Prevents Miscommunication:*
   Ensures all stakeholders share the same understanding of the project goals.

2. *Reduces Rework and Costs:*
   Fixing issues at the requirement stage is cheaper than after development.

3. *Improves Quality:*
   Leads to building software that truly satisfies user needs.

4. *Saves Time:*
   A clear plan prevents confusion and delays during later stages.

5. *Ensures Project Success:*
   Most software project failures result from poor or incomplete requirement analysis.


*Example*

Imagine developing a **school management system**:

* If requirements are not clearly defined, developers might build a student attendance module while the school actually needed a grade reporting system.
* Proper requirement analysis ensures that every feature—attendance tracking, grading, or fee payment—is clearly defined, understood, and implemented correctly.

# Key Activities in Requirement Analysis


*1. Requirement Gathering*

* This is the **first step** in the requirement analysis process.
* It involves **collecting information** about the system from all relevant stakeholders such as clients, end users, and business managers.
* The goal is to **understand what the users need** from the new or improved system.
* **Techniques used include:**

  * Interviews and questionnaires
  * Observation of current system use
  * Brainstorming sessions
  * Reviewing existing documentation and reports
* The output of this stage is a **list of raw user needs and expectations**.


*2. Requirement Elicitation*

* This activity focuses on **clarifying, refining, and expanding** the gathered requirements.
* It helps uncover **hidden or unclear needs** that users might not express directly.
* The analyst works closely with stakeholders to ensure the requirements are **realistic, feasible, and relevant**.
* **Common techniques include:**

  * Use case analysis
  * Workshops and focus group discussions
  * Scenario-based discussions
  * Prototyping or mock-ups
* The result is a **comprehensive and well-understood set of requirements**.



*3. Requirement Documentation*

* This activity involves **recording and organizing** all the analyzed requirements into a clear and structured format.
* The main purpose is to create a **Software Requirement Specification (SRS)** document that serves as a formal agreement between clients and developers.
* The SRS should include:

  * Functional and non-functional requirements
  * System constraints and assumptions
  * Diagrams and models where necessary
* The documentation ensures **traceability, clarity, and consistency** of all requirements.


*4. Requirement Analysis and Modeling*

* This step involves **studying the documented requirements** to identify conflicts, redundancies, or gaps.
* Analysts use models and diagrams to **represent the system visually**, making it easier to understand complex requirements.
* **Common modeling tools include:**

  * Data Flow Diagrams (DFDs)
  * Use Case Diagrams
  * Entity-Relationship Diagrams (ERDs)
  * Flowcharts and process models
* This activity ensures that requirements are **logical, consistent, and technically feasible** before development begins.


 *5. Requirement Validation*

* The goal of validation is to **confirm that the final set of requirements accurately reflects user needs** and project goals.
* It checks that requirements are **complete, correct, realistic, and testable**.
* **Validation techniques include:**

  * Reviews and walkthroughs
  * Prototyping and user feedback sessions
  * Test case generation and feasibility checks
* This ensures that the requirements are **approved by stakeholders** before design and implementation start, preventing costly changes later.

* Types of Requirements

## ⚙️ **Functional Requirements**

Functional requirements describe **what the system should do** — the specific operations, features, and services it must perform to meet user and business needs.

### 🔸 **User Management**

* The system must allow **customers to create accounts**, log in, and manage their profiles.
* Hotel managers must be able to **register their hotels**, providing details such as hotel name, location, room types, pricing, and amenities.
* Administrators must have access to **view, edit, or remove** user and hotel records.

### 🔸 **Hotel and Room Management**

* Hotel managers must be able to **add, update, or delete** room details (availability, prices, and descriptions).
* The system must allow **real-time updates** of room availability to prevent double bookings.
* The system should support **multiple room types** (single, double, suite, etc.) per hotel.

### 🔸 **Search and Filtering**

* Customers must be able to **search hotels** based on city, check-in/check-out dates, price range, ratings, and amenities.
* The system must **sort search results** by relevance, rating, or price.
* The system must **display hotel details** including images, address, and user reviews.

### 🔸 **Booking and Payment**

* Customers must be able to **select a hotel, choose room(s), and book** them for specific dates.
* The system must handle **secure payment processing** through integrated gateways (e.g., Stripe, PayPal).
* A **unique booking reference number** must be generated for every successful booking.
* Users must be able to **view, modify, or cancel** their bookings based on the hotel’s policy.
* The system must automatically **update room availability** after booking or cancellation.

### 🔸 **Notifications and Communication**

* The system must send **confirmation emails/SMS** to customers after booking and payment.
* The system must send **reminders or updates** (e.g., check-in dates, cancellations).
* The system should allow **in-app messaging** between customers and hotel owners.

### 🔸 **Review and Rating**

* Customers must be able to **rate and review** hotels after completing their stay.
* The system should **display average ratings and reviews** for each hotel.

### 🔸 **Administration and Reporting**

* Admins must be able to **generate reports** on bookings, payments, and user activity.
* Admins must be able to **monitor system performance** and manage content (e.g., flag inappropriate reviews).

  

## ⚙️ **Non-Functional Requirements**

Non-functional requirements describe **how the system performs its functions**, focusing on performance, reliability, usability, and scalability.

 🔹 **Performance**

* The system must respond to search queries within **2 seconds** under normal conditions.
* It must handle at least **10,000 concurrent users** without performance degradation.
* The booking transaction rate should support **up to 100 transactions per second** at peak time.

 🔹 **Availability and Reliability**

* The system should have an uptime of **99.9%** to ensure continuous service.
* The system must provide **fault tolerance** — if one service fails, others continue to function.
* All user and booking data must be **automatically backed up daily**.

 🔹 **Scalability**

* The system architecture must support **horizontal scaling** to handle increased traffic or hotels.
* The database must support **read replicas** and **load balancing** for efficient performance.

 🔹 **Security**

* All sensitive user data (passwords, payment info) must be **encrypted** during transmission and storage.
* The system must comply with **PCI DSS** standards for secure online payments.
* User accounts must be protected through **multi-factor authentication (MFA)** and secure login mechanisms.

 🔹 **Usability**

* The user interface must be **intuitive and easy to navigate** for all users (customers, hotel managers, and admins).
* The system must maintain a **consistent design** across web and mobile versions.
* Accessibility features (e.g., screen reader compatibility) must be supported for users with disabilities.

 🔹 **Maintainability**

* The system code should follow **modular architecture** to simplify updates and bug fixes.
* Documentation (SRS, API references, system diagrams) must be **kept up-to-date** for all team members.

 🔹 **Portability**

* The system should be **accessible on multiple platforms** — desktop, tablet, and mobile devices.
* The mobile app must support **offline viewing** of confirmed bookings and sync when online.

 🔹 **Data Integrity and Consistency**

* The system must ensure **real-time synchronization** of room availability across all booking channels.
* Data replication between master and replica databases must occur within **1 second delay**.


