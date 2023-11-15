# Code-Projects-Blood-Bank-1.0

Welcome to the Code-Projects Blood Bank 1.0 repository. This project aims to provide efficient Blood Bank.

### CVE-2023-46014

- **Description:** SQL Injection vulnerability via `hospitalLogin.php`, 'hmail' and 'hpassword' parameters.
- **Affected Version:** 1.0
- **Affected File:** `/hospitalLogin.php`
- **Vulnerable Parameters:** 'hmail', 'hpassword'
- **Impact:** Local attackers can execute arbitrary code by manipulating the 'hmail' and 'hpassword' parameters.
- **Solution:** Implement parameterized queries and proper input validation for the 'hmail' and 'hpassword' parameters in `/hospitalLogin.php`.

### CVE-2023-46015

- **Description:** Reflected Cross-site Scripting vulnerability via `index.php`, 'msg' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/index.php`
- **Vulnerable Parameter:** 'msg'
- **Impact:** Attackers can inject malicious scripts into web pages viewed by other users.
- **Solution:** Implement proper input validation and sanitize user-supplied data in the 'msg' parameter.

### CVE-2023-46016

- **Description:** Reflected Cross-Site Scripting (XSS) vulnerability via `abs.php`, 'search' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/abs.php`
- **Vulnerable Parameter:** 'search'
- **Impact:** Allows attackers to inject malicious scripts into web pages viewed by other users.
- **Solution:** Implement proper input validation and sanitize user-supplied data in the 'search' parameter.

### CVE-2023-46017

- **Description:** SQL Injection vulnerability via `receiverLogin.php`, 'remail' and 'rpassword' parameters.
- **Affected Version:** 1.0
- **Affected File:** `/receiverLogin.php`
- **Vulnerable Parameters:** 'remail', 'rpassword'
- **Impact:** Local attackers can execute arbitrary code by manipulating the 'remail' and 'rpassword' parameters.
- **Solution:** Implement parameterized queries and proper input validation for the 'remail' and 'rpassword' parameters  in `/receiverLogin.php`.

### CVE-2023-46018

- **Description:** SQL Injection vulnerability via `receiverReg.php`, 'remail' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/receiverReg.php`
- **Vulnerable Parameter:** 'remail'
- **Impact:** Local attackers can execute arbitrary code by manipulating the 'remail' parameter.
- **Solution:** Implement parameterized queries and proper input validation for the 'remail' parameter in `/receiverReg.php`.

### CVE-2023-46019

- **Description:** Reflected Cross-site Scripting vulnerability via `abs.php`, 'error' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/abs.php`
- **Vulnerable Parameter:** 'error'
- **Impact:** Allows attackers to inject malicious scripts into web pages viewed by other users.
- **Solution:** Implement proper input validation and sanitize user-supplied data in the 'error' parameter.

### CVE-2023-46020

- **Description:** Stored Cross-site Scripting vulnerability via `updateprofile.php`, 'rename', 'remail', 'rphone', and 'rcity' parameters.
- **Affected Version:** 1.0
- **Affected File:** `/updateprofile.php`
- **Vulnerable Parameters:** 'rename', 'remail', 'rphone', 'rcity'
- **Impact:** Allows attackers to inject malicious scripts into web pages viewed by other users.
- **Solution:** Implement proper input validation and sanitize user-supplied data in the mentioned parameters.

### CVE-2023-46021

- **Description:** Out-of-Band SQL Injection vulnerability via `cancel.php`, 'reqid' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/cancel.php`
- **Vulnerable Parameter:** 'reqid'
- **Impact:** Local attackers can execute arbitrary code by manipulating the 'reqid' parameter.
- **Solution:** Implement parameterized queries and proper input validation for the 'reqid' parameter in `cancel.php`.

### CVE-2023-46022

- **Description:** Out-of-Band SQL Injection vulnerability via `delete.php`, 'bid' parameter.
- **Affected Version:** 1.0
- **Affected File:** `/delete.php`
- **Vulnerable Parameter:** 'bid'
- **Impact:** Local attackers can execute arbitrary code by manipulating the 'bid' parameter.
- **Solution:** Implement parameterized queries and proper input validation for the 'bid' parameter in `/delete.php`.

---
