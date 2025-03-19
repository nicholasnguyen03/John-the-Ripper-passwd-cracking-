Overview:
This project demonstrates password cracking using John the Ripper (JtR), a powerful open-source password security auditing tool.The exercise involved cracking hashed passwords using different attack techniques, including Single Crack Mode, Wordlist Mode, and Incremental Mode with masks and custom length constraints.

How It Works:
Gather hashed passwords from a file (e.g., hashes.txt).
Use John the Ripper to crack passwords using:
🔹 Single Crack Mode – Uses system/user details to generate guesses.
🔹 Wordlist Mode – Tests passwords from a predefined wordlist (e.g., rockyou.txt).
🔹 Incremental Mode – Brute-force attack testing all possible character combinations.
🔹 Mask Mode – Optimized brute-force with custom character sets and position rules.
🔹 Custom Min & Max Length Settings – Restricts password length range to speed up attacks.
Analyze cracked passwords to evaluate password security.

This is a project given by Codepath, where 1,000 Username/Password hashes were given to crack. I was able to crack over 50% of the 1,000 passwords and given below are the password length distribution. 

Length (# chars)	Count (# passwords)
(1	| 2)
(2	| 13)
(3	| 87)
(4	| 284)
(5	| 487)
(6	| 107)
(7	| 18)
(8	| 2)
