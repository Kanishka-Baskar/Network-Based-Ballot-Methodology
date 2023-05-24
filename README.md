# Network-Based-Ballot-Methodology
1. Network Based Balloting System is a project based on PHP and MySQL. Hence, XAMPP/WAMP/MAMP/LAMP should be installed. 
2. Create a database named vote using phpMyAdmin and upload the file named "vote".
3. Here, The instructions are given to run the project using XAMPP.
4. Open XAMPP, Start Apache, MySQL, FileZilla.
5. Now, Run the project using any web browser with the command "localhost/voting/".
6. The Login_ID, User_Name and Password for the admin is "1", "admin" and "admin" respectively.
7. The Login_ID, User_Name and Password for the user is "4", "user" and "user" respectively.

Project Description:
Network Based Balloting Methodology can also be called as NBBM which can be used by managements, co-operate companies and also by government. Managements such as School
management, College management, Clubs can make use of NBBM to select Secretary, Head, President, Vice President, and Best Candidate of the year and so on. Government can use NBBM to select the Prime Minister, Chief Minister, Councilor, Education Minister, and so on.

Modules used in Network Based Balloting Methodology are:
	• Admin Login
	• User Login
	• Student Login
	• Student Registration
	• Voter’s List
	• Candidate List

Sub-modules used in NBBM are:
	• Casting Ballot
	• Report

Admin Login:
• Admin can login using ID and Password.
• ‘N’ number of Users and Student ID can be created/removed by the Admin.
• The Admin can activate Student ID for particular period of time i.e., Student ID can be activated only during the period of election time and then Student ID can
be deactivated and so the Student cannot login i.e., the Students are restricted from logging in.
• Finally, the report can be viewed by the Admin i.e., the details of Candidates who got more no. of ballots.

User Login:
• Users can login using their User ID and password created by Admin.
• Users can be created by the Admin and the User’s login details can be viewed by the Admin.
• Users can also add the Candidates and their details or even remove the Candidates.
• Users are helpful to create the Student ID. Thus, it reduces the workload for the Admin.
• Finally, Users can also view the report i.e., number of ballots received by each Candidate details can be viewed by the User too.

Student Login:
• First of all, Student ID should be added by the Admin or User. Then, Student ID should be registered by the Student and then only the Student can Login using their Student ID and Password.
• Before logging in, the Admin should activate Students. Otherwise, it’s not possible to Login.
• Invalid Student ID and Password leads to the home with a pop up window saying invalid student details.

Student Registration:
• The Student ID should be registered before logging in.
• After adding the Student ID by the Admin or User, the Student should make the registration.
• During Registration, the following details are collected from the student,
	❖ Student ID
	❖ Password
	❖ First Name
	❖ Last Name
	❖ Gender
	❖ Course Name
	❖ Year of Studying
• At last, they have to click on “Create My Account” button for successful registration.

Voter List:
• The registered Student list can be seen by everyone using the webpage.
• Students name will be displayed with the following details,
	❖ Student ID
	❖ Name
	❖ Gender
	❖ Course
	❖ Year
	❖ Account status(active/inactive)
	❖ Status(voted/not voted)
	❖ Date Registered

Candidate List:
• In this module, Candidate name list will be displayed who has added by the Admin or User.
• It is visible to everyone using this website.
• The Candidate list will be displayed with the following details,
	❖ First Name
	❖ Last Name
	❖ Gender
	❖ Year
	❖ Course

Casting ballot:
• The Student can Login using their Student ID and password.
• After logging in, Students can select their Candidate and cast their ballot by clicking the submit button at the end of the page.
