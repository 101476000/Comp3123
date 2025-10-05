# Class Exercise node Project

- Complete given class exercise
- Follow instruction mentions as a TODO - comments in source code files
- Fix any error found in the code
- Use SLACK or email to send any question

# Summary of Changes:
- Added an employeeModule to manage employee data.
## Defined handlers for each URL:
- / returns a welcome message.
- /employee returns all employee details.
- /employee/names returns employee full names in ascending order.
- /employee/totalsalary returns the total salary of all employees.
## Properly set response headers for JSON and HTML content.


---

## Submission Details
**Student:** Carlos Figuera  
**Student ID:** 101476000  
**Course:** COMP3123  
**Exercise:** exec03

### How to Run
1. Install Node.js (LTS).
2. In this folder, run:
   ```bash
   npm install
   npm run dev   # or: node index.js
   ```
3. Open:
   - http://localhost:8081/
   - http://localhost:8081/employee
   - http://localhost:8081/employee/names
   - http://localhost:8081/employee/totalsalary

### Summary of Changes Implemented
- Added `Employee.js` module with helper functions.
- Implemented handlers and correct headers for each endpoint.
- Added 405 for non-GET and 404 for unknown routes.

### GitHub (to be filled by student after pushing)
- Repository link: _<https://github.com/101476000/Comp3123>_
