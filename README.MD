# IOT
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/1-IoT-Ecosystem_CompTIA-2.jpg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/4_stage_iot_solutions_architecture_0.jpeg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/Industrial_IoT_Infographic.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/IoT-Ecosystem-16.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/Screen-Shot-2017-03-05-at-8.03.59-PM.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/beecham_research.jpg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/br-internet-of-things-ecosystem.jpg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/communication_technologies.jpeg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/internet-of-things-comparison-chart.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/iot-protocols.jpg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/iot-solution-en.jpg)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/osmosis-iot.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/screen-shot-2014-02-04-at-10-51-33-am.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/snap-2014-04-06-at-21-19-31.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/snap-2014-04-06-at-21-19-31.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/tableforrowearticle.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/xMQTT-speed-table.png.pagespeed.ic.YNHl6LFo48.png)
ref
![alt text](https://github.com/Aslamlatheef/IOT/blob/master/Images/yole-2-1.jpg)

-----------------------------------------------------------------------------------------------------------------------
this is repository that i maintianing for keep my work for public access and also i can also refer when ever i need
-----------------------------------------------------------------------------------------------------------------------
# HTTP VS MQTT
HTTP is the most popular and widely used protocol. But over the last years MQTT rapidly gain tractions. Developers have to choose between them when we are talking about IoT development.

# Design and Messaging

MQTT is data centric whereas HTTP is document-centric. HTTP is request-response protocol for client-server computing and not always optimized for mobile devices. Main solid benefits of MQTT in these terms are lightweightness (MQTT transfers data as a byte array) and publish/subscribe model, which makes it perfect for resource-constrained devices and help to save battery.
Besides, publish/subscribe model provides clients with independent existence from one another and enhance the reliability of the whole system. When one client is out of order the whole system can keep on working properly.

# Speed and Delivery
According to measurements in 3G networks, throughput of MQTT is 93 times faster than HTTP’s.
Besides, in comparison to HTTP, MQTT Protocol ensures high delivery guarantees. There are 3 levels of Quality of Services:
- at most once: guarantees a best effort delivery.
- at least once: guaranteed that a message will be delivered at least once. But the message can also be delivered more than once.
- exactly once: guarantees that each message is received only once by the counterpart
MQTT also provides users with options of Last will & Testament and Retained messages. The first means that in case of unexpected disconnection of a client all subscribed clients will get a message from a broker. Retained message means that a newly subscribed client will get an immediate status update.

# HTTP Protocol has none of these abilities.

# Complexity and Message Size
 
MQTT has pretty short specification. There are only CONNECT, PUBLISH, SUBSCRIBE, UNSUBSCRIBE and DISCONNECT types that are significant for developers. Whereas HTTP specifications are much longer.
MQTT has a very short message header and the smallest packet message size of 2 bytes. Using text message format by HTTP protocol allows it to compose lengthy headers and messages. It helps to eliminate troubles because it can be read by humans, but at the same time it’s needless for resource-constrained devices.

# Conclusion

MQTT Protocol is easy of use. It is essential when response time, throughput, lower battery and bandwidth usage are on the first place for future solutions. It’s also perfect in case of intermittent connectivity.
HTTP is worthy and extendable. But MQTT is more suitable when it is referred to IoT development.

