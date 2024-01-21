
# Expense Payment System

## Description

The Expense Payment System is designed to manage and track expense items for field personnel within a company. This application allows field employees to input their expenses into the system instantly. Employers can efficiently monitor and approve these expenses in real-time, enabling prompt payment to the employees. This system aims to streamline the process, eliminating the need for manual paperwork and ensuring timely reimbursement for field personnel.

The application caters to two main roles within the company: administrators and field personnel. Field personnel are responsible for entering expense details and requesting reimbursements. They can view their existing requests and track the status of each request. Pending requests for approval are visible, allowing them to monitor and follow up. Company users with administrative privileges can view and manage existing expense requests, approving or rejecting them as needed.

For approved expenses, the payment process is facilitated instantly through bank integration. The system transfers the approved amount to the employee's account via Electronic Funds Transfer (EFT). In the case of rejected requests, administrators are required to provide an explanation in a designated field. This allows the requesting employee to understand why their expense request was rejected.

This system not only simplifies the expense management process but also ensures that field personnel receive their reimbursements promptly, reducing the need for paperwork and delays in payment.

## Technologies Used

- .NET
- Entity Framework
- PostgreSQL
- MVC (Model-View-Controller)
- Bank Integration (EFT)

## Setup

1. **Database Configuration**

   - Ensure that PostgreSQL is installed on your local machine.
   - Modify the connection string in the `appsettings.json` file to match your PostgreSQL configuration.

2. **Running the Application**

   - Clone the repository to your local machine.
   - Open the project in your preferred IDE.
   - Build and run the application.

## Usage

Explain how to use your application or any additional setup required for users.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

Mention any third-party libraries, tutorials, or resources that you found helpful in your project.

## Application Features

- **Expense Entry:**
  - Field personnel can enter their expenses into the system.
  - Expenses can be categorized and specified for detailed tracking.

- **Reimbursement Requests:**
  - Field personnel can submit reimbursement requests for their expenses.
  - Requests are processed in real-time for quick approval.

- **Request Tracking:**
  - Users can track the status of their expense requests.
  - Pending requests for approval are visible for monitoring.

- **Administrative Approval:**
  - Administrators can view and manage expense requests.
  - Requests can be approved or rejected with optional explanations.

- **Bank Integration:**
  - Approved expenses trigger instant payment through bank integration.
  - Electronic Funds Transfer (EFT) ensures timely reimbursement for field personnel.

## Database Schema

### Personal Table

- **PersonalId:** (Primary Key) Unique identifier for each personal entry.
- **UserName:** User's username.
- **Password:** User's password.

### PersonalAccount Table

- **AccountId:** (Primary Key) Unique identifier for each personal account.
- **Balance:** Current balance in the personal account.
- **PersonalId:** (Foreign Key) Relates to the `Personal` table.

### PersonalCostLog Table

- **PersonalCostLogId:** (Primary Key) Unique identifier for each personal cost log entry.
- **CoutBalance:** Current balance in the cost log.
- **PersonalId:** (Foreign Key) Relates to the `Personal` table.

## Usage

To use the application, follow these steps:

1. Open the application in your preferred IDE.
2. Ensure that PostgreSQL is installed on your local machine.
3. Modify the connection string in the `appsettings.json` file to match your PostgreSQL configuration.
4. Clone the repository to your local machine.
5. Build and run the application.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.


## Screenshots








<img width="418" alt="image1" src="https://github.com/emretterzi/FinalCase/assets/56559417/7b743ad4-9731-4e81-bb38-b7e3d3745273">

<img width="505" alt="image4" src="https://github.com/emretterzi/FinalCase/assets/56559417/2f042e13-5bb4-4908-a7e5-48c2797215a5">

![image2](https://github.com/emretterzi/FinalCase/assets/56559417/cf2a16ba-6e1f-4960-9ee2-5586a30d2756)





![image3](https://github.com/emretterzi/FinalCase/assets/56559417/30f2c875-6c2e-4981-8643-3a5a7e2c759b)



![image5](https://github.com/emretterzi/FinalCase/assets/56559417/5d7a36a7-fdf6-4fc6-a863-16b34dd22663)
