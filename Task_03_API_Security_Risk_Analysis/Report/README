# Task 03 – API Security Risk Analysis

## Overview
This task focuses on performing a basic API Security Risk Analysis on a public demo API.
The goal is to understand common API security issues such as missing authentication,
data exposure, and lack of access control.

Only read-only and ethical testing was performed.

---

## API Tested
- API Name: JSONPlaceholder
- Base URL: https://jsonplaceholder.typicode.com
- Endpoint Tested:
  GET /users

---

## Tools Used
- Postman – API testing and inspection
- Web Browser – API documentation review

---

## Methodology
1. Reviewed the official API documentation
2. Selected a public demo endpoint
3. Sent GET requests using Postman
4. Checked authentication, headers, and response data
5. Identified security risks
6. Collected screenshots as evidence

---

## Identified Security Risks

1. Missing Authentication  
   - Severity: Medium  
   - Anyone can access the API without login  
   - Recommendation: Implement API authentication (API keys or tokens)

2. Excessive Data Exposure  
   - Severity: Medium  
   - User data like email and address are exposed  
   - Recommendation: Return only required fields

3. Lack of Authorization  
   - Severity: Medium  
   - All user data is accessible without restrictions  
   - Recommendation: Apply proper access control

4. Missing Rate Limiting  
   - Severity: Low  
   - API can be abused with unlimited requests  
   - Recommendation: Add rate limiting

---

## Evidence
Screenshots from Postman testing are included in the Evidence folder.
These show:
- API request and response
- HTTP status code (200 OK)
- Authorization set to No Auth
- Response headers
---

## Scope and Ethics
- Only public demo APIs were tested
- No private or production systems were targeted
- No exploitation or attacks were performed

---

## Conclusion
This task helped in understanding basic API security concepts and how unsecured APIs
can expose sensitive data. The analysis was performed ethically using a public test API.

