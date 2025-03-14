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
