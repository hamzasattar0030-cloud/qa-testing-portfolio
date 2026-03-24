# Login Test Cases

## TC_LOGIN_001
**Title:** Verify user can log in with valid credentials  

**Execution Date:** 24 March 2026

**Preconditions:**  
User is registered and on login page  

**Test Data:**  
Email: test@test.com  
Password: Test123  

**Steps:**  
1. Open login page  
2. Enter valid email  
3. Enter valid password  
4. Click login  

**Expected Result:**  
User is redirected to the products page and inventory is displayed

**Actual Result:**  
User is redirected to the products page and inventory is displayed

**Status:**  
Pass

**Tested By:** Hamza Sattar


---

## TC_LOGIN_002
**Title:** Invalid password  


**Execution Date:** 24 March 2026

**Preconditions:**  
User is on login page

**Test Data:**  
Email: valid user  
Password: invalid password  

**Steps:**  
1. Enter valid email  
2. Enter wrong password  
3. Click login  

**Expected Result:**  
Error message indicating invalid credentials is displayed 

**Actual Result:**  
Error message indicating invalid username or password is displayed

**Status:**  
Pass

**Tested By:** Hamza Sattar

---

## TC_LOGIN_003
**Title:** Empty fields  


**Execution Date:** 24 March 2026

**Preconditions:**  
User is on login page

**Test Data:**  
Email: blank  
Password: blank  

**Steps:**  
1. Leave email blank  
2. Leave password blank  
3. Click login  

**Expected Result:**  
Validation messages are displayed for required fields and login is blocked

**Actual Result:**  
Validation messages are displayed and login is prevented

**Status:**  
Pass 

**Tested By:** Hamza Sattar
