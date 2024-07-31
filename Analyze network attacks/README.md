## Portfolio Activity: Analyze network attacks

### Activity Overview

I read the following scenario and access the [support materials](https://github.com/kevin-tran-tech/Google-Cybersecurity/blob/main/Analyze%20network%20attacks/How%20to%20read%20a%20Wireshark%20TCP_HTTP%20log.pdf) to complete the [cybersecurity incident report](https://github.com/kevin-tran-tech/Google-Cybersecurity/blob/main/Analyze%20network%20attacks/Cybersecurity%20incident%20report.pdf). 

By completing this activity, I was able to enchance my understanding of network security by identifying a type of network attack I have discovered and describe how it was affecting the web server and employees.

### Scenario

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.
