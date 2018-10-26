<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?

    Sessions allow the server to store user data between HTTP requests.

2. What does bcrypt do to help us store passwords in a secure manner.

    bcrypt is a security algorithm designed for hashing passwords,
	so you don't store user passwords in database as a plain text.

3. What does bcrypt do to slow down attackers?

    bcrypt encrypts passwords in several rounds,
	every round adds time to generate the hash.
	It slows down the attacks.

4. What are the three parts of the JSON Web Token?

    header 
	payload
	signature
