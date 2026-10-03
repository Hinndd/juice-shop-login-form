# Juice Shop Login Form (Secure Demo)

A simple HTML/CSS/JavaScript login form built for Homework 2B (Part 2), mimicking the OWASP Juice Shop login page.

## What it does
- Collects an email and password
- Client-side validation prevents empty submissions
- Validates that the email contains "@" and the password is at least 8 characters
- Simulates a server-side validation check (via a mock async function) in addition to client-side checks

## How to run it
1. Clone or download this repository
2. Open `index.html` directly in any web browser (no server or build step required)
3. Try submitting with an empty field, an invalid email, a short password, and valid credentials to see the different validation messages
