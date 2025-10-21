# requirement-analysis
# Requirement Analysis in Software Development
This repository is created to explore and document the process of Requirement Analysis in the Software Development Life Cycle (SDLC).  
It covers the key activities involved — such as requirement gathering, elicitation, documentation, modeling, and validation — providing a foundational understanding of how clear, accurate, and prioritized requirements contribute to the success of software projects.
## What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the Software Development Life Cycle (SDLC) that focuses on understanding and defining what the users need from a software system.  
It involves gathering requirements from stakeholders, analyzing them to ensure clarity and feasibility, documenting them in a structured format, and validating them to confirm alignment with business goals.

### **Key Objectives of Requirement Analysis**
- To identify the **needs, expectations, and constraints** of the users and stakeholders.  
- To ensure that the **software requirements** are complete, consistent, and unambiguous.  
- To create a **clear foundation** for system design, development, and testing.  
- To minimize misunderstandings and reduce the risk of costly rework later in the development process.

### **Importance in the SDLC**
Requirement Analysis serves as the **blueprint** for the entire software project. Without well-defined requirements, the development process can face challenges such as scope creep, delays, or misaligned outcomes.  
By conducting thorough analysis:
- Developers know **what to build**.  
- Testers know **what to verify**.  
- Stakeholders understand **what to expect**.  

## Key Activities in Requirement Analysis

The Requirement Analysis process is composed of several interrelated activities that ensure the software requirements are accurate, complete, and aligned with business objectives.

### **1. Requirement Gathering**
- Involves collecting information from various stakeholders such as clients, users, and business managers.  
- Techniques include **interviews, surveys, questionnaires, and workshops**.  
- The goal is to understand the **business needs** and **user expectations** that the software must fulfill.

### **2. Requirement Elicitation**
- Focuses on exploring and refining gathered requirements to uncover deeper insights.  
- Uses techniques like **brainstorming, prototyping, observation, and use case analysis**.  
- Helps in identifying hidden or unclear requirements that stakeholders may not have initially articulated.

### **3. Requirement Documentation**
- All collected and refined requirements are formally documented in artifacts such as the **Software Requirement Specification (SRS)**, **use cases**, and **user stories**.  
- Ensures that the requirements are communicated clearly and consistently across the development team.  
- Provides a reference point throughout the project lifecycle.

### **4. Requirement Analysis and Modeling**
- Involves examining requirements to ensure they are **complete, feasible, and consistent**.  
- Modeling techniques such as **data flow diagrams (DFD), entity-relationship diagrams (ERD), and use case diagrams** are used to visualize system behavior.  
- Helps bridge the gap between user requirements and system design.

### **5. Requirement Validation**
- The final step that ensures all documented requirements align with stakeholder expectations and project objectives.  
- Includes **reviews, walkthroughs, and prototyping sessions** with stakeholders.  
- Ensures that the defined requirements are correct, testable, and achievable within the project constraints.

---

These five activities collectively ensure that the software project starts on a solid foundation — reducing risks, improving communication, and aligning the development team with stakeholder goals.

## Types of Requirements

In software development, requirements are generally categorized into two main types: **Functional Requirements** and **Non-functional Requirements**.  
Both are essential for defining what a system should do and how it should perform.

### **1. Functional Requirements**

**Definition:**  
Functional requirements specify **what the system should do**. They describe the core functions, features, and interactions that the software must support to fulfill user needs.

**Examples (Booking Management Project):**
- Users should be able to **create an account** and log in securely.  
- The system should allow users to **search for available properties** based on filters such as location, price, and availability.  
- Users should be able to **book a property** by selecting check-in and check-out dates.  
- Property owners should be able to **add, edit, and remove listings**.  
- The system should **generate booking confirmations and send email notifications**.  
- Admins should be able to **view reports and manage user accounts**.

### **2. Non-functional Requirements**

**Definition:**  
Non-functional requirements define **how the system should perform** rather than what it does. They focus on the quality attributes such as performance, reliability, security, usability, and scalability.

**Examples (Booking Management Project):**
- The system should **load pages within 2 seconds** under normal network conditions.  
- It should support **at least 500 concurrent users** without performance degradation.  
- All sensitive data must be **encrypted** during storage and transmission.  
- The system should maintain **99.9% uptime** to ensure continuous availability.  
- The interface should be **mobile-responsive** and **user-friendly** across devices.  
- The system should support **multi-language functionality** for international users.  
- Backups should be performed **daily** to prevent data loss.
- 
## Use Case Diagrams

**Definition:**  
A **Use Case Diagram** is a visual representation that shows the interactions between **users (actors)** and the **system**. It helps illustrate what the system should do by outlining the key use cases and how users engage with them.

**Benefits of Use Case Diagrams:**
- Provides a **clear overview** of system functionality.  
- Helps in **identifying user roles** and their interactions with the system.  
- Serves as a **communication tool** between stakeholders, analysts, and developers.  
- Supports the creation of detailed **use case specifications** for development and testing.

---

### **Use Case Diagram for the Booking Management System**

**Actors:**
- **Guest/User** – Searches, books, and manages reservations.  
- **Property Owner** – Manages property listings and monitors bookings.  
- **Admin** – Oversees users, properties, and system operations.

**Use Cases:**
- Create Account / Login  
- Search for Property  
- View Property Details  
- Book Property  
- Manage Bookings  
- Add / Edit / Remove Property  
- View Reports  
- Manage Users

Below is the visual representation of the use case diagram:

<img width="4480" height="2721" alt="alx-booking-uc png" src="https://github.com/user-attachments/assets/45e43018-3d31-49ed-9f66-3e7c30616183" />

