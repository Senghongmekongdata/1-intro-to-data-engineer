# **Introduction to Data Engineering**

![1000_F_345312834_y1esquNNNnxZumL9UwVTnzg7qpeb95Dx](https://user-images.githubusercontent.com/58208161/183018648-3bf94683-b7d7-451f-bbb4-0b08a8c5666a.jpg)

## **What is Data Engineering**
### **Modern Data Ecosystem and Role of Data Engineering**
Modern data ecosystem includes a network of interconnected and continually evolving entities that include:

- Data, that is available in a host of different formats, structures, and sources. 

- Enterprise Data Environment, in which raw data is staged so it can be organized, cleaned, and optimized for use by end-users.

- End-users, such as business stakeholders, analysts, and programmers who consume data for various purposes.

Emerging technologies such as Cloud Computing, Machine Learning, and Big Data, are continually reshaping the data ecosystem and the possibilities it offers.

Data Engineers, Data Analysts, Data Scientists, Business Analysts, and Business Intelligence Analysts, all play a vital role in the ecosystem for deriving insights and business results from data.

The goal of Data Engineering is to make quality data available for analytics and decision-making. And it does this by collecting raw source data, processing data so it becomes usable, storing data, and making quality data available to users securely. 

### **Responsibilities and Skillsets of a Data Engineer**

The role of a Data Engineer includes:

- Gathering data from disparate sources.
- Integrating data into a unified view for data consumers.
- Preparing data for analytics and reporting.
- Managing data pipelines for a continuous flow of data from source to destination systems.
-Managing the complete infrastructure for the collection, processing, and storage of data.

To be successful in their role, Data Engineers need a mix of technical, functional, and soft skills.

- Technical Skills include working with different operating systems and infrastructure components such as virtual machines, networks, and application services. It also includes working with databases and data warehouses, data pipelines, ETL tools, big data processing tools, and languages for querying, manipulating, and processing data. 

- An understanding of the potential application of data in business is an important - skill for a data engineer. Other functional skills include the ability to convert business requirements into technical specifications, an understanding of the software development lifecycle, and the areas of data quality, privacy, security, and governance. 

- Soft Skills include interpersonal skills, the ability to work collaboratively, teamwork, and effective communication. 

## **The Data Engineering Ecosystem**
### **The Data Ecosystem and Languages for Data Professionals**

A Data Engineer’s ecosystem includes the infrastructure, tools, frameworks, and processes for extracting data, architecting and managing data pipelines and data repositories, managing workflows, developing applications, and managing BI and Reporting tools.

Based on how well-defined the structure of the data is, data can be categorized as

- Structured data, that is data which is well organized in formats that can be stored in databases.

- Semi-structured data, that is data which is partially organized and partially free-form.

- Unstructured data, that is data which can not be organized conventionally into rows and columns.

Data comes in a wide-ranging variety of file formats, such as, delimited text files, spreadsheets, XML, PDF, and JSON, each with its own list of benefits and limitations of use.

Data is extracted from multiple data sources, ranging from relational and non-relational databases, to APIs, web services, data streams, social platforms, and sensor devices.

Once the data is identified and gathered from different sources, it needs to be staged in a data repository so that it can be prepared for analysis. The type, format, and sources of data influence the type of data repository that can be used.

Data professionals need a host of languages that can help them extract, prepare, and analyse data. These can be classified as:

- Querying languages, such as SQL, used for accessing and manipulating data from databases.

- Programming languages such as Python, R, and Java, for developing applications and controlling application behavior.

- Shell and Scripting languages, such as Unix/Linux Shell, and PowerShell, for automating repetitive operational tasks.



### **Data Repositories, Data Pipeline, and Data Integration Platforms**

A Data Repository is a general term that refers to data that has been collected, organized, and isolated so that it can be used for reporting, analytics, and also for archival purposes. 

The different types of Data Repositories include:

- Databases, which can be relational or non-relational, each following a set of organizational principles, the types of data they can store, and the tools that can be used to query, organize, and retrieve data.

- Data Warehouses, that consolidate incoming data into one comprehensive store house. 

- Data Marts, that are essentially sub-sections of a data warehouse, built to isolate data for a particular business function or use case.

- Data Lakes, that serve as storage repositories for large amounts of structured, semi-structured, and unstructured data in their native format.

- Big Data Stores, that provide distributed computational and storage infrastructure to store, scale, and process very large data sets.

The ETL, or Extract Transform and Load, Process is an automated process that converts raw data into analysis-ready data by:

- Extracting data from source locations.

- Transforming raw data by cleaning, enriching, standardizing, and validating it.

- Loading the processed data into a destination system or data repository.

The ELT, or Extract Load and Transfer, Process is a variation of the ETL Process. In this process, extracted data is loaded into the target system before the transformations are applied. This process is ideal for Data Lakes and working with Big Data.

Data Pipeline, sometimes used interchangeably with ETL and ELT, encompasses the entire journey of moving data from its source to a destination data lake or application, using the ETL or ELT process.

Data Integration Platforms combine disparate sources of data, physically or logically, to provide a unified view of the data for analytics purposes.


### **Big Data Platform**
Big Data refers to the vast amounts of data that is being produced each moment of every day, by people, tools, and machines. The sheer velocity, volume, and variety of data challenged the tools and systems used for conventional data, leading to the emergence of processing tools and platforms designed specifically for Big Data.

Big Data processing technologies help derive value from big data. These include NoSQL databases and Data Lakes and open-source technologies such as Apache Hadoop, Apache Hive, and Apache Spark.

Hadoop provides distributed storage and processing of large datasets across clusters of computers. One of its main components, the Hadoop File Distribution System, or HDFS, is a storage system for big data.

Hive is a data warehouse software for reading, writing, and managing large datasets.

Spark is a general-purpose data processing engine designed to extract and process large volumes of data. 


## **Data Engineering Lifecyle**
### **Data Platforms, Data Stores, and Security**

The architecture of a data platform can be seen as a set of layers, or functional components, each one performing a set of specific tasks. These layers include:

- Data Ingestion or Data Collection Layer, responsible for bringing data from source systems into the data platform.

- Data Storage and Integration Layer, responsible for storing and merging extracted data.

- Data Processing Layer, responsible for validating, transforming, and applying business rules to data.

- Analysis and User Interface Layer, responsible for delivering processed data to data consumers.

- Data Pipeline Layer, responsible for implementing and maintaining a continuously flowing data pipeline.

A well-designed data repository is essential for building a system that is scalable and capable of performing during high workloads. 

The choice or design of a data store is influenced by the type and volume of data that needs to be stored, the intended use of data, and storage considerations. The privacy, security, and governance needs of your organization also influence this choice.

The CIA, or Confidentiality, Integrity, and Availability triad are three key components of an effective strategy for information security. The CIA triad is applicable to all facets of security, be it infrastructure, network, application, or data security.


### **Data Collection and Data Wragling**

Depending on where the data must be sourced from, there are a number of methods and tools available for gathering data. These include query languages for extracting data from databases, APIs, Web Scraping, Data Streams, RSS Feeds, and Data Exchanges. 

Once the data you need has been gathered and imported, your next step is to make it analytics-ready. This is where the process of Data Wrangling, or Data Munging, comes in. 

Data Wrangling involves a whole range of transformations and cleansing activities performed on the data. Transformation of raw data includes the tasks you undertake to: 

- Structurally manipulate and combine data using Joins and Unions. 

- Normalize data, that is, clean the database of unused and redundant data.

- Denormalize data, that is, combine data from multiple tables into a single table so that it can be queried faster.

- Cleansing activities include: 

- Profiling data to uncover anomalies and quality issues.

- Visualizing data using statistical methods in order to spot outliers. 

- Fixing issues such as missing values, duplicate data, irrelevant data, inconsistent formats, syntax errors, and outliers. 

A variety of software and tools are available for the data wrangling process. Some of the popularly used ones include Excel Power Query, Spreadsheets, OpenRefine, Google DataPrep, Watson Studio Refinery, Trifacta Wrangler, Python, and R, each with their own set of features, strengths, limitations, and applications.

### **Querying Data, Performance Turning, and Troubleshooting**

- In order for raw data to become analytics-ready, a number of transformation and cleansing tasks need to be performed on raw data. And that requires you to understand your dataset from multiple perspectives. One of the ways in which you can explore your dataset is to query it. 

- Basic querying techniques can help you explore your data, such as, counting and aggregating a dataset, identifying extreme values, slicing data, sorting data, filtering patterns, and grouping data.

- In a data engineering lifecycle, the performance of data pipelines, platforms, databases, applications, tools, queries, and scheduled jobs, need to be constantly monitored for performance and availability. 

- The performance of a data pipeline can get impacted if the workload increases significantly, or there are application failures, or a scheduled job does not work as expected, or some of the tools in the pipeline run into compatibility issues. 

- Databases are susceptible to outages, capacity overutilization, application slowdown, and conflicting activities and queries being executed simultaneously. 

- Monitoring and alerting systems collect quantitative data in real time to give visibility into the performance of data pipelines, platforms, databases, applications, tools, queries, scheduled jobs, and more.

- Time-based and condition-based maintenance schedules generate data that helps identify systems and procedures responsible for faults and low availability.


### **Governance and Complaince**

Data Governance is a collection of principles, practices, and processes that help maintain the security, privacy, and integrity of data through its lifecycle.

Personal Information and Sensitive Personal Information, that is, data that can be traced back to an individual or can be used to identify or cause harm to an individual, needs to be protected through governance regulations. 

General Data Protection Regulation, or GDPR, is one such regulation that protects the personal data and privacy of EU citizens for transactions that occur within EU member states. 
Regulations, such as HIPAA (Health Insurance Portability and Accountability Act) for Healthcare, PCI DSS (Payment Card Industry Data Security Standard) for retail, and SOX (Sarbanes Oxley) for financial data are some of the industry-specific regulations. 

Compliance covers the processes and procedures through which an organization adheres to regulations and conducts its operations in a legal and ethical manner.

Compliance requires organizations to maintain an auditable trail of personal data through its lifecycle, which includes acquisition, processing, storage, sharing, retention, and disposal of data.

Tools and technologies play a critical role in the implementation of a governance framework, offering features such as:

- Authentication and Access Control.

- Encryption and Data Masking.

- Hosting options that comply with requirements and restrictions for international data transfers.

- Monitoring and Alerting functionalities.

- Data erasure tools that ensure deleted data cannot be retrieved.

## **DataOps Methodology**
Gartner defines DataOps as a collaborative data management practice focused on improving the communication, integration, and automation of data flows between data managers and consumers across an organization. DataOps aims to create predictable delivery and change management of data, data models, and related artifacts. DataOps uses technology to automate data delivery with the appropriate levels of security, quality, and metadata to improve the use and value of data in a dynamic environment.”

(Source: https://blogs.gartner.com/nick-heudecker/hyping-dataops/)

A small team working on a simpler or limited number of use cases can meet business requirements efficiently. As data pipelines and data infrastructures get more complex, and data teams and consumers grow in size, you need development processes and efficient collaboration between teams to govern the data and analytics lifecycle. From data ingestion and data processing to analytics and reporting, you need to reduce data defects, ensure shorter cycle times, and ensure 360-degree access to quality data for all stakeholders.

DataOps helps you achieve this through metadata management, workflow and test automation, code repositories, collaboration tools, and orchestration to help manage complex tasks and workflows. Using the DataOps methodology ensures all activities occur in the right order the right security permissions. It helps set in a continual process that allows you to cut wastages, streamline steps, automate processes, increase throughput, and improve continually.

Several DataOps Platforms are available in the market, some of the popular ones being IBM DataOps, Nexla, Switchboard, Streamsets, and Infoworks.

### **DataOps Methodology:**
The purpose of the DataOps Methodology is to enable an organization to utilize a repeatable process to build and deploy analytics and data pipelines. Successful implementation of this methodology allows an organization to know, trust, and use data to drive value.

It ensures that the data used in problem-solving and decision making is relevant, reliable, and traceable and improves the probability of achieving desired business outcomes. And it does so by tackling the challenges associated with inefficiencies in accessing, preparing, integrating, and making data available.

In a nutshell, the DataOps Methodology consists of three main phases:

- The **Establish DataOps Phase** provides guidance on how to set up the organization for success in managing data.
- The **Iterate DataOps Phase** delivers the data for one defined sprint.
- The **Improve DataOps Phase** ensures learnings from each sprint is channeled back to continually improve the DataOps process.

The figure below presents a high-level overview of these phases and the key activities within each of these phases.

![Un9ggw6dSQy_YIMOnbkMWA_658a6043f3f845baa2d7c86b89754683_DataOpsMethodology](https://user-images.githubusercontent.com/58208161/183378489-acdb97be-2ed1-4054-be9d-87d91f9edf12.png)

### **Benefits of using the DataOps methodology:**
Adopting the DataOps methodology helps organizations to organize their data and make it more trusted and secure. Using the DataOps methodology, organizations can:

- Automate metadata management and catalog data assets, making them easy to access.
- Trace data lineage to establish its credibility and for compliance and audit purposes.
- Automate workflows and jobs in the data lifecycle to ensure data integrity, relevancy, and security.
- Streamline the workflow and processes to ensure data access and delivery needs can be met at optimal speed.
- Ensure a business-ready data pipeline that is always available for all data consumers and business stakeholders.
- Build a data-driven culture in the organization through automation, data quality, and governance.

As a data practitioner, using the methodology can help you reduce development time, cut wastages and duplication of effort, increase your productivity and throughput, and ensure that your actions produce the best possible quality of data. 

With DataOps, data professionals, consumers, and stakeholders can collaborate more effectively towards the shared goal of creating valuable insights for business. While implementing the methodology will require systemic change, time, and resources, but in the end, it makes data and analytics more efficient and reliable.

Interestingly, it also opens up additional career opportunities for you as a data engineer. **DataOps Engineers** are technical professionals that focus on the development and deployment lifecycle rather than the product itself. And as you grow in experience, you can move into more specialist roles within DataOps, contributing to defining the data strategy, developing and deploying business processes, establishing performance metrics, and measuring performance.

# **Career Opportunities and Learning Paths**
## **Data Warehousing Specialist**
### **Data Warehousing Specialist role**
Data Warehousing Specialists design, model, and implement corporate data warehousing activities, program and configure warehouses of databases, and provide support to data warehouse users. The tasks for this specialist role are focussed on data warehousing and form a significant subset of the wider Data Engineering role.

### **Opportunity estimates for the Data Warehousing Specialist role**
According to careeronestop.org, an organization sponsored by the U.S. Department of Labour, the future is bright for Data Warehouse Specialists and very similar or related roles, such as Data Architects and Database Administrators. The expected growth rate of opportunities in these fields is higher than the average, and is expected to average about 8 to 10 percent per year over the next decade. Approximately 13,900 openings are expected to emerge each year in the U.S. alone.

According to salary.com, the median salary for a Data Warehouse Specialist in the US is $110,168.


### **Data Warehousing Specialist alternative job titles**
Just like the role of Data Engineer, the Data Warehousing Specialist role is quite fluid and can vary considerably. In fact, the Data Warehousing Specialist is a particluar kind of Data Engineer, more tightly focused on the data warehousing aspects of the broader discipline. Accordingly, searching online job postings for this particular role returns many other closely related positions, including:

- Data Warehouse Specialist
- Data Warehouse Engineer
- Data Warehouse Solution Architect
- Data Warehousing/ETL Solution Specialist
- Data Warehouse Architect
- Data Architect, Data Warehousing & MPP
- Data Warehouse Analyst
- Data Warehouse Administrator
- Data Warehousing Development Specialist

### **Tasks performed by Data Warehousing Specialists**
As a specialization within the broader field of Data Engineering, Data Warehousing Specialists may be responsible for many kinds of tasks. These tasks may include any of the following:

- Developing processes, procedures, and software applications for enterprise data management
- Analyzing and improving data warehousing processes for efficiency, accuracy, usablilty, or security
- Designing, modelling, or implementing corporate data warehousing activities
- Developing or maintaining standards, such as organization, structure, or nomenclature, for the design of data warehouse elements, such as data architectures, models, tools, and databases
- Providing or coordinating troubleshooting support for data warehouses
- Writing or modifying programs to meet customer requirements
- Creating documentation such as metadata and diagrams of entity relationships, business processes, and process flow
- Designing, implementing, or operating comprehensive data warehouse systems to balance optimization of data access with batch loading and resource utilization factors, according to customer requirements
- Performing system analysis, data analysis or programming, using a variety of computer languages and procedures
- Reviewing designs, code, test plans, or documentation to ensure quality
- Creating plans, test files, and scripts for data warehouse testing, ranging from unit to integration testing
- Implementing business rules via stored procedures, middleware, or other technologies
- Supporting users of the data warehouse

### **Soft skills required for the Data Warehousing Specialist role**
- Critical thinking - Using logic and reasoning to identify the strengths and weaknesses of alternative solutions, conclusions, or approaches to problems
- Complex problem solving - Identifying complex problems and reviewing related information to develop and evaluate options and implement solutions
- Decision making - Assessing the costs and benefits of a variety of optional solutions, and choosing the most appropriate solution
- Systems evaluation - Identifying and evaluating system performance measures, and actions needed to improve or correct poor performance
- Active learning - Understanding the implications of new information or technologies for both current and future problem-solving and decision-making
Communicating effectively

### **Technical Skills required for the Data Warehousing Specialist role**
#### **Specialized knowledge**
- Programming - writing computer programs for various purposes
- Systems analysis - determining how a business system works, and understanding how changes in conditions may affect outcomes
- Data architecture - understanding the models, the policies, rules or standards that govern which data is collected, how data is stored, arranged, and integrated, and how to put data to use in data systems
- Data management and analysis - securely collecting, storing, and analyzing data
- Data pipelines - building and maintaining data pipelines
- Business intelligence - data warehousing; extract, transform, and load (ETL); and data mapping
- Database normalization - data integrity and normalization
- Data storage structures - especially relational databases
- Data migration - ETL of data from one system to another
- Metadata management and metadata standards
- Data integration platforms
- Overview of the Data Engineering Ecosystem
- Cloud data - building scalable cloud data infrastructure
- Database administration, including Big Data administration
- Data acquisition and transformation - Digitizing data for display, analysis, and storage
- Data lakes, data marts, data reservoirs
- IoT - Integrating data from various connected devices and systems in IoT using data pipelines
- Building event streaming pipelines

#### **Law & Government**
- Acts & Regulations - knowledge of laws, regulations, requirements and ethical issues related to the access and use of information, for example intellectual capital, personally identifiable information, and customer data

#### **Software and IT skills**
- Cloud computing and cloud platforms: Amazon Web Services (AWS), Microsoft Azure, SpringCloud, GCS (Google Cloud Storage)
- Data warehouse tools: Snowflake, Data Bricks, BigQuery, Redshift, Db2
- Data pipeline tools: Apache Kafka, Apache Airflow, Luigi
- Big data tools: Apache Hadoop, Apache Spark, Apache Hive
- Operating systems: UNIX, Linux
- Programming languages: SQL, Bash, Python, R, Java, C++
- Databases - Cassandra, Microsoft SQL Server, MySQL, PostgreSQL, Amazon DynamoDB, Apache Solr, IBM Db2, MongoDB, neo4j, Oracle PL/SQL, PostgreSQL
- Metadata management software - CA Erwin Data Modeler; Oracle Warehouse Builder; SAS Data Integration Server; Talend Data Fabric; Alation Data Catalog, SAP Information Steward, Azure Data Catalog, IBM Watson Knowledge Catalog, Oracle Enterprise Metadata Management (OEMM), Adaptive Metadata Manager, Unifi Data Catalog, data.world, and Informatica Enterprise Data Catalog
- Agile software development methodologies
- Version control - Git
- Modelling and API development
- Business intelligence and data analysis software - IBM Cognos Impromptu, MicroStrategy, Microsoft Power BI, Google Analytics, InsightSquared, Oracle Business Intelligence Enterprise Edition, Qlik Tech QlikView, ‎Sisense, ‎Tableau, ‎Dundas BI, ‎SAS Analytics, Domo, SAP Lumira


### **Pathways to becoming a Data Warehouse Specialist**
There are many possible paths to becoming a Data Warehousing Specialist. Most practitioners have a minimum of a Bachelor's Degree in a mathematical or computational field such as Computer Science, Computer Engineering or the Mathematical Sciences. However, many practitioners instead have a Technology or Technical Diploma in a Computational or Information Technology discipline. Combining this educational background with some hands-on experience with application development and use of software for managing databases and metadata is a good way to prepare for the role.


### **Career progression**
The career progression of a Data Warehouse Specialist might take a direct path, such as starting at the Junior or Associate Data Warehouse Specialist role, and evolving over time through the Data Warehouse Specialist, Senior Data Warehouse Specialist, Lead Data Warehouse Specialist, and Principal Data Warehouse Specialist roles. Having said that, the path of progression is by no means unique.

Since the Data Warehouse Specialist role is simply a Data Engineering role with an emphasis on Data Warehousing, you will most likely find yourself shifting between specializations within the Data Engineering world, depending on your interests and abilities as well as the needs of the teams you find yourself working with.

On smaller teams you may need to participate day-to-day in many or all stages of the data engineering lifecycle. Working with larger teams, you will naturally find some combination of a smaller niche and career progression as the best fit. No matter your path, in order to progress throughout your career as an engineer, you will always need to be learning about and making use of emerging tools and technologies. This continuous learning will also inform you as you discover your path.


### **Summary**
In this reading, you learned that:

- The Data Warehousing Specialist is a particluar kind of Data Engineer, more tightly focused on the data warehousing aspects of the broader discipline
- Data Warehousing Specialists design, model, and implement corporate data warehousing activities, program and configure warehouses of databases, and provide support to data warehouse users
- Data Warehousing Specialists require specialized knowledge of data architecture - understanding the models, the policies, rules or standards that govern which data is collected, how data is stored, arranged, and integrated, and how to put data to use in data systems
- Soft skills required for the data warehousing specialist role include complex problem solving and active learning
- No matter your path, in order to progress throughout your career as an engineer, you will always need to be learning about and making use of emerging tools and technologies


<br />

> **Congratulation for your data journey...!**
