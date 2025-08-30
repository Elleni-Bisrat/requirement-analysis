# Requirement Analysis in Software Development

## Introduction
This repository is dedicated to exploring the process of **Requirement Analysis** in Software Development.  
Requirement analysis is a critical phase of the Software Development Life Cycle (SDLC) that focuses on gathering, understanding, and documenting the needs of stakeholders to ensure the successful delivery of software projects.

The purpose of this repository is to:
- Document the key concepts of requirement analysis
- Provide examples and case studies
- Serve as a resource for students and developers learning about software engineering practices

---

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, and defining the needs and expectations of stakeholders for a software system. It serves as the foundation of the Software Development Life Cycle (SDLC), ensuring that the final product meets business goals and user needs.  

In this phase, analysts work closely with clients, users, and other stakeholders to:
- Understand the problem to be solved
- Define what the software should do (functional requirements)
- Clarify how the system should perform (non-functional requirements)
- Resolve conflicts, ambiguities, and inconsistencies in requirements

### Importance in SDLC
- **Clarity of Goals:** Prevents misunderstandings by clearly defining project objectives.  
- **Reduced Risks:** Early detection of gaps or conflicts in requirements avoids costly rework later.  
- **Improved Communication:** Acts as a bridge between stakeholders and developers.  
- **Foundation for Design & Development:** Provides a blueprint for system architecture, coding, and testing.  
- **Customer Satisfaction:** Ensures that the software aligns with user needs and expectations.  

In short, requirement analysis is essential for delivering high-quality software on time and within budget.

## Why is Requirement Analysis Important?
Requirement Analysis plays a **vital role** in the success of software projects. Without it, development efforts may lead to wasted time, increased costs, and products that fail to meet user needs.  

Here are three key reasons why it is critical:

1. **Prevents Miscommunication and Misunderstanding**  
   - Clear and well-documented requirements ensure that both stakeholders and developers are aligned on project goals.  
   - Eliminates ambiguity and sets realistic expectations for everyone involved.  

2. **Saves Time and Reduces Costs**  
   - Identifying and fixing issues during the requirement phase is much cheaper and faster than addressing them after development.  
   - Avoids unnecessary rework, scope creep, and project delays.  

3. **Ensures Quality and User Satisfaction**  
   - Properly analyzed requirements lead to building a product that truly meets user needs.  
   - Increases stakeholder confidence and results in higher acceptance of the final software.  

In summary, **requirement analysis is the backbone of SDLC**—it ensures smooth development, minimizes risks, and maximizes project success.


## Key Activities in Requirement Analysis
Requirement Analysis is not a single task—it involves a series of structured activities to ensure that requirements are accurate, clear, and usable. The five key activities include:  

- **Requirement Gathering**  
  - Collecting information from stakeholders, clients, and end-users.  
  - Techniques: interviews, questionnaires, workshops, and brainstorming sessions.  

- **Requirement Elicitation**  
  - Actively engaging with stakeholders to uncover their needs, goals, and constraints.  
  - Helps identify both explicit (stated) and implicit (unstated) requirements.  

- **Requirement Documentation**  
  - Recording requirements in a structured format such as Software Requirement Specification (SRS).  
  - Ensures all stakeholders have a common reference for system expectations.  

- **Requirement Analysis and Modeling**  
  - Examining the gathered requirements to identify gaps, conflicts, and feasibility.  
  - Using models such as data flow diagrams, UML diagrams, or use cases to represent requirements visually.  

- **Requirement Validation**  
  - Reviewing and verifying requirements with stakeholders to confirm accuracy and completeness.  
  - Ensures the documented requirements align with business objectives and user needs.  
## Types of Requirements

In software engineering, requirements are broadly categorized into **Functional Requirements** and **Non-functional Requirements**. Both are critical to delivering a complete and usable system.  

### 1. Functional Requirements
Functional requirements describe **what the system should do**—the specific features and behaviors of the application.  

