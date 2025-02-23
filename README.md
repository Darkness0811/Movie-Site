# Database-connectivity-for-website-using-local-server
**Project Report: Cinephilia Web Application Using XAMPP**

**1. Introduction**
The Cinephilia web application is a movie-related platform developed using HTML, CSS, PHP, and XAMPP as the local server environment. The project provides users with functionalities such as viewing movie details, user registration, and login authentication.

**2. Technologies Used**
- XAMPP (Apache, MySQL, PHP, and Perl)
- HTML & CSS for front-end design
- PHP for back-end processing
- MySQL for database management

**3. Features**
- User authentication (Login and Registration)
- Movie listing with details
- Search functionality
- Responsive design

**4. Implementation Steps**

**Step 1: Install XAMPP**
- Download and install XAMPP from the official website.
- Start the Apache and MySQL services from the XAMPP Control Panel.

**Step 2: Set Up the Project Files**
- Place the project files inside the `htdocs` directory of XAMPP (e.g., `C:\xampp\htdocs\cinephilia`).
- Ensure that all required files (HTML, CSS, PHP) are correctly structured within the project folder.

**Step 3: Configure the Database**
- Open `phpMyAdmin` via `http://localhost/phpmyadmin/`.
- Create a new database named `cinephilia`.
- Create necessary tables (e.g., `users` for login authentication, `movies` for storing movie details).

**Step 4: Implement User Authentication**
- `register.php` handles user registration, storing usernames, emails, and passwords in the database.
- `login.php` verifies user credentials against the stored records in the `users` table.

**Step 5: Front-End Design**
- `index.html` provides a login form for users.
- `register.html` allows new users to sign up.
- `style.css` ensures responsive and aesthetic UI design.

**Step 6: Movie Display and Search Functionality**
- `CINEPHILIA.html` lists movies along with their details.
- The search feature enables users to find movies based on specific criteria.

**Step 7: Testing and Deployment**
- Run the application by accessing `http://localhost/cinephilia/`.
- Test all functionalities (registration, login, movie browsing, and search).
- Fix any bugs or errors.

**5. Conclusion**
The Cinephilia web application successfully integrates front-end and back-end functionalities using XAMPP. This project serves as a foundation for developing more advanced movie-related platforms with additional features such as user reviews, ratings, and recommendations.

