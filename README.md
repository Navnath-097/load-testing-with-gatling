# load-testing-with-gatling
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NAVNATH VISHNU CHAVAN

*INTERN ID*: CT08THZ

*DOMAIN*: SOFTWARE TESTING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

## DISCRIPTION OF PROJECT:

Task: To perform advanced load testing of a web application using gatling.

As per following instructions I performed load testing on a web application and the result was like following:

### **Overview**
- The test conducted was named **OrangeHRMLoginTest**.
- It was executed using **Gatling version 3.13.3**, released on **2025-01-22**.
- The test started on **2025-02-11 at 13:47:46 GMT** and ran for **21 seconds**.

---

### **Key Metrics**
#### **Response Time Analysis**
- A bar chart visualizes **response time ranges**:
  - Most requests had a response time of **less than 800ms**.
  - Some requests fell into the **800ms-1200ms** range.
  - A few requests exceeded **1200ms**.
  - There were some **failed requests**.

#### **Number of Requests**
- The test executed a total of **32 requests**.
- A pie chart shows that most requests were **successful (OK)**, while some **failed (KO)**.

#### **Request Execution Breakdown**
- Each request is detailed with statistics such as:
  - **Total Requests**
  - **OK (successful) and KO (failed) requests**
  - **Error percentage**
  - **Response time percentiles (50th, 75th, 95th, and 99th percentiles)**
  - **Mean and max response times**
  - **Standard deviation**

- The request with the **highest response time** took around **4340ms**.
- Some requests completed in as little as **290ms**.

---

### **Errors**
- The error table shows **HTTP 401 (Unauthorized) errors**.
- **100% of failed requests** encountered this error.

---

### **Performance Over Time**
- **Active Users Along the Simulation**
  - The number of **active users remained constant** throughout the test.

- **Response Time Distribution**
  - Most requests had **low response times**.
  - A small percentage of requests had **high response times**.

- **Response Time Percentiles Over Time**
  - Initially, response times fluctuated.
  - Over time, response times **stabilized**.

- **Number of Requests per Second**
  - Requests were **consistently sent** during the test.
  - Some spikes in request rates were observed.

- **Number of Responses per Second**
  - The number of **responses per second** closely follows the request pattern.
  - A **pie chart** shows that most responses were **successful**, with a **few failures**.

---

### **Conclusions**
- **Overall Performance**: The majority of requests responded within a reasonable time frame, but a few outliers had high response times.
- **Failures**: The **HTTP 401 errors** indicate potential authentication issues.
- **Stability**: The system handled a consistent number of requests, but some fluctuations in response time were observed.
- **Improvement Areas**:
  - Investigate **HTTP 401 errors**.
  - Optimize high-latency requests to reduce **response time spikes**.
