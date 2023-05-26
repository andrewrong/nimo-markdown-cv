---
layout: cv
title: MengYe Shen
email:
  url: mailto:shenmengye@gmail.com
  text: shenmengye@gmail.com
homepage:
  url: http://nomoshen.com
  text: nomoshen.com

---

# MengYe **Shen**

<!--
include contact information from the front matter
Supported arguments:

    - homepage: url, text
        - phone
        - email
            -->

{% include cv-contact.html %}

## Skills

* Experienced in developing and maintaining distributed systems, proficient in C++/Golang programming.
* In-depth understanding of the main modules of MongoDB and the source code of the time series data engine.
* Years of experience in low-level development.

## Work Experience

### **Shanghai Qiniu Cloud Technology Co., Ltd.** `August 2020 - Present`

_**Cloud Storage Technology Expert**_<br>

#### 1. Performance and Stability Optimization of MongoDB

**Background:** MongoDB is a crucial database in the company, but it encounters performance and stability issues in specific business scenarios and large-scale clusters.

**Key improvements:**

- Optimized the routing module of MongoDB to solve jitter issues in large-scale clusters.
- Introduced a health check mechanism in the core to compensate for the shortcomings of MongoDB's heartbeat mechanism, improving the stability of MongoDB clusters.
- Implemented rate limiting in mongos to ensure the stability of MongoDB and provide timely feedback to the business layer.
- Added a routing filtering module to MongoDB Secondary to reduce latency of business requests.
- Developed a parallel migration tool based on the MongoDB movechunk command to enhance cluster expansion efficiency.

<br>

#### 2. Stability Optimization of Object Storage Metadata

**Background:** There were stability issues with the metadata module in the object storage, especially the lack of tolerance from the business layer towards underlying database failures and network jitter.

**Key improvements:**

- Addressed the comprehensive impact of underlying MongoDB cluster failures on business requests.
- Significantly reduced the unexpected request errors caused by minor network jitter, improving the business's resilience to network fluctuations.
- Introduced a low-level network health check module to automatically switch to alternative networks for fault recovery.

<br>

#### 3. Restructuring of Object Storage Metadata Lifecycle

**Background:** There are some issues with the lifecycle of object storage metadata, such as the inability to apply rule changes to historical data, difficulties in deleting certain data, and high storage costs.

**Key improvements:**

- Developed and validated project plans to optimize the metadata lifecycle.
-  Implement timely deletion within the specified timeframe, ensuring that historical data takes effect promptly.
- Optimized resource utilization by utilizing computational resources without occupying additional storage resources.

<br>

### **Alibaba** `September 2019 - August 2020`

_**Technical Expert (P7)**_<br>

#### Miniaturization Solution for Private Cloud Monitoring System

**Background:** The goal was to integrate multiple monitoring products in the basic infrastructure of the output environment into a single, efficient, and feature-rich monitoring system.

- Developed and implemented a complete miniaturization solution.
- Mainly responsible for developing functions such as synchronization and aggregation of collection configuration information, synchronization of k8s clusters and basic infrastructure metadata, and receiving monitoring data.

<br>

### **Hangzhou Shi Qu Information Technology Co., Ltd. (Mogujie)** `April 2014 - August 2019`

_*****Senior Development Engineer*****_<br>

#### 1. Building a Distributed Monitoring System and Self-developed Time Series Data Engine from 0 to 1

**Main responsibilities:**

- Built the **distributed monitoring system** from scratch at Mogujie, including data collection, storage, querying, and alerting.
- Developed a **self-developed time series database** to address issues of read/write performance, high storage costs, and batch deletion of expired data.
- Constructed a comprehensive **distributed system** to handle challenges such as scaling, data consistency, and fault recovery.

## Education

### **Hangzhou Dianzi University** `September 2011 - April 2014`

- **Major:** Computer Application Technology
- Master's Degree

### **Ningbo University of Technology** `2007.9 - 2011.7`

- **Major:** Computer Science and Technology
- Bachelor's Degree

<!-- ### Footer

Last updated: May 2023 -->
