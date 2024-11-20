# Contract Monthly Claim System

## Overview
The **Contract Monthly Claim System** is a web application designed to facilitate the submission, tracking, and management of claims by lecturers. The system automates the claims process, allowing for efficient review, approval, and reporting.

## Features
- **User Authentication**: Secure login for lecturers, coordinators, and HR managers.
- **Claim Submission**: 
  - Lecturers can input hours worked, hourly rates, and submit claims easily.
  - Automated calculation of payment based on hours and rates.
  - Validation to ensure accurate data entry.
- **Approval Workflows**: Coordinators and managers can review claims based on predefined criteria and approve or reject them.
- **Claim Tracking**: Real-time updates on claim statuses (Pending, Approved, Rejected).
- **HR Management**: 
  - Automatic report generation for approved claims.
  - Tools to manage lecturer data (e.g., update contact info).
- **Document Upload**: Attach supporting files for claims.
- **Management Dashboard**: Streamlined tools for managing claims and lecturer data.

## Technology Stack
- **Frontend**: ASP.NET Core MVC with jQuery.
- **Backend**: C# with Entity Framework.
- **Database**: SQL Server.
- **Development Environment**: Visual Studio.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AsemahleNonkwelo/Contract-Claim-Monthly-System
Open the solution file (ContractClaimSystem.sln) in Visual Studio.
Restore NuGet packages as prompted.
Update the database connection string in appsettings.json (or web.config).
Build the solution and run the application.
Usage

Lecturers:
Log in using your credentials.
Submit claims on the "Add Claims" page with hours worked and rates.
Attach supporting documents and track claim statuses.
Coordinators and Managers:
Access the dashboard to review claims.
Approve or reject claims based on automated validation criteria.
HR:
Generate reports for approved claims.
Manage lecturer information.
Dependencies

Visual Studio (latest version recommended)
SQL Server for database management
ASP.NET Core MVC for web application development
jQuery for client-side validation and interaction
Entity Framework for database interactions
Contributing

Contributions are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

Thanks to the community for the open-source tools and resources that made this project possible.
