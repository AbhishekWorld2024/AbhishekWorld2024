

# Hi there! 👋 I'm Abhishek Arugonda






<h2>📫 Connect with me:</h2>

<p>
  <a href="https://www.linkedin.com/in/abhishek-arugonda-bb611a1b2/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn"/>
  </a>

  <a href="https://x.com/home" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/twitter--v1.png" alt="Twitter"/>
  </a>

  <a href="mailto:abhishek.arugonda223@gmail.com" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/gmail--v1.png" alt="Email"/>
  </a>
</p><br>

<!-- Coder GIF - Centered -->
<p align="center">
  <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif"  alt="Coder GIF" width="600">
</p><br>





<h2>🛠️ Languages & Tools</h2>

<table>
    <thead>
        <tr>
            <th>Category</th>
            <th>Skills</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Programming</strong></td>
            <td>Java, Python, C, JavaScript, Data Structures</td>
        </tr>
        <tr>
            <td><strong>Frameworks & APIs</strong></td>
            <td>Spring Boot, Hibernate, Spring Security, ReactJS, Maven, RestAPI’s , HTML, CSS, Agile Methodologies, Scrum, Apache/Kafka ,
Jenkins.</td>
        </tr>
        <tr>
            <td><strong>Databases</strong></td>
            <td>MySQL,Mongo DB</td>
        </tr>
        <tr>
            <td><strong>DevOps & CI/CD</strong></td>
            <td>Docker, Kubernetes, Jenkins, Azure ACR</td>
        </tr>
        <tr>
            <td><strong>Cloud Platforms</strong></td>
            <td>AWS, Azure</td>
        </tr>
        <tr>
            <td><strong>Testing & QA</strong></td>
            <td>JUnit, Selenium</td>
        </tr>
        <tr>
            <td><strong>Version Control</strong></td>
            <td>Git, GitHub, Linux</td>
        </tr>
       <tr>
      <td><strong>Monitoring & Logging</strong></td>
        <td>ELK Stack (Elasticsearch, Logstash, Kibana), Splunk,Prometheus</td> 
</tr>
    </tbody>
</table>

</body>
</html>









## <h2>🏆 Certifications</h2>

### AWS-Certified-Solutions-Architect-Associate  
<img src="https://github.com/AbhishekWorld2024/AbhishekWorld2024/blob/main/aws-certified-solutions-architect-associate.png?raw=true" alt="AWS Certificate" width="300"/>


<h2>💼 Experience</h2>

<h3>Software Developer <span style="font-weight: normal;">| Aug 2025 – Present</span></h3>
<p><strong>The Cigna Group</strong> — Austin, TX</p>
<ul>
  <li>Designed and developed a full-stack, serverless microservices platform using <strong>ReactJS</strong> and <strong>Redux</strong> for frontend UI.</li>
  <li>Implemented and managed REST endpoint URLs via <strong>AWS API Gateway</strong>, orchestrating backend workflows with <strong>AWS Lambda</strong> and <strong>AWS Step Functions</strong>, improving workflow reliability by <strong>30%</strong> via automated retries.</li>
  <li>Architected cloud-native data flows using <strong>DynamoDB</strong> and <strong>MongoDB</strong>, enabling <strong>99.9% service availability</strong> and achieving <strong>sub-100ms read latency</strong> for high-traffic transactional data.</li>
  <li>Led end-to-end system design and architecture planning, API contracts, orchestration flows, and integration patterns across frontend, API Gateway, serverless compute, external services, and databases for scalable enterprise systems.</li>
  <li>Built and integrated <strong>Java-based backend APIs</strong> for response transformation and business logic execution, reducing API response time by <strong>~20%</strong> through optimized payload handling and caching strategies.</li>
</ul>

<hr/>

