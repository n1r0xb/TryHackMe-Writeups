# <div align="center">[`Elastic Stack: The Basics`](https://tryhackme.com/room/investigatingwithelk101)</div>
<div align="center">
 <img src="https://github.com/user-attachments/assets/d37c79b5-ecc4-40dc-a36c-645ca3866dc2" height="250"></img>
</div>

---
|Terminology|Definition|
|:---------:|----------|
|`API`           |API, which stands for Application Programming Interface, is a set of rules and protocols for building software and applications. An API allows different software programs to communicate with each other. It defines methods of communication between various components, including the kinds of requests that can be made, how they're made, the data formats that should be used, and conventions to follow.|
|`Elasticsearch` |Elasticsearch is a distributed, scalable, and highly available search engine. It is used to store and index data so that it can be quickly searched and analysed.|
|`ELK`           |ELK stands for Elasticsearch, Logstash, and Kibana. These are three open-source tools that are commonly used together to collect, store, analyse, and visualise data.|
|`JSON`          |JavaScript Object Notation is an open standard file and data interchange format that uses human-readable text to store and transmit data objects consisting of attribute–value pairs and arrays.|
|`Kibana`        |Kibana is a web-based visualisation tool for exploring data stored in Elasticsearch. It can be used to create interactive dashboards and charts that help users to understand data.|
|`Logstash`      |Logstash is a tool for collecting and processing data from a variety of sources. It can be used to collect logs from applications, servers, and other systems. It can also be used to parse and transform data before it is stored in Elasticsearch.|
|`SIEM`          |Security Information and Event Management system that is used to aggregate security information in the form of logs, alerts, artifacts and events into a centralized platform that would allow security analysts to perform near real-time analysis during security monitoring.|
|`SOC`           |Security Operations Center (SOC) is a team of IT security professionals tasked with monitoring, preventing , detecting , investigating, and responding to threats within a company’s network and systems.|
|`VPN`           |A Virtual Private Network is a way to create a secure "tunnel" between two networks. For example, you use a VPN on TryHackMe to access the private network on which the machines operate. VPNs are also commonly used for an employee to log into their workplace when they are not on site (such as working from home or travelling for business matters). VPNs are also used where networks (such as coffee shops) do not provide encryption, and are a great way of preventing others from reading your network traffic.|
---
## `Elastic Stack Overview`

**Elastic Stack** is a collection of different open-source components that work together to collect data from any source, store and search it, and visualize it in real time. 

**Core Components:**
* **Elasticsearch**  is a full-text search and analytics engine for JSON-formatted documents.
* **Logstash** is a data processing engine that takes data from different sources, filters it, or normalizes it, and then sends it to the destination. A Logstash configuration file is divided into three parts, as shown below:

  <img width="151" height="234" alt="Elastic-Stack-Overview(EStB)-THM" src="https://github.com/user-attachments/assets/e8fd0fd5-c51f-497e-bea8-f0d5316d933f"></img>

* **Beats** are host-based agents known as data-shippers that ship/transfer data from the endpoints to Elasticsearch.

  <img width="685" height="293" alt="Elastic-Stack-Overview-2(EStB)-THM" src="https://github.com/user-attachments/assets/a08722cb-a7b2-4d86-912c-2f2e0584a221" />

* **Kibana** is a web-based data visualization tool that works with Elasticsearch to analyze, investigate, and visualize data streams in real time.

---

<b>*Q1: Logstash is used to visualize the data. (yay / nay)*</b>

<details>
  <summary><i>Click to reveal the answer</i></summary>
  <code>Nay</code>
</details>

<b>*Q2: Elasticstash supports all data formats apart from JSON. (yay / nay)*</b>

<details>
  <summary><i>Click to reveal the answer</i></summary>
  <code>Nay</code>
</details>

---
## `Discover Tab`

