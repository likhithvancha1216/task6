# Short Report — Task 6: Password Strength Analysis

**Author:** Likhith Bharadwaj Reddy  
**Date:** 30-09-2025  

---

## Objective  
Generate multiple passwords with increasing complexity, test them using online tools, analyze results, and derive best practices.

---

## Passwords Tested & Results  

| Label   | Password Example       | Estimated Crack Time (from tool) | Notes |
|---------|------------------------|----------------------------------|-------|
| Weak    | `password123`          | Less than **1 second**           | Common word + digits, extremely weak |
| Medium  | `P@ssword2025!`        | Around **8 hours**               | Mix of case, number, and symbol, but still short |
| Strong  | `M!cr0$oft_SeCur1ty#2025` | More than **5 trillion years** | Long, random mix of cases, numbers, and symbols |

---

## Tools Used  
- **PasswordMeter.com** → Provided strength score (Weak / Medium / Strong)  
- **HowSecureIsMyPassword.net** → Provided estimated crack times  

---

## Visualizations  

### Chart 1
![Password Strength Comparison 1](Password_Strength_Comparison_1.png)

### Chart 2
![Password Strength Comparison 2](Password_Strength_Comparison_2.png)

---

## Observations  

- **Weak password**: Instantly crackable due to predictable word + small numbers.  
- **Medium password**: Somewhat better, but brute force or dictionary attacks can break it in hours.  
- **Strong password**: Extremely secure, virtually unbreakable with current computing power.  
- Password **length** and **diversity of characters** are the most important factors.  

---

## Analysis  

- Increasing length increases security exponentially.  
- Adding randomness (symbols, numbers, uppercase) resists dictionary attacks.  
- Even strong passwords are unsafe if **reused across accounts**.  
- Best practice is to use **unique, long, and random passphrases** with MFA enabled.  

---

## Best Practices & Recommendations  

- Use at least **12–16 characters**, ideally a passphrase.  
- Mix uppercase, lowercase, numbers, and symbols.  
- Avoid dictionary words or predictable substitutions like `Password → P@ssw0rd`.  
- Use **Multi-Factor Authentication (MFA)** for critical accounts.  
- Store unique passwords safely in a **password manager**.
