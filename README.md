# Project-Phase-6-Security-Recommendations
Project Phase 6: Security Recommendations
School schedule app
Student Name: Ki Fung Yune 000904318
a. What is your security recommendation? Why did you choose it?
i. Some recommendations may not apply to the project (i.e.: biometric authentication, password policies, etc.)
Implement robust data encryption protocols to protect sensitive information retrieved from the campus app. Additionally, enforce a secure password policy coupled with two-factor authentication, utilizing one-time passwords sent to the student's email for added security. These measures ensure that student data remains confidential and protected from unauthorized access, enhancing overall app security and user trust.
b. Who does the recommendation benefit (end-user, developer, etc.)?
This recommendation benefits both end-users and developers. End-users(students) benefit from increased security and privacy protection for their personal data. Developers benefit by building trust with users, reducing the risk of data breaches, and complying with data protection regulations.
c. If the recommendation was found somewhere other than the provided checklist, include a link to it.
The security recommendation for implementing two-factor authentication (2FA) aligns with industry best practices for enhancing user authentication security. Specifically, the recommendation advocates for the use of 2FA to add an additional layer of verification beyond just a password, thereby reducing the risk of unauthorized access to user accounts. 
Reference:https://duo.com/product/multi-factor-authentication-mfa/two-factor-authentication-2fa
d. When would the recommendation have to be implemented (based on how serious the security risk is)?
The recommendation should be implemented as early as possible in the development lifecycle to minimize security risks. However, it may require ongoing maintenance and updates to adapt to evolving threats and security standards.

e. Why do you think your project needs your recommendation?
The mobile app project involves handling sensitive student data, such as login credentials, personal information(email, phone, address). Implementing secure data storage and transmission protocols helps mitigate the risk of data breaches, identity theft, and unauthorized access to confidential information.
f. How do you think your recommendation could be applied?
Implementing two-factor authentication (2FA) in the school schedule app could be achieved by integrating a service that generates and sends one-time passwords (OTPs) to users' registered email addresses or mobile phone numbers. This process would involve the following steps:
User Registration: register their email addresses or phone numbers with the app 
Login Process: When log in, user would also be prompted to enter the OTP sent to their registered email or phone number.
OTP Generation and Delivery: The app would utilize a third-party service or library to generate unique OTPs and send them securely to users via email or SMS.
Authentication: Upon receiving the OTP, users would enter it into the app to complete the authentication process.
Access Granted: If the OTP entered by the user matches the one generated by the system, access to the app's features and functionalities would be granted.
i. How feasible would the implementation be?
Implementing two-factor authentication (2FA) with one-time passwords (OTPs) in the school schedule app is highly feasible. Several factors contribute to the feasibility of this implementation:
Availability of Third-Party Services: Numerous third-party services and libraries are available that specialize in generating and delivering OTPs via email or SMS. These services offer easy-to-use APIs and SDKs, simplifying integration with the app.
Cost-Effectiveness: Implementing OTP-based 2FA does not incur significant costs. Many third-party services offer free or affordable pricing plans for sending OTPs, especially for moderate usage levels.