**Examples for a Booking Management System:**  
- The system shall allow users to **create new bookings** for rooms.  
- The system shall enable users to **view available rooms** based on date and time.  
- The system shall allow users to **cancel or modify an existing booking**.  
- The system shall send **email or SMS notifications** to users upon successful booking.  
- The system shall provide an **admin dashboard** to manage all bookings.  

---

### 2. Non-functional Requirements
Non-functional requirements define **how the system should perform** rather than what it does. These cover performance, usability, reliability, and security aspects.  

**Examples for a Booking Management System:**  
- The system should support **at least 500 concurrent users** without performance degradation.  
- The booking confirmation should be processed within **2 seconds**.  
- The system should be available **24/7 with 99.9% uptime**.  
- User data must be stored securely with **data encryption and role-based access control**.  
- The interface should be **responsive and accessible**, supporting both desktop and mobile devices.

  ## Use Case Diagrams

### What is a Use Case Diagram?
A **Use Case Diagram** is a visual representation of how users (actors) interact with a system.  
It focuses on capturing the **functional requirements** of the system by showing different use cases (actions or services) and how they relate to external users.  

### Benefits of Use Case Diagrams
- **Clarity of system scope:** Defines the boundaries of what the system will and will not do.  
- **Improved communication:** Provides a simple and visual way to explain requirements to stakeholders.  
- **Identification of actors and interactions:** Helps developers and stakeholders understand who uses the system and how.  
- **Foundation for design:** Serves as the starting point for creating more detailed models like sequence diagrams and activity diagrams.  

---

### Example:## Movie Ticket Booking System

In this system, there are four main actors:

- **System Admin**: Can manage users, customers, bookings, payments, seats, and shows.  
- **System User**: Can log in/out, update profile, change password, view movies, book tickets, make payments, and download tickets.  
- **Hall Owner**: Can create shows, collect payments, and manage related booking activities.  
- **Customer**: Can view movie details, book tickets, make payments, and download tickets.  

---

### Use Cases include:

- **Manage Users and Full Application** (Admin)  
- **Manage Customer** (Admin)  
- **Manage Booking** (Admin, System User)  
- **Manage Payment** (Admin, System User)  
- **Manage Seats** (Admin)  
- **Manage Shows** (Admin, Hall Owner)  
- **Login and Logout from System** (System User, Admin)  
- **Update My Profile** (System User, Admin, Customer)  
- **Change Account Password** (System User, Admin, Customer)  
- **Book Tickets** (System User, Customer)  
- **View Movie Details** (System User, Customer)  
- **Create Shows** (Hall Owner)  
- **Collect Payments** (Hall Owner)  
- **Make Payment** (System User, Customer)  
- **Download Ticket** (System User, Customer)  


### Use Case Diagram
The obtained general use case diagram is:

<img width="815" height="680" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/86715588-5f40-4c6a-a89d-550eca80b9ed" />

## Acceptance Criteria

### Importance of Acceptance Criteria in Requirement Analysis
Acceptance Criteria are the conditions that a software product must satisfy to be accepted by a user, customer, or stakeholder. They define the boundaries of a user story or requirement and ensure clarity for both the development team and stakeholders.  

Well-written acceptance criteria:
- Provide a clear understanding of the scope of a requirement.  
- Reduce ambiguity and misunderstandings between stakeholders and developers.  
- Act as a basis for test cases to validate functionality.  
- Help determine when a feature is “done.”  

By defining acceptance criteria early in the requirement analysis phase, teams can ensure alignment with user needs and business goals, improving the quality and usability of the system.  

---

### Example: Checkout Feature (Booking Management System)
**Feature:** Checkout Process  

**Acceptance Criteria:**
1. The system must allow the user to review their booking details before confirming.  
2. The user must be able to select a payment method (e.g., credit card, PayPal, or mobile payment).  
3. The system must validate payment details before processing.  
4. A confirmation page must be displayed after a successful checkout with booking details and transaction ID.  
5. The system must send a booking confirmation notification (via email/SMS) to the user after checkout.  
6. If the payment fails, the system must display an error message and allow the user to retry.  

These criteria ensure that the checkout process is user-friendly, reliable, and aligned with both customer and business requirements.




