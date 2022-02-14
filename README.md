# TPE2-Application-Development

### ThingsPro Edge Application v.s. tpFunc Function
There are two ways for customers to develop, run your own application on ThingsPro Edge device. Both ways allow your application to integrate and leverage ThingsPro Edge's capabilities and features by Restful API and SDK.

The application could be edge computing program (to calculate, manipulate, analysis data on edge), data acquisition (to fetch data by proprietary protocols), scheduling task (to arrange routine operation tasks), or data publish program (to transfer data to specific IT system).

Below table gives you ideas how to select suitable application development way to fit your requirements.

|                        | ThingsPro Edge Application                                   | tpFunc Function                                       |
| ---------------------- | ------------------------------------------------------------ | ----------------------------------------------------- |
| Framework              | Docker container managed by ThingsPro Edge                   | Python program managed by tpFunc                      |
| Language               | All programing language                                      | Python 3                                              |
| TagHub SDK             | Python and Go Lang SDK                                       | Python SDK                                            |
| Access TPE API         | OK                                                           | OK                                                    |
| LAN Access             | OK (by Docker Container)                                     | OK (by tpFunc)                                        |
| WAN Access             | OK (by Docker Container)                                     | OK (by tpFunc)                                        |
| Storage Access         | OK (by Docker Container)                                     | X                                                     |
| Serial Port Access     | OK (by Docker Container)                                     | X                                                     |
| BLE Access             | OK (by Docker Container)                                     | X                                                     |
| Expose Restful API     | OK (by Docker Container)                                     | OK (by tpFunc)                                        |
| Expose Web GUI         | OK (by Docker Container)                                     | X                                                     |
| Knowledge Require      | Docker container<br />Application design<br />Linux Driver & Utility<br />ThingsPro Edge Application build and deployment | Python coding<br />tpFunc deployment                  |
| Program Design Pattern | By your own                                                  | - Time Driven<br />- Data Driven<br />- Web API Style |




## ThingsPro Edge Application

1. <a href="documents/What%20is%20ThingsPro%20Edge%20Appliation.md">What is ThingsPro Edge Application</a>
2. <a href="documents/Build%20and%20Run%20Hello%20World%20Application.md">Build and Run "Hello World" Application</a>
3. <a href="documents/Invoke%20ThingsPro%20Edge%20API%20on%20Hello%20World%20Application.md">Invoke ThingsPro Edge API on "Hello World" Application</a>
4. <a href="documents/Use%20TagHub%20SDK%20on%20Hello%20World%20Application%201.md">Use TagHub SDK on Hello World Application 1</a> (publish tag)
5. <a href="documents/Use%20TagHub%20SDK%20on%20Hello%20World%20Application%202.md">Use TagHub SDK on Hello World Application 2</a> (subscribe tag)
6. <a href="documents/Azure%20IoT%20Central.md">(Example) Azure IoT Central Demo Application</a>
7. (Example) OPC UA Client Application

## tpFunc Function
1. What is tpFunc and tpFunc funciton
2. <a href="documents/Scheduled%20Operation%20Task%201.md">(Example) Scheduled Operation Task 1</a> (by confg)
3. <a href="documents/Scheduled%20Operation%20Task%202.md">(Example) Scheduled Operation Task 2</a> (by code)
4. <a href="documents/Enable%20onChange%20Feature%20on%20TagHub.md">(Example) Enable onChange Feature on TagHub</a> 
