# Requirement Analysis in Software Development.
## What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and defining the needs and expectations of stakeholders for a software project. It is one of the most critical stages in the Software Development Lifecycle (SDLC), as it lays the foundation for all future design, development, and testing activities.

During this phase, project teams work closely with stakeholders—such as clients, end-users, and business managers—to clearly understand what the system should achieve. The outcomes are usually documented in the form of **Software Requirement Specifications (SRS)** or **user stories**, which serve as a reference for developers and testers throughout the project.

### Importance of Requirement Analysis in SDLC
- **Clarity of Goals:** Ensures all stakeholders have a shared understanding of the project’s objectives and deliverables.  
- **Reduced Errors:** Minimizes misunderstandings and misinterpretations that often lead to costly rework.  
- **Scope Management:** Defines the boundaries of the project, helping to prevent scope creep.  
- **Improved Design & Development:** Provides developers with clear guidance, leading to more accurate system design and implementation.  
- **Quality Assurance:** Serves as a benchmark against which testing and validation can be performed.  
- **Time & Cost Efficiency:** Detecting and addressing requirements issues early reduces delays and unnecessary expenses.  

In short, Requirement Analysis is the **blueprint stage** of software development. Without it, projects risk drifting off-course, exceeding budgets, or failing to meet user needs.


## Why is Requirement Analysis Important?

Requirement Analysis is a critical stage in the Software Development Lifecycle (SDLC) because it sets the direction for the entire project. Proper analysis ensures that the software meets user needs, avoids unnecessary costs, and is delivered on time. Below are three key reasons why Requirement Analysis is important:

### 1. Provides Clarity and Alignment  
Requirement Analysis ensures that all stakeholders—clients, developers, testers, and project managers—have a shared understanding of the project’s objectives. This clarity reduces miscommunication and aligns the team toward a common goal.

### 2. Reduces Cost and Time Overruns  
Identifying and addressing requirements early prevents costly changes later in the development process. Since fixing errors at later stages (testing or deployment) is significantly more expensive, requirement analysis helps save both time and money.

### 3. Ensures Quality and Customer Satisfaction  
Clear and validated requirements act as a foundation for design, development, and testing. This improves the overall quality of the software and ensures that the final product meets customer expectations and business goals.



## Key Activities in Requirement Analysis

Requirement Analysis involves a series of structured activities that ensure the needs of stakeholders are correctly understood, documented, and validated. The five key activities are:

- **Requirement Gathering**  
  Collecting information from stakeholders, customers, and end-users about what they expect from the system. This often includes interviews, surveys, and studying existing systems.

- **Requirement Elicitation**  
  Actively engaging with stakeholders to uncover both stated and hidden needs. Techniques such as brainstorming sessions, workshops, observation, and prototyping are commonly used.

- **Requirement Documentation**  
  Recording the gathered and elicited requirements in a clear and structured format. Common outputs include a Software Requirement Specification (SRS) document or user stories.

- **Requirement Analysis and Modeling**  
  Examining requirements for completeness, feasibility, consistency, and relevance. Modeling tools (e.g., use case diagrams, data flow diagrams) may be used to represent requirements visually.

- **Requirement Validation**  
  Verifying that the documented requirements truly reflect stakeholder needs. This is done through reviews, walkthroughs, and feedback sessions to ensure accuracy before design and development begin.


## Types of Requirements

In software projects, requirements are typically divided into two main categories: **Functional Requirements** and **Non-functional Requirements**. Both are essential for building a system that not only works as expected but also performs effectively and reliably. Below is a breakdown with examples for the **Booking Management Project** (from the case study).

### Functional Requirements
Functional requirements define **what the system should do**. They describe specific behaviors, features, and interactions of the system from the user’s perspective.

**Examples for the Booking Management Project:**
- Users should be able to create a new booking for rooms or services.
- The system must allow users to view, update, or cancel existing bookings.
- Customers should receive an email or SMS confirmation after a successful booking.
- The system should generate booking history reports for administrators.
- Users must be able to search available rooms based on date and type.

### Non-functional Requirements
Non-functional requirements define **how the system should perform**. They focus on quality attributes such as performance, security, usability, and reliability rather than specific features.

**Examples for the Booking Management Project:**
- The system should be available **24/7** with 99.9% uptime.
- Response time for any booking request must be less than **2 seconds**.
- The system must support up to **500 concurrent users** without performance degradation.
- All sensitive data (e.g., customer details, payment information) must be encrypted.
- The interface should be mobile-responsive and accessible to people with disabilities (WCAG compliance).


## Use Case Diagrams

A **Use Case Diagram** is a visual representation of the interactions between users (actors) and a system. It is part of the Unified Modeling Language (UML) and is widely used in Requirement Analysis to capture functional requirements. Use Case Diagrams help project teams understand **who** will use the system and **what** actions they can perform.

### Benefits of Use Case Diagrams
- **Clarity:** Provides a clear, high-level view of the system’s functionality.  
- **Stakeholder Communication:** Makes it easier for non-technical stakeholders to understand system behavior.  
- **Requirement Validation:** Ensures all functional requirements are covered and aligned with user needs.  
- **Design Foundation:** Serves as a blueprint for system design and testing scenarios.  

### Use Case Diagram for the Booking Management System
Actors and Use Cases identified for the booking system include:  
- **Actors:**  
  - Customer  
  - Admin  
  - Payment System  

- **Use Cases:**  
  - Create Booking  
  - View/Update/Cancel Booking  
  - Receive Confirmation (email/SMS)  
  - Process Payment  
  - Generate Reports  

Below is the Use Case Diagram for the Booking System:  
![alt text](alx-booking-uc.png)![alt text](alx-booking-uc.png)
![Booking System Use Case Diagram](alx-booking-uc.png)


## Acceptance Criteria

**Acceptance Criteria** are predefined conditions that a software feature must meet to be considered complete and acceptable by stakeholders. They play a vital role in **Requirement Analysis** by clearly defining the scope of a requirement and setting measurable standards for success. Acceptance Criteria help bridge the gap between stakeholders and developers, ensuring that both parties have a shared understanding of what "done" means for a feature.

### Importance of Acceptance Criteria
- **Clarity:** Provides unambiguous guidelines on what is expected from a feature.  
- **Alignment:** Ensures all stakeholders (developers, testers, and business owners) agree on feature outcomes.  
- **Testing Basis:** Serves as the foundation for writing test cases and verifying functionality.  
- **Scope Control:** Prevents scope creep by setting clear boundaries for what is included and excluded in a feature.  

### Example: Acceptance Criteria for the Checkout Feature
For the **Checkout feature** in the Booking Management System, the acceptance criteria may include:

- The system should allow a customer to review their booking details before proceeding to payment.  
- The system must support secure payment methods (credit/debit card, mobile money).  
- The checkout process should not take more than **3 steps** (Review → Payment → Confirmation).  
- Upon successful payment, the customer must receive a confirmation email and SMS with booking details.  
- If payment fails, the system should display an error message and allow the user to retry.  
- The checkout process must complete within **5 seconds** under normal load conditions.  
