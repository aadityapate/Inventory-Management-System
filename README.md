# Inventory Management System

## Project Overview
The **Inventory Management System** is a real-time, multi-store inventory tracking solution. It records sales, manages stock deliveries between branches, and sends low-stock warnings via email, ensuring smooth operations across all store locations. The system is implemented using Python and MySQL, offering an efficient way to manage inventory across multiple stores or within a single location.

## Key Features
- **Real-Time Tracking**: Tracks products and parts from seller to storeroom, between storerooms, and finally to retail locations or customers.
- **Multi-Branch Support**: Connects multiple stores and manages inventory between them.
- **Email Alerts**: Automatically sends warnings when stock is low at any location.
- **Sales and Restocking Records**: Logs sales and restocking events for accurate inventory management.

## Objectives
- Ensure optimal inventory levels, avoiding both overstock and out-of-stock situations.
- Enhance coordination between multiple store locations.
- Efficient resource management by minimizing inventory costs while maintaining operational needs.
- Automate notifications for low-stock items to prompt timely restocking.
- Maintain detailed records of sales and inventory movements for analysis and reporting.
- Protection against risks such as obsolescence and theft.
- Timely customer service with sufficient stock to meet demand.


## Technologies Used
- **Programming Language**: Python
- **Database**: MySQL
- **Libraries**: Tkinter, Pandas, NumPy

## How It Works
1. **Real-Time Inventory Management**: Track inventory as it moves between stores and is sold or restocked.
2. **Automated Alerts**: Receive low-stock warnings via email for prompt restocking.
3. **Database Integration**: Store and manage all inventory data using MySQL for accurate reporting and management.
4. **User Interface**: Built using Python’s Tkinter for a simple, user-friendly interface.

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aadityapate/Inventory-Management-System.git
   
2. **Navigate to the project directory**:
    ```bash
    cd Inventory-Management-System

3. **Set Up the Virtual Environment**: Ensure you have Python installed. Then, create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

4. **Install Dependencies**: Install the required Python packages:
   ```bash
   pip install -r requirements.txt

5. **Configure the MySQL Database**:
   - Install MySQL: Ensure MySQL is installed on your system. You can download it from the official website.
   - Create a Database: Log in to your MySQL server and create a new database:
     ```bash
     CREATE DATABASE inventory_management;
   - Update Configuration: Modify the database configuration in the project to match your MySQL credentials. This typically involves editing a configuration file (e.g., 
     config.py) with your database name, user, password, and host details.

6. Initialize the Database Schema: Apply the database migrations to set up the necessary tables:
   ```bash
   python manage.py migrate
  Access the application by navigating to http://127.0.0.1:8000/ in your web browser.

7. Run the Application: Start the development server:
   ```bash
   python manage.py runserver

8. Set Up Email Notifications (Optional): To enable low-stock email alerts, configure the email settings in your project. This may involve setting SMTP server details and 
   authentication credentials in your configuration file.

**Note**: Ensure you have the necessary permissions and that your firewall settings allow communication on the required ports for both MySQL and the web application.

## Team
- **1. Aaryan Puri** 
- **2. Aditya Pate** 
- **3. Dhruv Gupta**

