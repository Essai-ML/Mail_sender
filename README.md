<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batch Email Sender</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        h2 {
            color: #555;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>

    <h1>Batch Email Sender</h1>

    <h2>Overview</h2>
    <p>
        The <strong>Batch Email Sender</strong> is an application that allows users to send personalized emails to multiple recipients using data from a CSV or Excel file. With a straightforward user interface, users can authenticate their email accounts, customize email content, and send batch emails effortlessly.
    </p>

    <h2>Features</h2>
    <ul>
        <li><strong>User Authentication:</strong> Secure login with SMTP email and app password.</li>
        <li><strong>File Upload:</strong> Load recipient details from CSV or Excel files.</li>
        <li><strong>Dynamic Content:</strong> Personalize email content with placeholders.</li>
        <li><strong>Test Email Functionality:</strong> Verify email formatting by sending a test email.</li>
        <li><strong>Batch Sending:</strong> Efficiently send personalized emails to multiple recipients.</li>
        <li><strong>HTML Support:</strong> Create visually appealing emails with HTML formatting.</li>
    </ul>

    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li><code>customtkinter</code></li>
        <li><code>pandas</code></li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/your_username/batch-email-sender.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd batch-email-sender</code></pre>
        </li>
        <li>Install the required libraries:
            <pre><code>pip install customtkinter pandas</code></pre>
        </li>
        <li>Run the application:
            <pre><code>python email_sender.py</code></pre>
        </li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li>Launch the application.</li>
        <li>Log in with your SMTP email and app password.</li>
        <li>Load a CSV or Excel file containing the names and email addresses of recipients.</li>
        <li>Select the appropriate columns for names and emails.</li>
        <li>Enter the email subject and body content. Use <code>{name}</code> as a placeholder for dynamic personalization.</li>
        <li>Optionally, enter a signature for your emails.</li>
        <li>Click the "Send Test Email" button to send a test email to yourself.</li>
        <li>Once satisfied, click the "Send Emails" button to send emails to all recipients.</li>
    </ol>

    <h2>Contributing</h2>
    <p>
        Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
    </p>

    <h2>License</h2>
    <p>
        This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more information.
    </p>

    <h2>Acknowledgments</h2>
    <p>
        Inspired by the need for efficient email communication.<br>
        Thanks to the developers of the libraries used.
    </p>

</body>
</html>
