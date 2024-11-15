Department Portfolio Website
Welcome to the Department Portfolio Website project for the Professional Project Department at Brigham Young University–Idaho (BYUI). This platform is designed to showcase the capabilities of our students, programs, and staff to companies and prospective students.

Table of Contents
Project Overview
Features
Technical Requirements
Installation and Setup
Usage
Contributing
License
Acknowledgments
Project Overview
The Department Portfolio Website aims to:

Showcase Student Work: Highlight senior projects, internship experiences, and activities from the Computer Society.
Inform Prospective Students: Provide insights into what has been accomplished and the opportunities available within the department.
Engage Companies: Demonstrate the skills and projects our students and faculty are capable of, facilitating potential collaborations and employment opportunities.
Features
Dynamic Content Display: Present various categories such as Senior Projects, Internships, and Computer Societies.
Portfolio Submission Workflow: Enable students to submit and update their portfolios using GitHub's issue-branch-merge workflow.
Search and Filtering: Allow visitors to search portfolios by location, company, year, or project type.
Responsive Design: Ensure the website is optimized for both desktop and mobile devices.
Technical Requirements
Platform: Hosted on GitHub Pages.
Technologies: HTML, CSS, JavaScript for the front-end; GitHub Actions for automating content rendering from Markdown to HTML.
Authentication: Secure login for administrators and students via BYUI authentication (SSO).
Installation and Setup
To set up the project locally:

Clone the Repository:

bash
Copy code
git clone https://github.com/BYUI-Professional-Project-Department/portfolio-website.git
cd portfolio-website
Install Dependencies: Ensure you have Node.js installed. Then, run:

bash
Copy code
npm install
Run the Development Server:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000 to view the website locally.

Usage
Viewing Portfolios: Navigate through the categories to explore various student projects and experiences.
Submitting a Portfolio:
Create an issue in the relevant category repository.
Checkout a new branch and add your portfolio content following the provided template.
Commit your changes and create a pull request for review.
Upon approval, your portfolio will be published on the website.
Contributing
We welcome contributions from students and faculty. To contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes with clear and concise messages.
Push your branch and create a pull request.
Ensure your code adheres to the project's coding standards and passes all tests.
License
This project is licensed under the MIT License.

Acknowledgments
We extend our gratitude to all students, faculty, and contributors who have made this project possible. Special thanks to the BYUI CSE 397 Team 2 for their dedication and hard work.

