# Simple-Gmail-Mail-Sender-Using-Automation-Python-Script-
Simple Gmail Mail Sender is a lightweight Python utility that sends emails using Gmail’s SMTP server. It demonstrates how to securely authenticate using an App Password and send emails programmatically.

🚀 Simple Gmail Mail Sender

A simple Python script to send emails using Gmail SMTP with App Password authentication.

✨ Features

✅ Secure Gmail SMTP connection (SSL)

✅ App Password authentication

✅ Clean and reusable function

✅ Beginner friendly

✅ Lightweight implementation

🛠 Requirements

Python 3.x

Gmail account

Gmail App Password enabled

Install Python if not already installed:

python --version

🔐 Important: Gmail App Password Setup

⚠️ Do NOT use your real Gmail password

Steps:

Enable 2-Step Verification in your Google account

Go to App Passwords

Generate a password for:

App: Mail

Device: Windows Computer (or Other)

Copy the generated 16-character password

▶️ How to Run
Step 1: Clone the repository
git clone https://github.com/your-username/simple-gmail-mail-sender.git
cd simple-gmail-mail-sender

Step 2: Update credentials

Open the script and modify:

sender_email = "your_email@gmail.com"
app_password = "your_generated_app_password"
receiver_email = "receiver_email@gmail.com"

Step 3: Run the program
python mail_sender.py


✅ Output:

Mail Sent Successfully

📧 Function Description
Mail_Send(sender, app_password, receiver, subject, body)
Parameter	Type	Description
sender	str	Sender Gmail address
app_password	str	Gmail App Password
receiver	str	Receiver email address
subject	str	Email subject
body	str	Email body
🔄 How It Works

Creates EmailMessage object

Sets headers (From, To, Subject)

Adds email body

Connects to Gmail SMTP (SSL)

Authenticates using App Password

Sends email

Closes connection

⚠️ Security Best Practices

❌ Never hardcode real passwords
❌ Never commit credentials to GitHub
✅ Use environment variables in production
✅ Use App Password instead of Gmail password

🚀 Future Improvements

 Add attachment support

 Add HTML email support

 Add multiple recipients

 Add logging

 Add environment variable support

 Add CLI arguments

👨‍💻 Author

Krishna Govindrav Hitnalikar

📜 License

This project is open-source and available under the MIT License.
