API Performance Test

**Overview**

This README provides instructions for executing the JMeter performance test for the following APIs:

- Create User

- List Users

- Update User

The goal is to evaluate the performance of these APIs under high concurrency conditions.

**Test Details**

- Concurrent Users: 100

- Test Duration: 15 minutes

- Ramp-Up Period: 60 seconds

APIs Tested: Create User (POST), List Users (GET), Update User (PUT)

**Prerequisites**

1- Apache JMeter (version 5.4.1 or later)

2- Java Development Kit (JDK) installed

3- Internet access to the target API server

**Setup Instructions**

1- Download the Test Script:

2- Obtain the jmeter_api_test.jmx file.

3- Open the Script in JMeter:

4- Launch JMeter.

5- Go to File > Open and select the jmeter_api_test.jmx file.

6- Configure Test Parameters (Optional):

7- Adjust the target domain, API endpoints, and request payloads if needed.

8- Modify the concurrent users or test duration number in the Thread Group settings.

9- Running the Test

10- To execute the test, click the Start button (green play icon).

11- Monitor real-time performance metrics using listeners like View Results Tree, Summary Report, or Graph Results.

**Results and Analysis After the test**

- Review key metrics:

- Average Response Time

- Throughput (requests/min)

- Error Rate

- Compare with the API Performance Report for expected benchmarks.

- Export results as CSV for detailed analysis if required.

**Troubleshooting**

1- High Error Rate: Verify API availability and adjust concurrency settings.

2- Connection Issues: Ensure correct API endpoint configuration and network stability.

3- Resource Exhaustion: Monitor server logs for CPU, memory, or database bottlenecks
