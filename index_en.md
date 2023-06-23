---
layout: cv
title: MengYe Shen
email:
  url: mailto:smy19890720@gmail.com
  text: smy19890720@gmail.com
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
* Good understanding of the core module source code of Mongodb.
* Good understanding of the Influxdb source code for time-series data engine.
* Familiar with LSM-structured data storage engines like Leveldb, Rocksdb.
* Familiarity with consensus algorithms such as Raft and MongoDB's consensus algorithm.

## Work Experience

### **Shanghai Qiniu Cloud Technology Co., Ltd.** `August 2020 - Present`

_**Cloud Storage Technology Expert**_<br>

***Achievements: Improved performance and stability of large-scale MongoDB clusters, led optimization and transformation of object storage lifecycle solution, and provided business support for object storage metadata management.***<br>

#### 1. MongoDB Performance and Stability Improvement

**Project Description:**

- Resolved the issue of 1-2 seconds of service unavailability after MongoDB routing refresh, reducing overall response latency.
- Accelerated the scaling speed of MongoDB, addressing the slow scaling speed and unexpected results.
- Added circuit-breaking and flow control capabilities at the MongoDB kernel level to better protect the underlying database.
- Improved MongoDB's stability in various edge cases, such as slow disks and primary node failure.
- Optimized MongoDB request latency and enhanced overall response time.
- Isolated MongoDB shard failures for business continuity.

**Responsibilities:** Led develop and design.

**Project Results:**

1. Reduced MongoDB routing refresh time from `1-2s` to `10-100ms`, significantly improving MongoDB's stability and maintenance complexity.
2. Shortened the time for scaling MongoDB from 3-4 months to within 1 month by introducing parallel migration solutions for data balancing.
3. Significantly reduced the impact of MongoDB's stability issues on business and SRE operations, automatically recovering from most MongoDB issues.
4. Reduced secondary query latency from seconds to milliseconds.
5. Minimized the business impact caused by a MongoDB shard failure, reducing company losses.<br>

### **Alibaba** `September 2019 - August 2020`

_**Technical Expert (P7)**_<br>

***Achievements: Maintenance and development of distributed monitoring system within Alibaba Group, downsizing of Alibaba Cloud proprietary cloud monitoring system.***<br>

#### Miniaturization Solution for Private Cloud Monitoring System

#### 1. Downsizing Alibaba Cloud Monitoring System

**Project Description:** Consolidated multiple monitoring products in the basic infrastructure and provided an efficient and comprehensive monitoring system.

**Responsibilities:** develop and design.

**Project Results:** Merged multiple monitoring systems to provide unified and automated monitoring services to the upper layer. Reduced resource consumption of the monitoring system itself, enhanced the competitiveness of the Alibaba Cloud proprietary cloud monitoring system, and achieved the goal of full functionality and low resource consumption.

<br>

### **Hangzhou Shi Qu Information Technology Co., Ltd. (Mogujie)** `April 2014 - August 2019`

_**Senior Development Engineer**_<br>

***Achievements: development of distributed monitoring system, self-developed high-performance time-series data engine, development and maintenance of distributed log system.***<br>

#### 1. Distributed Monitoring System

**Project Description:**

- Peer-to-peer distributed system without a single point of failure, easy deployment, stable operation, with a throughput of 200,000 TPS per server.
- Self-developed TimeDB database with LSM structure for easy migration and data cleaning.
- Real-time collection of monitoring data at the second level.
- Scaling support within 10 minutes.
- Active aggregation and query caching.
- Alerting and warning.

**Responsibilities:** develop and design.

**Project Results:** The throughput is an order of magnitude higher than OpenTSDB, widely used in various business systems of Mogujie, including finance and advertising systems.

#### 2. Distributed Log System

**Project Description:**

- TB-level data collection.
- All-in-one log collection, analysis, and search.
- Self-service configuration with user-friendly experience.

**Responsibilities:** Led design and development.

**Project Results:**

- Supported TB-level log collection for Mogujie with low latency, high throughput, and high availability, ensuring the company's report generation and advertising reconciliation.
- Widely used in various business systems of Mogujie, enabling near real-time log search and analysis.

**Related Technologies:** Kafka, Elasticsearch, Logagent

## Education

### **Hangzhou Dianzi University** `September 2011 - April 2014`

- **Major:** Computer Application Technology
- Master's Degree

<!-- ### Footer

Last updated: May 2023 -->