<h3>Software Developer <span style="font-weight: normal;">| Dec 2023 – May 2025</span></h3>
<p><strong>The University of Kansas</strong> — Lawrence, KS</p>
<ul>
  <li>Contributed to the development and maintenance of the University of Kansas web platform, improving usability, accessibility, and performance for <strong>10K+ students, faculty, and staff</strong> across multiple academic systems.</li>
  <li>Integrated frontend features with backend services through <strong>RESTful APIs</strong>, collaborating closely with backend teams for seamless data flow, content rendering, and optimized user experience across dynamic pages and modules.</li>
  <li>Monitored and optimized system performance using <strong>AWS CloudWatch</strong> and <strong>Splunk</strong>, enabling real-time observability and reducing incident resolution time by <strong>30%</strong> through proactive alerting.</li>
  <li>Supported backend services using <strong>MongoDB</strong> for website data storage and retrieval, improving data access efficiency by <strong>20%</strong>.</li>
</ul>

<hr/>

<h3>Software Engineer <span style="font-weight: normal;">| Jul 2021 – Jun 2023</span></h3>
<p><strong>Cognizant</strong> — Hyderabad, India</p>
<ul>
  <li>Implemented backend systems using <strong>Java</strong> for payment processing applications, maintaining <strong>99.95% system availability</strong>.</li>
  <li>Optimized microservices architecture for seamless integration of <strong>CBPR+</strong>, <strong>ISO 20022 migration</strong>, and <strong>SEPA payments</strong>.</li>
  <li>Integrated <strong>RESTful APIs</strong> with third-party payment gateways to support secure international payment processing.</li>
  <li>Collaborated with cross-functional teams including payment operations and compliance, reducing integration defects by <strong>25%</strong> and ensuring regulatory adherence across enterprise payment systems.</li>
  <li>Followed <strong>Agile (Scrum)</strong> methodology, actively participating in sprint planning, daily stand-ups, and retrospectives.</li>
</ul>




<h2>Projects</h2>
<h3>Real-time object detection using the ESP32-S3 microcontroller</h3>
<p>Our project focuses on real-time object detection using the ESP32-S3 microcontroller. The goal was to create a lightweight and efficient system that could detect objects within the ESP32-S3's resource constraints.</p>

<h4>Implementation</h4>
<h4>Dataset and Training:</h4>
<p>We used a dataset of approximately 2.2k images and labels, splitting it into training, testing, and validation subsets. The YOLOv5n model was trained with parameters like a 320x320 image size, 50 epochs, and a batch size of 16, achieving precise results.</p>

<h4>Optimization:</h4>
<p>We pruned 20% of the model weights to reduce size and fine-tuned it for optimal performance. The optimized model was converted to TensorFlow Lite format and further quantized to uint8 format to improve compatibility with the ESP32-S3.</p>

<h4>Deployment:</h4>
<p>The uint8 TFLite model was integrated into the ESP32-S3. We wrote source files for camera setup, inference handling, and bounding box visualization. The system streamed live detection results via Wi-Fi, with bounding box coordinates visible on a hosted web page and the serial monitor.</p>


 <h3>DIFFERENTIAL PRIVACY ON HEALTHCARE</h3><br>
->In this project, we presented a comprehensive framework that integrates state-of-the-art
privacy-preserving techniques, addressing the critical privacy concern in healthcare data.<br>
->The main goal of our project is to strengthen the confidentiality of individual records by
implementing differential privacy, a paradigm that is widely acknowledged. The Laplace
mechanism is utilized to incorporate precisely calibrated noise into numeric columns in the database, like
'Age,' 'Billing Amount,' and 'Room Number,' maintaining data integrity while augmenting
privacy.<br>
->Data masking is incorporated to anonymize columns, like 'Medical
Condition' and 'Name,' by restricting their representation to a specific maximum length.<br>
->Applying hashing to tokenization, specific columns such as 'Hospital,' 'Insurance Provider,' and
'Medication' are protected against security breaches.<br>
->To give users concrete control over the degree of privacy they desire to
preserve, the project presents the idea of a privacy budget (ε) as a parameter. <br>
-> This comprehensive method yields a refined healthcare dataset, establishing the groundwork for
responsible data handling and adding to the ongoing conversation about privacy in the
healthcare industry.<br>




