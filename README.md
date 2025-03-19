<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyHealth Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #34495e;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
            display: block;
        }
        nav a:hover {
            background-color: #1abc9c;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #1abc9c;
            color: white;
        }
        footer {
            background-color: #325980;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        MyHealth Dashboard
    </header>

    <!-- Top Navigation -->
    <nav>
        <a href="http://127.0.0.1:5500/ibm.html">Home</a>
        <a href="http://127.0.0.1:5500/website.html">Appointments</a>

        <a href="http://127.0.0.1:5500/ab.html">Medical History</a>
        <a href="http://127.0.0.1:5500/abc.html">Settings</a>
    </nav>

    <!-- Main Container -->
    <div class="container">

        <!-- Patient Information Section -->
        <section aria-labelledby="patient-info">
            <h2 id="patient-info">Patient Information</h2>
            <p><strong>Name:</strong> Dhruv Kumar</p>
            <p><strong>Date of Birth:</strong> Dec 6, 2002</p>
            <p><strong>Contact:</strong> (+91)6207109955</p>
            <p><strong>Emergency Contact:</strong> Anish Kumar:- (+91)9955427262</p>
        </section>

        <!-- Upcoming Appointments Section -->
        <section aria-labelledby="appointments">
            <h2 id="appointments">Upcoming Appointments</h2>
            <table aria-describedby="appointments">
                <thead>
                    <tr>
                        <th>Date</th>
                        <th>Time</th>
                        <th>Doctor</th>
                        <th>Appointment Type</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>March 30, 2025</td>
                        <td>10:00 AM</td>
                        <td>Dr. Michael</td>
                        <td>General Checkup</td>
                    </tr>
                    <tr>
                        <td>April 5, 2025</td>
                        <td>2:30 PM</td>
                        <td>Dr. Trisha</td>
                        <td>Heart Cheak-up</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Medical History Section -->
        <section aria-labelledby="medical-history">
            <h2 id="medical-history">Medical History</h2>
            <details>
                <summary>View Medical History</summary>
                <ul>
                    <li><strong>Allergies:</strong>
                        <ul>
                            <li>Peanuts</li>
                            <li>Pollen</li>
                        </ul>
                    </li>
                    <li><strong>Conditions:</strong>
                        <ul>
                            <li>beta blockers</li>
                            <li>Asthma</li>
                        </ul>
                    </li>
                    <li><strong>Medications:</strong>
                        <ul>
                            <li>Anticoagulants</li>
                            <li>Albuterol</li>
                        </ul>
                    </li>
                    <li><strong>Past Surgeries:</strong>
                        <ul>
                            <li>Cardiovascular Surgery - 2015</li>
                        </ul>
                    </li>
                </ul>
            </details>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 MyHealth. <a href="#">Contact Us</a> | <a href="#">Terms of Service</a></p>
    </footer>

</body>
</html>