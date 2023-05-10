# Secure-Code-Commandments
This is a list of commandments that you should follow when writing secure code, regardless of the programming language you use. These commandments are based on industry best practices and recommendations from the Open Web Application Security Project (OWASP), a leading organization in web application security.

## Why Secure Code Matters

Writing secure code is essential to protect your application and its users from various types of attacks, such as injection, cross-site scripting (XSS), cross-site request forgery (CSRF), broken authentication and session management, insecure direct object references, security misconfigurations, and others. A secure codebase reduces the risk of vulnerabilities and data breaches, which can have severe consequences for your organization and its reputation.

## The Commandments

1. **Input Validation:** Validate all user input data to prevent malicious data injection. Use OWASP advice and perform code review to ensure input validation is implemented correctly. This is easy due to the fact that alot of well known frameworks such as Django, React, express etc have this built in already.

2. **Output Encoding:** Implement output encoding to prevent XSS attacks. Perform code review to ensure output encoding is implemented correctly.

3. **Parameterized Queries:** Use parameterized queries instead of dynamic queries to prevent SQL injection attacks. Perform code review to ensure parameterized queries are implemented correctly.

4. **Authentication and Authorization:** Use the authentication and authorization features provided by your framework and avoid writing your own. Follow OWASP advice on password management.

5. **Session Management:** Use identity and session management features available in your framework, network, or cloud provider to secure user sessions.

6. **Security Headers:** Implement all applicable security headers to prevent security vulnerabilities.

7. **Caching Sensitive Data:** Avoid caching sensitive page data. Perform code review to ensure caching is not used inappropriately.

8. **Secure Cookies:** Follow best practices to secure your cookies.

9. **File Uploads:** Take every possible precaution when performing file uploads. Follow OWASP advice and scan uploaded files.

10. **Error Handling:** Catch, handle, log, and alert upon all errors appropriately. Follow OWASP guidance on login, alerting, and monitoring.

11. **URL Parameters:** Do not store sensitive or decision-making information in URL parameters.

12. **HTTPS Everywhere:** Serve your application over HTTPS only. Follow code review to ensure HTTPS is implemented correctly.

13. **Data Encryption:** Encrypt all data in transit and at rest.

14. **Password Managers:** Allow users to cut and paste into the password field to use password managers.

15. **Secret Management:** Keep all connection strings, hashes, passwords, and other secrets in a secret store. Follow secret management best practices.

16. **Password Hashing:** Hash and salt all passwords.

17. **Keep Your System Up to Date:** Regularly update all components to keep your system secure. Follow API security best practices.

## How to Use the Commandments

You can use these commandments as a checklist when reviewing your codebase for security vulnerabilities. You can also use them as a guideline when writing new code, to ensure that you follow secure coding practices from the start.

These commandments are language agnostic, which means that you can apply them to any programming language or platform. However, the implementation details may vary depending on the technology stack you use. Therefore, you should always consult the documentation and best practices for your specific programming language and platform, in addition to following these commandments.

## Conclusion

Writing secure code is a continuous process that requires diligence, discipline, and attention to detail. By following these commandments, you can improve the security of your codebase and reduce the risk of vulnerabilities and data breaches. Remember to always keep your system up to date and follow the latest security best practices.
