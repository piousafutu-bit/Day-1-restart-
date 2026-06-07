# Day 3: API Testing with Postman
Date: [Today]

## Test 1: Get User Data
**API URL:** https://jsonplaceholder.typicode.com/users/1
**Method:** GET
**Expected:** Status 200 OK + user data shows
**Actual:** Status 200 OK
**Result:** PASS ✅
**Notes:** API returns data correctly

## Test 2: Get Missing User
**API URL:** https://jsonplaceholder.typicode.com/users/99999
**Method:** GET
**Expected:** Status 404 Not Found + error message
**Actual:** Status 404 Not Found
**Result:** PASS but could be better
**Notes:** Should return message "User not found" not just 404
