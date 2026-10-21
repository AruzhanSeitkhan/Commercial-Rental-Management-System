This project is a web-based information system designed to automate the management of commercial properties, tenants, lease agreements, and rental payments.
The system aims to centralize rental information, reduce manual data processing, and help property owners and managers monitor commercial rental operations.
The project is being developed as a university diploma project.
The planned system includes:
- Commercial property and premises management
- Tenant information management
- Lease agreement creation and tracking
- Space availability checks and overlap prevention
- Rental charges and payment records
- Outstanding balance calculations
- Notifications for expiring leases and overdue payments
- Dashboard and rental revenue analytics
- Role-based access control
- ML-based monthly rental price estimation
Property Owner: Manages properties, premises, and user roles. Views occupancy, rental payments, outstanding balances, and reports.
Rental Manager: Manages tenants, premises, and lease agreements. Checks space availability and monitors lease expiration dates.
Accountant: Maintains rental charges and manually records verified payments. Monitors outstanding balances and financial reports.
The application will consist of a React frontend, a Java/Spring Boot backend, a PostgreSQL database, and a separate Python ML service.
The frontend communicates with the backend through REST APIs. The backend manages business logic, authentication, data validation, and database operations.
The ML service will provide estimated monthly rental prices based on property characteristics.
The system does not directly integrate with 1C.
The Accountant verifies actual payments using bank records or 1C and manually records confirmed payments in the rental management system.
Excel/CSV export is considered an optional feature for future data exchange.
Status: In Development
The project is currently in the planning, requirements analysis, and UI/UX design stages. Implementation and testing will follow the approved project requirements.
- Ayaulym Idrissova — Backend Development and Database Design
- Aruzhan Seitkhankyzy — Business Logic, Analytics, and Testing
- Aluana Muslimova — Frontend Development, UI/UX Design, and ML Module
The project documentation includes the Project Proposal, Evidence of Relevance, Literature Review, Requirements Specification, Architecture Diagrams, Verification and Evaluation Plan, and Project Management Plan.
The next stages include implementing the backend and frontend, preparing the ML dataset, training the rental price estimation model, integrating system components, and conducting testing.
