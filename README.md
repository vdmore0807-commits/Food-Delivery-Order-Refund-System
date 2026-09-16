\# Food Delivery Order \& Refund Management System



\*\*Business Analysis Case Study | QuickBite\*\*



This is a Business Analysis portfolio project based on a fictional food delivery company, \*\*QuickBite\*\*.



The project focuses on documenting the process for \*\*order cancellation and refunds\*\*. It covers what happens when a customer cancels an order, a restaurant rejects an order, or a payment-related issue requires a refund.



The project was created to practice Business Analysis documentation and process modeling.



\---



\## Project Overview



The system covers the following areas:



\* Viewing order status

\* Cancelling eligible orders

\* Checking refund eligibility

\* Initiating refunds

\* Viewing refund status

\* Sending refund notifications

\* Providing Customer Support with order, payment, and refund details

\* Preventing duplicate refunds

\* Maintaining refund records



\---



\## Business Requirements



The project includes \*\*8 business requirements (BR-01 to BR-08)\*\* covering:



\* Order cancellation

\* Refund eligibility

\* Refund initiation

\* Refund status

\* Refund notifications

\* Customer Support access

\* Duplicate refund prevention

\* Refund record maintenance



Business rules are also defined for situations such as restaurant-rejected orders, failed payments, and refund processing.



\---



\## Functional Requirements



The project contains \*\*9 functional requirements (FR-01 to FR-09)\*\*.



These describe how the system should handle:



1\. Order status

2\. Order cancellation

3\. Refund eligibility

4\. Refund initiation

5\. Refund status

6\. Refund notifications

7\. Customer Support access

8\. Duplicate refund prevention

9\. Refund records



The FRD also includes non-functional requirements, external system requirements, and exception handling.



\---



\## Use Cases



The project contains \*\*9 use cases (UC-01 to UC-09)\*\*:



| ID    | Use Case                       |

| ----- | ------------------------------ |

| UC-01 | View Order Status              |

| UC-02 | Cancel Order                   |

| UC-03 | Check Refund Eligibility       |

| UC-04 | Initiate Refund                |

| UC-05 | View Refund Status             |

| UC-06 | Update Refund Status           |

| UC-07 | View Order \& Payment Details   |

| UC-08 | Update Restaurant Order Status |

| UC-09 | Send Refund Notification       |



The use case document includes actors, preconditions, triggers, main flows, and alternative flows.



\---



\## User Stories \& Acceptance Criteria



The project includes \*\*9 user stories (US-01 to US-09)\*\*.



The user stories cover the main requirements of the system, including order cancellation, refund processing, refund status, restaurant order updates, and notifications.



Each user story has acceptance criteria describing the expected behaviour of the system.



\---



\## Process Modeling



A \*\*BPMN process model\*\* was created to represent the order and refund workflow.



The process includes three main lanes:



\* \*\*Customer\*\*

\* \*\*QuickBite System\*\*

\* \*\*Restaurant Staff\*\*



The repository contains both the editable Draw.io file and a PNG version of the BPMN diagram.



\---



\## Requirements Traceability Matrix



An \*\*RTM (Requirements Traceability Matrix)\*\* was created to connect requirements across the project.



The main traceability flow is:



\*\*Business Requirements → Functional Requirements → Use Cases → User Stories → Acceptance Criteria\*\*



This helps keep the requirements connected across the different documents.



\---



\## External Systems



The project considers the following external systems:



\* \*\*Payment Gateway\*\* — refund requests and refund status

\* \*\*Order Management System\*\* — order status and cancellation information

\* \*\*Restaurant System\*\* — restaurant order acceptance/rejection

\* \*\*Notification Service\*\* — refund-related notifications



\---



\## Exception Handling



The project also documents common exception scenarios, such as:



\* Cancellation is no longer allowed

\* Refund request fails

\* Payment status cannot be confirmed

\* Refund already exists

\* Refund status cannot be retrieved



\---



\## Business Analysis Skills Demonstrated



\* Business Requirements Documentation

\* Functional Requirements Documentation

\* Business Rules

\* Non-Functional Requirements

\* Use Case Analysis

\* User Stories

\* Acceptance Criteria

\* BPMN Process Modeling

\* Requirements Traceability

\* Exception Handling

\* External System Analysis



\---



\## Project Structure



```text

Food-Delivery-Order-Refund-System/

│

├── BRD/

│   └── QuickBite\_BRD.docx

│

├── FRD/

│   └── QuickBite\_FRD.docx

│

├── Process Models/

│   ├── QuickBite Process Models.docx

│   ├── QuickBite\_BPMN.drawio

│   └── QuickBite\_BPMN.png

│

├── Project Overview/

│   └── Project Overview.docx

│

├── RTM/

│   └── QuickBite\_RTM.docx

│

├── Use Case/

│   ├── QuickBite Use Case Specifications.docx

│   └── QuickBite\_Use\_Case\_Diagram.drawio.png

│

└── User Stories/

&#x20;   └── QuickBite User Stories.docx

```



\---



\## Tools Used



\* Microsoft Word

\* Draw.io

\* GitHub



\---



\## Project Note



\*\*QuickBite is a fictional company created for this Business Analysis case study.\*\*



This project is intended for portfolio and learning purposes and is not based on an actual client or production system.



\*\*Created by:\*\* Vaishnavi More



