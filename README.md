# Password Strength & Security Evaluation Lab

## 🛡️ Project Overview
This project explores the relationship between password complexity and the time required to crack them. It includes a comparison of different password types, an analysis of common cyber attacks, and best practices for digital security.

---

## 📊 Password Strength Comparison
I tested four password variations using industry-standard strength checkers to analyze how complexity affects security.


| Complexity | Password Example | Length | Time to Crack | Observation |
| :--- | :--- | :--- | :--- | :--- |
| **Very Low** | `password123` | 11 | Instantly | Extremely common; found in every leaked database. |
| **Low** | `Password224` | 11| 1 Month| Predictable pattern (Capital + Word + Number). |
| **Medium** | `G7#pQ2!9zL` | 10 | 5 Years | High randomness but lacks sufficient length. |
| **High** | `Correct-Horse-Battery-Staple!1` | 29 | Centuries | Length + Passphrase style is the most secure. |

---

## 💡 Key Lessons & Best Practices
*   **Length > Complexity:** Adding three random letters is often more effective than adding one complex symbol. Aim for 12-16+ characters.
*   **The Passphrase Method:** Use 4-5 random, unrelated words. They are easier for humans to remember but harder for machines to guess.
*   **Unique Everything:** Never use the same password for more than one account.
*   **Use a Password Manager:** Store unique, complex passwords in an encrypted vault (e.g., Bitwarden, 1Password).

---

## 🔍 Research: Common Attacks
1. **Brute Force Attack:** An attacker uses software to try every possible combination of characters. 
   * *Impact:* Short passwords (under 8 characters) are cracked in seconds.
2. **Dictionary Attack:** An attacker uses a list of common words and known leaked passwords.
   * *Impact:* Using "dictionary" words (even with numbers) makes passwords vulnerable.
3. **Credential Stuffing:** Attackers use usernames and passwords leaked from one site to log into others.
   * *Impact:* Shows why password reuse is dangerous.

---

## 📝 Summary: How Complexity Affects Security
Password complexity is the primary defense against automated "guessing" attacks. Its effectiveness is based on two main factors:

*   **Exponential Entropy:** Every time you add a character or a different type of character (symbol, number, uppercase), you exponentially increase the number of possible combinations. This makes it mathematically impossible for standard computers to guess the password in a human lifetime.
*   **Defense Against Pattern Recognition:** Hackers use algorithms that look for common human patterns (like replacing 'a' with '@'). True complexity avoids these predictable patterns, forcing the attacker to use "Brute Force" which is the slowest and most expensive method of attack.

---

## 🛠️ Tool Used
* [Security.org Password Strength Checker]([https://www.security.org](https://www.security.org/how-secure-is-my-password/))

---

