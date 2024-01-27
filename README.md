Talent Standard Task Code Repository
Welcome to the Job Junction projectCode Repository. This project serves as a platform for job hunters and employers built using  ReactJS, C# Web API, and MongoDB in Talent Code Architecture. Below is the documentation to help you get started and explore the different modules.

Standard Tasks
Module 1: Talent Profile Page
 LinkedIn URL & GitHub URL
 Description
 User Details Component
 Address
 Nationality
 Languages
 Skills
 Work Experience
 Visa Status
 Job Seeking Status
 Photo Upload

Module 2: Talent Feed Page
Front-end
 Add AJAX calls to retrieve data from the controllers
Back-end
 Build action methods in controllers and services to fetch data from the database

FAQs
Installation Steps
Find the folder containing webpack.config.js in the solution explorer.
Right-click on the folder and select 'Open Folder in File Explorer.'
Open the command prompt and navigate to the folder with webpack.config.js.
Install npm utility packages: npm install
Verify webpack version: webpack -version
Launch Talent Project
Detailed Instructions

Get the latest source via Source Control Explorer.
Run webpack:
arduino
Copy code
cd C:\Talent\Talent\App\Talent.App.WebApp\wwwroot\js\react
npm run build
Launch Talent.WebApp project in Visual Studio. Register an account using your email address and log in.
Project Structure
Detailed Structure

Web Application:
Talent.WebApp: All frontend files are located here.
Microservices:
Talent.Services.Identity: Backend functions related to Login/Logout.
Talent.Services.Profile: Backend functions related to Profile.
Talent.Services.Talent: Backend functions related to Talent Matching, Jobs.
