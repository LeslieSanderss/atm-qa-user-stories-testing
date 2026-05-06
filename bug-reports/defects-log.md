# 🐞 Defect Log – ATM System

---

## 🐛 Bug #1: PIN Validation Issue
**Severity:** High  
**Module:** Login  

### Description:
System allows PINs with fewer than 4 digits.

### Steps to Reproduce:
1. Go to login page
2. Enter card number
3. Enter PIN with 2 digits
4. Submit

### Expected Result:
System should reject invalid PIN length

### Actual Result:
Login proceeds or partial validation occurs

---

