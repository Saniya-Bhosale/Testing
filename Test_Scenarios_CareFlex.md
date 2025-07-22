# 📋 Test Scenarios – CareFlex Functional Testing

This document outlines high-level test scenarios across different modules.

---

## 👨‍⚕️ Doctor Registration

1. Verify all required fields must be filled.
2. Validate email format (e.g., abc@domain.com).
3. Confirm that password and confirm password must match.
4. Check for minimum password length.
5. Ensure duplicate email cannot be registered again.
6. Ensure doctor data is saved correctly to the database.

---

## 👨‍⚕️ Doctor Login

1. Login works with valid credentials.
2. Error message shown when invalid email/password is entered.
3. Error message shown if email is not registered.
4. Validate form is not submitted with empty fields.

---

## 🧑‍⚕️ Patient Registration

1. Verify all patient fields  must be filled.
2. Check for valid numerical values in height and weight.
3. Email format should be validated.
4. Password and confirm password should match.
5. System should validate the Doctor Key with existing records.
6. Error message must be shown if Doctor Key is invalid.
7. Confirm patient data is saved to the correct doctor's account.

---

## 🧑‍⚕️ Patient Login

1. Successful login with correct credentials.
2. Error message shown on incorrect credentials.
3. Validate login with registered and non-registered email IDs.
4. Ensure session or token is created (if applicable).

---

## 🔑 Doctor Key Validation

1. Doctor Key should map to a valid doctor only.
2. Invalid or expired Doctor Key should be rejected.
3. Each patient must be mapped correctly to the corresponding doctor via the key.
