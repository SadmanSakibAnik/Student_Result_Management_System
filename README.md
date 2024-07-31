<!DOCTYPE html>
<html>
<head>
    <title>Student Result Management System - README</title>
</head>
<body>
    <h1>Student Result Management System</h1>
    <p>The Student Result Management System (SRMS) is a comprehensive software application designed to manage and streamline the process of recording, calculating, and displaying student academic results. This system is intended for educational institutions to efficiently handle student grades, generate report cards, and provide access to academic performance data.</p>
    
    <h2>Features</h2>
    <ul>
        <li><strong>User Authentication:</strong> Secure login for administrators, teachers, and students.</li>
        <li><strong>Student Management:</strong> Add, update, and delete student information.</li>
        <li><strong>Course Management:</strong> Manage course details including course code, name, and credit hours.</li>
        <li><strong>Result Entry:</strong> Input student grades for various assessments and exams.</li>
        <li><strong>Grade Calculation:</strong> Automatic calculation of final grades based on predefined criteria.</li>
        <li><strong>Report Generation:</strong> Generate and print student report cards and transcripts.</li>
        <li><strong>Data Export/Import:</strong> Export and import data in various formats (CSV, Excel).</li>
        <li><strong>User Roles:</strong> Different access levels for administrators, teachers, and students.</li>
        <li><strong>Notifications:</strong> Send notifications to students about their results and other important information.</li>
    </ul>
    
    <h2>Installation</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li><a href="https://nodejs.org/" target="_blank">Node.js</a> (version 14.x or higher)</li>
        <li><a href="https://www.mysql.com/" target="_blank">MySQL</a> (version 8.x or higher)</li>
    </ul>
    
    <h3>Steps</h3>
    <ol>
        <li><strong>Clone the repository:</strong></li>
        <pre><code>git clone https://github.com/yourusername/student-result-management-system.git</code></pre>
        
        <li><strong>Navigate to the project directory:</strong></li>
        <pre><code>cd student-result-management-system</code></pre>
        
        <li><strong>Install the dependencies:</strong></li>
        <pre><code>npm install</code></pre>
        
        <li><strong>Configure the database:</strong></li>
        <ul>
            <li>Create a database named <code>srms</code> in MySQL.</li>
            <li>Update the database configuration in the <code>.env</code> file located in the project root directory.</li>
        </ul>
        
        <li><strong>Run the database migrations:</strong></li>
        <pre><code>npm run migrate</code></pre>
        
        <li><strong>Start the application:</strong></li>
        <pre><code>npm start</code></pre>
        
        <li><strong>Access the application:</strong></li>
        <p>Open your browser and go to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a>.</p>
    </ol>
    
    <h2>Usage</h2>
    <h3>Admin Panel</h3>
    <ul>
        <li><strong>Login:</strong> Access the admin panel using your credentials.</li>
        <li><strong>Manage Students:</strong> Add, edit, or delete student records.</li>
        <li><strong>Manage Courses:</strong> Add, edit, or delete course information.</li>
        <li><strong>Enter Results:</strong> Input student grades for different assessments.</li>
        <li><strong>Generate Reports:</strong> Generate and download report cards and transcripts.</li>
    </ul>
    
    <h3>Teacher Portal</h3>
    <ul>
        <li><strong>Login:</strong> Access the teacher portal using your credentials.</li>
        <li><strong>View Courses:</strong> View courses assigned to you.</li>
        <li><strong>Enter Grades:</strong> Input student grades for the courses you teach.</li>
        <li><strong>View Reports:</strong> View and download student report cards.</li>
    </ul>
    
    <h3>Student Portal</h3>
    <ul>
        <li><strong>Login:</strong> Access the student portal using your credentials.</li>
        <li><strong>View Results:</strong> Check your academic performance and download report cards.</li>
        <li><strong>Notifications:</strong> Receive notifications about new grades and important updates.</li>
    </ul>
    
    <h2>Contributing</h2>
    <p>We welcome contributions from the community. If you would like to contribute,
