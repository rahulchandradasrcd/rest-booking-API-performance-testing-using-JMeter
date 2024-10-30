# Rest-Booking-API-Performance-Testing-Using-JMeter
This project demonstrates Performance Testing using JMeter, providing a collection of tests to validate various endpoints of the API.

## Features
* Tests for GET, POST, PUT, DELETE requests
* Collection of tests covering different API endpoints

## Technology used:
- JMeter

## Overview
This repository contains a JMeter project for performance testing of the [Restful-Booker](https://restful-booker.herokuapp.com/apidoc/index.html) Website.

## Usage
1. Clone the repository to your Local Machine From:
````
https://github.com/rahulchandradasrcd/rest-booking-api-performance-testing-using-jmeter.git
````
2. Open JMeter and load the test plan.
3. Configure the necessary settings and parameters in the test plan.
4. Run all Test plan.

## Run in CMD (Non GUI mode) on your project folder
To run the test plan through CMD (Non GUI mode), use the following command:
````
jmeter -n -t Test_100.jmx -l report\Test_100.jmx.jtl
````
This command runs JMeter in non-GUI mode (-n), specifies the test plan file (-t), and writes the results to a JTL file (-l).

## Testing
The sample test plan includes the following components:
### 1. Thread Group:
  * Thread Count: 100
