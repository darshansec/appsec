# 1. Recon & Discovery
- [ ] Dirb Test / Forced Browsing
- [ ] File Discovery / Publicly Accessible Backup Files
- [ ] Default page disclosure
- [ ] Banner Disclosure (Server/Application)
- [ ] IIS Tilde Enumeration
- [ ] Jexboss

# 2. Information & Sensitive Data Exposure
- [ ] Sensitive Data Exposure (default phe file, error log, API)
- [ ] Sensitive Data in GET Method / Sensitive Data in Response / Sensitive Data in URL
- [ ] Information Exposure via Comments
- [ ] Information Exposure via Cookies
- [ ] Sensitive Information over Unencrypted Channel
- [ ] Password in Recoverable Format
- [ ] Sensitive data in Response

# 3. Authentication & Account Controls
- [ ] Weak Password Policy
- [ ] Weak Account Lockout Mechanism
- [ ] Weak Password Reset / Unverified Password Change
- [ ] Missing Logout Functionality
- [ ] Default Credentials
- [ ] Weak Security Question/Answer
- [ ] Username Enumeration
- [ ] Authentication Bypass
- [ ] OTP Bypass / OTP Spamming / Email Spamming
- [ ] Admin Session Concurrency

# 4. Session Management
- [ ] Session Fixation
- [ ] Concurrent Session
- [ ] Session Deletion
- [ ] Session Misconfiguration
- [ ] Session Timeout / Session Persistence
- [ ] Session Sidejacking
- [ ] Session Prediction: Sequencer
- [ ] Session Persistence (IIS/ViewState notes)

# 5. Access Control & Authorization
- [ ] Missing Functional Level Access Control
- [ ] Admin Session Concurrency (repeat)
- [ ] Privilege Escalation
- [ ] IDOR

# 6. Input Validation / Injection Classes
- [ ] Improper Input Validation
- [ ] Input Validation (generic)
- [ ] Injection Testcases (SQL/XPath/ORM/Command/etc)
- [ ] SQL Injection
- [ ] Command Injection
- [ ] Template Injection / Server Side Template / Client Side Template Injection
- [ ] XSS / HTML Injection / Hyperlink Injection / Content Spoofing
- [ ] CSV Injection / CSV Macro Code Injection
- [ ] XML Injection / XXE
- [ ] XPath Injection
- [ ] SSRF
- [ ] File Path Traversal / LFI / RFI
- [ ] Unvalidated Open Redirection
- [ ] XMLRPC / wp-json / wlwmanifest.xml
- [ ] Prototype Pollution
- [ ] Injection TestCases (general)

# 7. File Uploads & File Handling
- [ ] Unrestricted File Upload
- [ ] Malicious File Upload
- [ ] Dangerous HTTP Methods (PUT/DELETE)
- [ ] TRACE
- [ ] Host Header Attack
- [ ] Carriage Return Line Feed (CRLF)

# 8. Transport Layer, TLS, CORS & Security Headers
- [ ] HSTS Flag
- [ ] Secure Flag / HttpOnly
- [ ] Clickjacking / X-Frame-Options
- [ ] Content Security Policy (CSP)
- [ ] CORS
- [ ] Insecure Transport (Mixed Content)
- [ ] Weak TLS / SSL Ciphers
- [ ] BCW

# 9. Headers, Response & Error Handling
- [ ] Improper Error Handling
- [ ] Error Handling (in 404 internal path disclosure)
- [ ] HTTP Response Header Injection
- [ ] Server Banner / Application Banner
- [ ] Content Type Interchange

# 10. Logging, Monitoring & Known Vulnerabilities
- [ ] Log4j
- [ ] Error Log exposure
- [ ] HTTP Request Smuggling
- [ ] Buffer Overflow
- [ ] RCE / Remote Code Execution

# 11. Web / CMS / Platform Specific
- [ ] Forced Browsing (/wp-json/, xmlrpc.php, wlwmanifest.xml)
- [ ] Default page / default page disclosure
- [ ] Publicly Accessible Admin Interface
- [ ] Vulnerable jQuery / Vulnerable JQ

# 12. Business Logic & Application-Specific
- [ ] Business Logic — negative and decimal values
- [ ] Card number enumeration
- [ ] Email/OTP spamming (functional abuse)

# 13. Miscellaneous / Follow-ups
- [ ] Host header attack
- [ ] SSRF
- [ ] HTTP Request Smuggling
- [ ] CRLF, Prototype Pollution, XXE, Jexboss, Log4j
- [ ] Auto Complete disabled / Weak Password Reset Functionality etc
- [ ] Notes like `-na`
