## Router

A physical or virtual appliance that passes information between two or more packet-switched computer networks. The networks can be LAN, WAN or a combinationod the two.
A router inspects a given data packet's destination internet protocol (IP) address, calculates the best way to reach its destination and then forwards it accordingly.

## Switch

## Firewalls

A firewall is a network security device eithe hardware or software-based which monitors all the incoming and outgoing traffic and based on a defined set of security rukes it accepts, rejects or drops that specific traffic.
It acts as security guard that helps keeps your digital world safe from unwanted visitors and potential threats.

## IDS & IPS

### Intrusion Detection System/ Intrusion Prevention System

IDS: is a hardware or software tool that monitors an analyze network or system activities for signs of unauthorized access or prolicy violations.
It passdively scans incomming traffic and compares it to pre-configured signatures or behavioral patterns.
IDS alerts the system administrator when potential threats are detected but does not take any activge action to block or mitigate them.

IPS: is an advanced security secuirty system that not only detects malicious activities but also prevents them from happening in real-time.
It intercepts the network traffic, compares it to known threat signatures, and immediately blocks or neutralizes suspicious activites before they can cause damage.

IPS is proactive, while IDS is primarily reaction

## Balancing the load

A load balancer is a crucial component in system design that distributes incoming network traffic across multiple server. Its main purpose is to ensure that no single server is overburdened with too mant requests, which helps improves the performance, reliability and availabilty of applications.

## Proxy server

Modern proxy servers do much more than forwarding web requests, all in the name of data security and network performance. Proxy servers act as a firewall and web filter, provide shared network connections, and cache data to speed up common requests. A good proxy server keeps users and the internal network protected from the bad stuff that lives out in the wild internet. Lastly, proxy servers can provide a high level of privacy.

### How Does a Proxy Server Operate?

Every computer on the internet needs to have a unique Internet Protocol (IP) Address. Think of this IP address as your computer’s street address. Just as the post office knows to deliver your mail to your street address, the internet knows how to send the correct data to the correct computer by the IP address.

A proxy server is basically a computer on the internet with its own IP address that your computer knows. When you send a web request, your request goes to the proxy server first. The proxy server then makes your web request on your behalf, collects the response from the web server, and forwards you the web page data so you can see the page in your browser.

When the proxy server forwards your web requests, it can make changes to the data you send and still get you the information that you expect to see. A proxy server can change your IP address, so the web server doesn’t know exactly where you are in the world. It can encrypt your data, so your data is unreadable in transit. And lastly, a proxy server can block access to certain web pages, based on IP address.

## NAS vs. SAN

### Network Attached Storage (NAS)

A single, self contained storage device that connects to a LAN using standard network protocols like Ethernet.
Ideal for file sharing, collaborative work storage, and general-purpose needs.

### Storage Area Network (SAN)

A dedicated, high-speed network connecting servers and storage devices, often using specialized protocols and cabling.
Ideal for database servers, virtualized environments and other applications requiring high-speed data access.

## Access point (AP)

Allows you to connect wirelessly to a network, such as the internet or a local area neytwork. It acts as a central hub for wireless communication and enables devices like smartphones, tablets and laptops to access to network without the need for wired connections.
Wireless network everywhere

## Wireless LAN controller

WLC is a network device used to monitor and manage wireless access points in an origanization. WLCs are connecter to router and allow devices from accross the origanization to connect to the router via access points.
