# AntiScam Website Prototype

Welcome to the AntiScam Website Prototype, a project developed as part of the Requirements Engineering course. This prototype serves as a step in the professional and business process of project development, focusing on scam prevention in an online environment.

## Technical Details

- **Language:** PHP
- **Framework:** Laravel
- **Project Type:** AntiScam Website Prototype
- **Objective:** Developed as part of the Requirements Engineering course, this educational website prototype aims to apply the professional practices learned in the discipline. The project focuses on scam prevention, incorporating features such as educational content, scam recognition tools, a reporting mechanism, user feedback, and a dedicated dashboard for technicians.

## Features

- **Educational Content:** Informative resources to help users understand various online scams.

- **Scam Recognition Tools:** Interactive tools and guides to recognize potential scams.
  
- **Reporting Mechanism:** A feature allowing users to report suspicious activities.
  
- **User Feedback:** Collection of user feedback to enhance scam prevention strategies.

- **Technician Dashboard:** Dedicated dashboard for technicians to work on and perform maintenance for the website.

# Setup Instructions

Follow these steps to set up the AntiScam Website Prototype on your local machine:

**IMPORTANT NOTE: EVERY TIME SOMETHING IS INSTALLED FOR VS CODE, IT NEEDS TO BE CLOSED AND REOPENED**

1. **Use [Visual Studio Code IDE](https://code.visualstudio.com/)**

2. **Install [XAMPP](https://www.apachefriends.org/download.html) to obtain PHP:**
   - If necessary, set up environment variables by following this short tutorial for setting the path: [Setting Environment Variables](https://maheshwaghmare.com/windows/blog/environment-variables-path/#set-environment-variable).

3. **Install [Composer](https://getcomposer.org/):**
   - In the installer, accept adding the PHP path and ignore the rest. Sometimes the installer doesn't ask for the PHP path, it's normal.
   - After reopening VS Code, run `composer global require "laravel/installer"`.

4. **Install [Node.js](https://nodejs.org/) with the LTS version**

5. **Install [Git Bash](https://git-scm.com/downloads):**
   - You can proceed with all options during installation.

6. **Open a new terminal in VS Code using Git Bash**

7. **Install the following extensions in VS Code:**
   - Node Extension Pack
   - PHP Extension Pack

8. **In the Git Bash terminal, navigate to the Backend folder:**
   
   ```bash
   cd backend
   ```

    - Run the command:
    ```bash
    composer install
    ```
    - Wait until completion, then run:
    ```bash
    npm install
    ```

    - As a precaution, also run:
    ```bash
    npm run build
    ```

9. **Create a file in the Backend folder named: `.env`**

10. **Copy the contents from the `.env.example` file to the `.env` file**

11. **Configure your local database in the `.env`file:**
    - Open the .env file and update the following configuration settings according to your local database setup:

    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```
    - Replace your_database_name, your_database_username, and your_database_password with your local database credentials.
    
    If you need assistance setting up a local database, you can refer to resources like [MySQL Installation Guide](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/) or [PostgreSQL Tutorial](https://www.postgresqltutorial.com/).


12. **Run `php artisan serve` in the Git Bash terminal**

13. **For automatic refresh, open another Git Bash terminal and run:**
    ```bash
    cd backend
    ```

    - And finally, to start the prototype run:
    ```bash
    npm run dev
    ```

`Good luck!`


# Copyright Information

This project, including its associated content, is intended for educational purposes within the academic context of the Requirements Engineering course. It should not be used for any professional or commercial purposes.

All rights to the content within this project, including but not limited to text, images, and other media, are reserved by the respective authors and copyright holders. The use, reproduction, or distribution of any part of this project for commercial purposes is strictly prohibited.

Please respect the intellectual property rights of the original creators and contributors. For any inquiries or concerns regarding the use of the content within this project, please contact the respective rights holders.

Thank you for understanding and respecting these terms.








