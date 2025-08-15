# Task 3 – SQL Injection Demonstration

## Objective
Demonstrate how **SQL Injection (SQLi)** vulnerabilities can be exploited in a web application login page, and explain how to prevent them.

## Tools Used
- **DVWA** (Damn Vulnerable Web Application)
- **XAMPP** / **WAMP** / **LAMPP** for hosting DVWA
- Web browser (Firefox / Chrome)

## Steps Performed
1. Set up DVWA on a local server using XAMPP.
2. Configured database and DVWA security settings to "Low."
3. Accessed the vulnerable login page.
4. Used SQL Injection payloads to bypass authentication.
5. Captured and documented the process with screenshots.
6. Explained the SQL Injection vulnerability and mitigation techniques.

## Example Payloads Used
- `' OR '1'='1' --`
- `' OR '1'='1' #`
- `admin' --`
- `admin' #`

## Files in This Folder
- **sql_injection_report.pdf ie. internship_task_3** – Detailed procedure, commands, payloads used, and explanations and screenshots.
- **screenshots/** – Folder containing attack demonstration screenshots.
- **demo-video-link.txt** – Google Drive link to the SQL Injection demo video.

## Summary of Findings
- Successfully bypassed login authentication using SQL Injection payloads.
- Identified lack of input validation as the cause of the vulnerability.
- Suggested mitigation:
  - Use prepared statements (parameterized queries).
  - Implement input validation & sanitization.
  - Restrict database privileges.
  - Use web application firewalls (WAF).

## Demo Video
📹 [Click here to watch the demonstration](https://drive.google.com/file/d/1BUm15RvoUHlJQ8FI5svdOlMlsLSmBPcK/view?usp=sharing)

