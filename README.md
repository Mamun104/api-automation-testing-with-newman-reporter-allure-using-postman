# API Automation Testing With Newman Reporter Allure Using Postman For macOS


## Technology and Tool Used
- Postman
- Node Js
- newman
- npm
- Visual Studio Code

## Prerequisites

- You must have installed node js to your system
- Postman
- NPM
- Newman

## Scenario of this project

- User Can't Login With Invalid Email
- User Can't Login With Invalid Password
- User Can't Login With Valid Email And Invalid Password
- User Can't Login With  Invalid Email And Valid Password
- User Can Login With Valid Credential
- Can't Create a User With Invalid Token
- Can't Create a User With Invalid SECRET-KEY
- Can't Create a User With Invalid Token And Valid  SECRET-KEY
- Can't Create a User With Invalid SECRET-KEY And Valid Token
- Create User With Valid Credential
- Can't get user list  With Invalid Token
- User can't search with wrong user id
- User can get user list with valid credential
- User can search user by user id
- Can't Update User With Invalid SECRET-KEY
- User can update a user with valid credential
- Can't Delete User  With Invalid Token
- Can't Delete User  With Invalid SECRET-KEY
- User can delete a user with valid credential
- Can't Create  Agent With Invalid Token
- Can't Create a Agent With Invalid SECRET-KEY
- Can't Create Agent With Invalid Token And Valid  SECRET-KEY
- Can't Create Agent With Invalid SECRET-KEY And Valid Token
- Create Agent With Valid Credential

## API Documents



      https://documenter.getpostman.com/view/16548351/2s9YeD8t6m


## ## How to run this project

- clone this project
- open this project in visual studio code

## npm install

            sudo npm install
- check the npm version

         npm -v
  
## Newman Install

      sudo npm install -g newman
  
- check the newman version

    newman -v

## Install Newman Reporter-Allure

        sudo npm install -g newman-reporter-allure

  - then hit the command in the terminal

## Usage

  To generate Allure results, specify allure in Newman's -r or --reporters option.

         $ newman run <Collection> -e <Environment> -r allure
         $ newman run <Collection> -e <Environment> -r allure --reporter-allure-export <allure-results-out-dir>
  Use the option --report-allure-collection-as-parent-suite to use the collection name as the parent suite title under the Suites view. This helps when you run multiple collections and want to aggregate them in a single report.

## Generating and Serving Allure report

Allure results will be generated under folder "allure-results" in the root location. Use allure-commandline to serve the report locally.

          $ allure serve

Generate the static report web-application folder using allure-commandline

           $ allure generate --clean
 ### Output: 

![Screenshot-1](https://github.com/Mamun104/api-automation-testing-with-newman-reporter-allure-using-postman/assets/78067017/9d14d439-c52c-4445-9a9a-ce896e915b80)

![image](https://github.com/Mamun104/api-automation-testing-with-newman-reporter-allure-using-postman/assets/78067017/ba9026de-5eff-4f74-adde-b61d8c21fd2a)



![Screenshot-2](https://github.com/Mamun104/api-automation-testing-with-newman-reporter-allure-using-postman/assets/78067017/1dc83ef2-841f-4d29-a492-a53f6b75af7b)


![Screenshot-3](https://github.com/Mamun104/api-automation-testing-with-newman-reporter-allure-using-postman/assets/78067017/50b9cffe-acf2-4289-8f66-7c86d2379a4b)

![Screenshot-4](https://github.com/Mamun104/api-automation-testing-with-newman-reporter-allure-using-postman/assets/78067017/06331206-a7e5-4f72-9454-e02b979eb856)
