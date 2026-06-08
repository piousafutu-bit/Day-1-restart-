   # Bug 04: Endpoint timeout - Server stopped responding
   
   **Date:** 08 June 2026  
   **API:** JSONPlaceholder /userz
   
   **Steps to Reproduce:**
   1. GET https://jsonplaceholder.typicode.com/userz
   
   **Expected Result:** 404 Not Found
   **Actual Result:** Server stopped responding / Timeout
   
   **Severity:** Medium - API not handling bad URLs gracefully
   **Screenshot:** [Add screenshot here]
