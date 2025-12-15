# TLS-Gmail-s-SMTP-server
Created by Dakota Wellerbrady

Overview:
This Python script allows you to send an email through Gmail's SMTP server using TLS encryption. 
The script connects to the Gmail SMTP server (smtp.gmail.com), authenticates with your Gmail 
account using base64-encoded credentials, and sends an email to a specified recipient.


Requirements:
- Python 3.x installed on your system.
- An App password from Gmail (for accounts with 2-step verification).

Setting Up:
- Replace the placeholders for sender_email, receiver_email, and password in the script with your Gmail credentials and target email.
- The email body (msg), (endmsg) and subject (subject) can be customized to your message.

Ensure Network Access: 
Make sure you're connected to the internet, as the script connects to Google's SMTP server over port 587.

How to run program:
1. Open a terminal and go to the directory that has the file in it.
2. Type "python SMTPClient.py" into the terminal and hit the enter key
3. Your done!


