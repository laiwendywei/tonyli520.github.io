---
layout: post
title: Capstone Module 4
---

### Exception Handling

The types of exceptions identifiable in the automation process can be classified according to the table below.

Error Type:
* Known: Previously encountered situation. A possible scenario is defined, and clear actions and workarounds are provided for each case.
* A situation never encountered before. It can be caused by external factors.

Based on the above criteria, the table below should reflect all the known exceptions identified throughout the process and map the expected action the robot needs to take in each case. Insert as many rows as required in the table, to capture all exceptions in a comprehensive list.

### Possible errors
1.
* Exception Name: Incorrect email or password 
* Parameters: If message for incorrect username or password exist
* Actions: Send email to exceptions@acmetest.com “Hello, The username or the email is incorrect. Please check and restart Thank you’’

2.
* Exception Name: No task of type WI5 exists 
* Actions: Stop Process

For any other unanticipated or unknown exceptions, the robot should send an email notification at exceptions@acme-test.com with the original email and error message screenshot attached.
