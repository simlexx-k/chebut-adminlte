# Chebut Tea Farmers Management System

![Logo](chebut-removebg-preview.png)

Chebut Tea Farmers Management System is a web-based application developed using PHP and Bootstrap AdminLTE. This application is designed to efficiently capture and manage farmers' records for tea production, process payrolls, generate payslips, and handle deductions such as NSSF, NHIF, and tax. It aims to streamline the management process and provide accurate financial information for tea farmers.

## Features

- User-friendly interface: The application utilizes Bootstrap AdminLTE to provide a responsive and intuitive user interface, making it easy for users to navigate and interact with the system.

- Farmer records management: The system allows users to capture and maintain comprehensive records of tea farmers. The information includes farmer details such as name, contact information, and identification number.

- Daily tea production records: Users can record the quantity of tea submitted by each farmer on a daily basis. This information is essential for tracking tea production and calculating payments accurately.

- Payroll processing: The application automates the payroll generation process based on the tea production records. It calculates payments for individual farmers based on the quantity of tea submitted, prevailing rates, and any applicable deductions.

- Payslip generation: The system generates payslips for each farmer, providing a detailed breakdown of their earnings. The payslips include information about the tea quantity, rates, deductions, and net payment.

- Deduction management: The application handles deductions such as NSSF (National Social Security Fund), NHIF (National Health Insurance Fund), and tax. It calculates and deducts the appropriate amounts from the farmers' payments, ensuring compliance with legal requirements.

- Reports and analytics: The system provides various reports and analytics to help monitor tea production, payments, and deductions. Users can generate reports based on specific time periods, farmer groups, or other criteria to gain insights into the tea farming operations.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/simlexx-k/chebut.git
   ```

2. Configure the PHP environment and ensure it meets the system requirements.

3. Import the database schema from `database/chebut.sql` to your MySQL database.

4. Update the database configuration by modifying the `config.php` file located in the `includes` directory. Provide the appropriate credentials for your MySQL database.

5. Launch the application by accessing the URL in your web browser.

## Usage

1. Login to the system using your administrator credentials.

2. Add and manage farmer records by navigating to the "Farmers" section. Enter the required details such as name, contact information, and identification number.

3. Record the daily tea production for each farmer by selecting the "Daily Production" section. Enter the quantity of tea submitted by each farmer for the specific date.

4. Process payrolls by accessing the "Payroll" section. The system will automatically calculate the payments based on the tea production records and applicable rates.

5. Generate payslips for farmers by selecting the "Payslips" section. The payslips will provide a breakdown of the payments, deductions, and net amounts.

6. Manage deductions such as NSSF, NHIF, and tax through the respective sections in the application. Set the appropriate rates and ensure accurate deductions during the payroll processing.

7. Generate reports and analytics by accessing the "Reports" section. Customize the report parameters to get insights into tea production, payments, and deductions based on your requirements.

## Contributing

Contributions to Chebut Tea Farmers Management System are welcome! If you find any issues or have suggestions for improvement, please submit an issue or pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE
