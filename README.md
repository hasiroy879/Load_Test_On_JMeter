# Demo for Load Testing
## Description: By this project named Booking, I can perform load testing on a booking website. Link of the base url is :
Server: https://restful-booker.herokuapp.com

## Technology I used:
- JMeter
- Report: html-extra

## How to run?
- Clone the project
- Open the project in powershell
- Hit the following command:
- ```jmeter -n -t .\Booking.jmx -l .\Booking.jtl -e -o Reports```
- Report will be generated in Report folder

  ## Test Step
  ![image alt](https://github.com/hasiroy879/Load_Test_On_JMeter/blob/main/LoadTest.PNG?raw=true)

  ## Test Report
  ![image alt](https://github.com/hasiroy879/Load_Test_On_JMeter/blob/main/Capture.PNG?raw=true)

  Finally our load test is successfully executed.
