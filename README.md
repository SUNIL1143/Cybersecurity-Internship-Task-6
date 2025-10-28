# Cybersecurity-Internship-Task-6
Report and analysis for Task 6 of the Elevate Labs Cyber Security Internship, focusing on password strength evaluation and security best practices.

# **Task 6: Password Strength Analysis Report**

## **1\. Objective**

The objective of this task was to understand what makes a password "strong" and to test the strength of different passwords using online tools. In this report, we have tested passwords of varying complexity and analyzed their results.

## **2\. Tool Used**

* **Tool:** Online Password Strength Checker (like passwordmeter.com)  
* **Purpose:** To give each password a score (0% to 100%) and provide feedback on its complexity (strength).

## **3\. Password Strength Test Results**

We tested four (4) different passwords to understand the difference from "Very Weak" to "Very Strong".

| Password Text | Score | Complexity Feedback | Analysis (Why it is rated this way) |
| :---- | :---- | :---- | :---- |
| myname | 7% | Very Weak | **Very Weak:** This is a dictionary word, is short, and only contains lowercase letters. It is very easy to guess. |
| admin123 | 39% | Weak | **Weak:** This is a very common combination of a username (admin) and a number sequence (123). It has no uppercase letters or symbols. |
| CASTRANTeREn | 45% | Good | **Good:** Its length (12 characters) is good, and it mixes uppercase and lowercase letters. However, it is not "Very Strong" because it lacks numbers or symbols. |
| B%3\_$Sq'\!UhW9yTm | 100% | Very Strong | **Very Strong:** This is an ideal password. Its length (15 characters) is long, and it uses all four elements: Uppercase Letters (B, S, U, W, T), Lowercase Letters (q, h, y, m), Numbers (3, 9), and Symbols (%, \_, $, \!, '). |

## **4\. How Password Complexity Affects Security**

Password complexity (the use of length, numbers, and symbols) directly affects its security.

* **Entropy:** Each new character type (number, symbol) increases the "possible combinations" for guessing the password exponentially.  
* **Attack Time:** A simple 6-character password (myname) can be cracked in seconds. In contrast, a 15-character complex password (B%3\_$Sq'\!UhW9yTm) could take years to crack.

Our test results clearly show this:

* Passwords like myname (7%) and admin123 (39%) are very vulnerable to **Dictionary Attacks** and **Brute Force Attacks**.  
* A password like B%3\_$Sq'\!UhW9yTm (100%) makes these attacks practically impossible.

## **5\. Common Password Attacks**

1. **Brute Force Attack:** In this attack, the hacker's software rapidly tries every possible combination (e.g., 'a', 'b', 'c', 'aa', 'ab', ...) until the correct password is found. The longer and more complex the password, the more time this attack will take.  
2. **Dictionary Attack:** In this attack, the software tries a pre-built list of common words, names, and simple number combinations (e.g., 'password', '123456', 'admin123'). Our myname and admin123 passwords would be cracked instantly by this attack.

## **6\. Best Practices & Tips Learned**

From this evaluation, we have learned these best practices for creating strong passwords:

1. **Length is Key:** Always use a password that is at least 12-15 characters long. The longer, the better.  
2. **Use All Four Types:** A strong password should always have a mix of these four elements:  
   * Uppercase Letters (A-Z)  
   * Lowercase Letters (a-z)  
   * Numbers (0-9)  
   * Symbols (\!, @, \#, $, %, etc.)  
3. **Avoid Common Words:** Never use dictionary words, your name, "password", or other common words like "admin" in your password.  
4. **Use Passphrases:** A complex password (B%3\_$Sq'\!UhW9yTm) is hard to remember. Instead, you can create a **passphrase**, like My-House@Nanded-Is-Great\!. This is long, includes all character types, and is easier to remember.  
5. **Use a Password Manager:** Creating and remembering a different, strong password for every account is difficult. Password manager tools (like Bitwarden, 1Password) generate strong passwords for you and store them safely.  
6. **Enable MFA (Multi-Factor Authentication):** Don't rely only on a password. Wherever possible, be sure to enable MFA (like an OTP) for an extra layer of security.
