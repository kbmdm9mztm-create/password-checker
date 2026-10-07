# Password Checker

A simple web page that:
- rates password strength with a score and colored bar
- checks if a password appeared in known data breaches
- generates random strong passwords

The breach check uses the Have I Been Pwned API with k-anonymity,
so your password is never sent anywhere. Only the first 5 characters
of its hash leave your browser.

Built with HTML, CSS, and JavaScript.