# send-email.py

This Python script sends an email message using SMTP SSL via Gmail.

## Usage

1. **Prepare Script:**
   - Replace `[message]` with your email message.
   - Replace `[subject]` with your email subject.
   - Replace `[email-from]` with the sender's email address.
   - Replace `[email-to-1], [email-to-2]` with the recipient's email addresses.
   - Replace `[email-sender-real]` with the sender's real email address.
   - Replace `[email-password-real]` with the sender's real email password.

2. **Run the Script:**
   - Execute the script using Python.

## Requirements

- Python 3.x
- Libraries:
  - smtplib

## Overview

This script sends an email message using SMTP SSL via Gmail. It requires the sender's Gmail email address and password for authentication.

## How it Works

- The script creates an email message using the provided message, subject, sender, and recipient information.
- It sends the email message via Gmail's SMTP server using SMTP SSL.
- After sending the email, it prints a confirmation message along with the current date and time.
