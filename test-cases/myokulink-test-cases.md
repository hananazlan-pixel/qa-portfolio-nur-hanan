## MY OKULink – Functional Test Cases

---

Test Case ID: TC-MYO-001  
Title: Verify user can log in with valid credentials  

Precondition:
- User has a registered account

Steps:
1. Open MY OKULink app
2. Enter valid email
3. Enter valid password
4. Tap Login

Expected Result:
- User is successfully logged in and redirected to homepage/dashboard

---

Test Case ID: TC-MYO-002  
Title: Verify error message is shown for invalid login  

Steps:
1. Open MY OKULink app
2. Enter invalid email or password
3. Tap Login

Expected Result:
- Error message is displayed indicating invalid credentials

---

Test Case ID: TC-MYO-003  
Title: Verify user can log out successfully  

Steps:
1. Log in to MY OKULink app
2. Navigate to settings
3. Tap Logout

Expected Result:
- User is logged out and redirected to login page screen
