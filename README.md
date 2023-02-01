# Dmoney-API-jmx

## Technology and Tools Used
- Java
- Apache JMeter

## Requests
- Login to user
- Create a new agent
- Create a customer
- Search the newly created user by phone number
- Deposit balance to the customer from agent
- Customer withdraw some money from agent
- Delete the user

## How to run this project
- Clone this project.
- Copy the Dmoney-API.jmx file in the bin folder of Apache JMeter installation location.
- Open the Dmoney-API.jmx file with JMeter and run the project-
- To Generate report on the command prompt, delete the "dmoney-api.csv" file and "Reports" folder from the project-
  - Hit the following command:
    - jmeter -n -t Dmoney-API.jmx -l dmoney-api.csv -e -o Reports

## Prerequisite
- Java needed to be installed.
- Apache JMeter needed to be installed.

## HTML Report
![APDEX](https://user-images.githubusercontent.com/52536969/216117948-ebf78e84-0079-4119-a483-3793969a6888.png)

![Statistics](https://user-images.githubusercontent.com/52536969/216118010-12914966-bd51-47ac-9f39-1a51778ab187.png)
