# Hotel Management System

## Setup Instructions

Follow these steps to set up the project locally using XAMPP:

### Prerequisites
- Ensure that [XAMPP](https://www.apachefriends.org/index.html) is installed on your system.
- Start the Apache and MySQL services in XAMPP before proceeding.

### Installation Steps

1. **Extract the Project Files**
   - Extract the downloaded project file to a directory of your choice.

2. **Copy the Project Folder**
   - Copy the main project folder, named `Hotel`.

3. **Paste the Folder into XAMPP Directory**
   - Paste the `Hotel` folder into the `xampp/htdocs/` directory.

4. **Create the Database**
   - Open a browser and navigate to `http://localhost/phpmyadmin/`.
   - Click on the **Databases** tab.
   - Create a new database with the name `hotel`.
   - Click on the **Import** tab.
   - Browse and select the `hotel.sql` file, located inside the `Hotel` folder.
   - Click **Go** to import the database. 

   **Note:** If the database is already created, you can skip steps 4 to 8.

5. **Access the Project**
   - Open a browser and go to `http://localhost/Hotel/` to access the main application.

6. **Admin Panel**
   - To access the admin panel, navigate to `http://localhost/Hotel/admin/index.php`.

---

### Additional Notes
- Ensure that the `hotel.sql` file is successfully imported to avoid database-related errors.
- If you face any issues, ensure that the Apache and MySQL services are running in XAMPP.
