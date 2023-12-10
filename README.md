# API Testing with PostMan (Dmoney)
This is a simple API testing project where I test an API (DMoney), primarily a fintech API. 
Users can perform all their financial transactions using it, similar to mobile banking apps (Nagad/Bkash, etc.).

I have conducted all the tests manually and created test cases covering all the features of this API. As a result, I established assertion points for API automation. Additionally, I have chained multiple APIs using Postman and generated reports using Newman.

## Prerequisite
 - NodeJS
 
## Tools Used
 - Postman
 - Newman

## How to run this project:
  - Clone this project
  ``` https://github.com/iamnadim/dmoney-api-newman-b9 ```
  - In the source root project, give the Following command:
    ``` npm i ```
  - Give the Following command to run:
    ``` npm start ```

## Postman documentation: 
https://documenter.getpostman.com/view/31247777/2s9YeK5AQR
## Drive link for screenshot: 
https://drive.google.com/drive/folders/1-cPl2lgZC4xq0_poLpS_yHEcR-A2Elrv?usp=drive_link

### ScreenShot of Newman Report

![Report-Newman 1](https://github.com/iamnadim/dmoney-api-newman-b9/assets/47740217/4d1071d5-0e7d-4a27-aa5d-6cba05351433)

![Report-Newman 2](https://github.com/iamnadim/dmoney-api-newman-b9/assets/47740217/daf35d19-4171-4ad6-a290-2b74bbde4f46)
![Report-Newman 3](https://github.com/iamnadim/dmoney-api-newman-b9/assets/47740217/14c64239-79de-4510-979c-281f9cd59d01)

## Test Case:
https://docs.google.com/spreadsheets/d/115Rjy7SunTg8Yq1NLsi9MHd4Tk87WAIEP1BR4xaW4Fc/edit?usp=sharing

## Bug And Improvement Report:
https://docs.google.com/spreadsheets/d/1deG4Xh_5q-VU9Ssg_Thv1jhim3ZJLTiKbvhrB8k31KE/edit?usp=sharing

## Test case are Created for the Following Scenario

1. Admin creates an agent random 2 customers
2. Admin creates random 2 customers
3. Deposit some money from the SYSTEM account to the agent
4. Agent deposit to any of 1 customer
5. The customer checks the balance
6. Customer withdraws any amount from the agent
7. Customer sends money to the other customer
8. Then the customer will check the statement
9. For each transaction, assert the expected balance
