
# Contents

- [Introduction](#Introduction)
- [Prerequisites](#Prerequisites)
- [Install](#Install)
- [Signup_API](#Signup_API)
- [Signin_API](#Signin_API)
- [TestAPI_Report](#TestAPI_Report)

# Introduction

This document provides a summary of the API Testing Project, which was created using some test cases for a website's Sign-up and Sign-in page.

# Prerequisites

- A Desktop/Laptop
- Internet Connection
- A Browser (Google Chrome)
- A Website (Builder Studio)

# Install

- [Postman software](https://www.postman.com/)
- [Node.js](https://nodejs.org/en/) (LTS version)
- Newman npm
```bash
  npm install -g newman
```

# Signup_API

- Here is the API URL of the Builder Studio website as a Collection Variable.

![API_url](https://user-images.githubusercontent.com/26795314/200159181-267a0b0e-1d1a-4531-bc8b-ab0237f988bd.png)

- This is the Body section of Signup API.

![Signup_API](https://user-images.githubusercontent.com/26795314/200159193-f751dfcd-42df-485b-8db6-74e859bee600.png)

- This is the Pre-request Script of Signup API.

![Signup_API-2](https://user-images.githubusercontent.com/26795314/200159200-d8567863-420c-49ed-8d04-5d60f8dedbf3.png)

- This is the Test Cases for Signup.

![TestCase_Signup](https://user-images.githubusercontent.com/26795314/200159224-ba4cf24b-51f4-467c-b8df-336ffe2f34cb.png)

# Signin_API

- Here is the API URL of the Builder Studio website as a Collection Variable.

![API_url](https://user-images.githubusercontent.com/26795314/200159234-7779f3be-c4a3-439c-8c96-c103ab7909f1.png)

- This is the Body section of Signin API.

![Signin_API](https://user-images.githubusercontent.com/26795314/200159242-7e3adc69-9fee-4bd2-b113-0f1ccac03e17.png)

- This is the Test Cases for Signin.

![TestCase_Signin](https://user-images.githubusercontent.com/26795314/200159257-95cf30b9-2b9a-44e9-bf84-08060e1b5d3f.png)

- This is the Environment section for both Signup and Signin.

![Environment](https://user-images.githubusercontent.com/26795314/200159260-873a652b-d59a-4270-9baa-4bd6195dc48c.png)

# TestAPI_Report

- This is an Htmlextra report produced by the Newman npm.

![TestAPI_Report_Htmlextra](https://user-images.githubusercontent.com/26795314/200159362-b92022d0-3012-44c8-86a1-c41521b8f615.png)

- This is an Html report produced by the Newman npm.

![TestAPI_Report_Html](https://user-images.githubusercontent.com/26795314/200159367-4bf12518-5335-4555-8fd1-9c232ad82f22.png)
