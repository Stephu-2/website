1.Introduction ……………………………………………………………………   01
1.1Abstract
1.2Project Overview
1.3 Objectives and Methodologies
1.4Time Schedule
1.5Organization Profile (Company details)
2.Literature Survey……………………………………………………………….    07
2.1Existing System
2.2Proposed System
3.Modules And System Implementations………………………………………    08
3.1System Requirement Specification
3.2Hardware requirements
3.3Module Description
3.4User Requirement Specification
4.System Analysis……………………………………………………………….     13
4.1ER Diagram
4.2Architecture Diagram
4.3Use-Case Diagram
4.4Class Diagram
4.5Table Design
5.Screenshots……………………………………………………………………     20
6.Source Code ………………………………………………………………….      32
7.Conclusion………………………………………………………………………   43
     8.    References………………………………………………………………………   44







CHAPTER I
INTRODUCTION

1.1 ABSTRACT:

          In Today’s world, everything is digitalized so the medical fields have to be digitalized so I created this website to book appointments online for consulting. The digitalization of healthcare services has become essential in the modern day to improve patient care and expedite medical procedures. The creation of medical appointment software has evolved as a crucial response to the problems associated with coordination, scheduling, and communication in healthcare settings as part of this continuous shift. the development and implementation of a user-friendly medical appointment website. The project addresses the growing need for efficient and convenient patient-doctor interaction in the modern healthcare system. The website offers online appointment scheduling, doctor profile browsing, appointment cancellation/rescheduling, and secure patient health information management. It aims to improve patient experience, and increase access to healthcare services. The project includes detailed information on the development process, technical specifications, user interface design, and security measures employed. Additionally, it evaluates the website's effectiveness in achieving its objectives through user testing and feedback analysis. This document concludes by outlining the project's contributions to healthcare technology and exploring potential enhancements.

1.2 OVERVIEW OF THE PROJECT:

         The Medical Appointment Website is a web application developed over a period time of two months, with features for booking appointments and managing doctors' and patients' details, users have the features to book appointments and download invoices. Admin is the person who manages both doctor and patient details.
                       
                       The aim of the project is to modernize hospital systems in India through digitization, offering streamlined operations and enhanced patient care. The admin module provides comprehensive control over the system, allowing for the registration, management, and oversight of doctors, patients, appointments, and admissions. Admins can efficiently handle doctor registrations, patient admissions, appointment bookings, and invoice generation. They can also oversee the approval and rejection of various requests, ensuring smooth operations and compliance with hospital protocols. Meanwhile, the patient module facilitates seamless interaction with the hospital, enabling users to create accounts, view doctor details, book appointments, and access invoices and prescriptions. Patient accounts require approval from the hospital admin, to ensure secure access and adherence to privacy measures. The doctor module caters to medical professionals, offering them access to patient details, appointment schedules, and discharge lists. Doctors can efficiently manage their patient load, view appointments assigned to them, and delete appointments once attended, streamlining their workflow and improving patient care. Overall, the project aims to revolutionize hospital management in India, enhancing efficiency, accessibility, and quality of care through digital solutions.

1.2.1 PROBLEM STATEMENT

In recent years, there has been a significant shift towards online platforms for various services, including healthcare. However, the process of scheduling medical appointments remains tedious and time-consuming for both patients and healthcare providers. There is a need for a streamlined and efficient medical appointment website that caters to the needs of both parties.              
By tackling several significant issues, the Medical Appointment Website aims to completely transform the way people make appointments with medical specialists. Patients now face difficulties making appointments because of a lack of availability, lengthy wait periods, and complicated procedures. With an intuitive interface, this technology seeks to streamline the scheduling procedure and guarantee effective administration for healthcare practitioners. Appointment reminders, alerts, and messaging capabilities on the website help to ensure timely and clear communication—essential in preventing missed appointments and miscommunications. Furthermore, patients may schedule appointments at their leisure because to round-the-clock accessibility, which does away with the necessity





1.3 OBJECTIVES AND METHODOLOGIES:
Objectives:
Design and develop a web-based interface for the Medical Appointment Booking System using Python's Django framework and HTML/CSS.
Implement database schema and tables using MySQL to store and manage appointment-related data, including patient details, doctor availability, and appointment bookings.
Develop modules for patient registration, appointment search, booking management, and notification handling, ensuring seamless user experience and efficient data management.
Implement functionalities for healthcare providers to manage appointment schedules, approve bookings, and generate invoices for services rendered.
Document the system architecture, design decisions, and implementation details for future reference and maintenance.

Methodology:
Set up the development environment using Python, Django framework, and MySQL database on a Windows system.
Design the user interface using HTML/CSS, incorporating responsive design principles for optimal viewing across different devices.
Define the database schema and create tables in MySQL to store appointment-related data, ensuring data integrity and normalization.
Develop Python modules for different functionalities of the Medical Appointment Booking System, including user authentication, appointment management, and notification handling.
Integrate the frontend interface with the backend database using Django and MySQL connectors, enabling seamless data retrieval and manipulation.
Deploy the Medical Appointment Booking System on Windows servers within the healthcare facility, providing necessary training and support to users for effective utilization.


1.4 TIME SCHEDULE
 
S. No	Title	Description	Date
1.	
Reporting to the company	
Going to the company and mailing the offer letter to the department	
22/12/2023
2.	
Choosing the Project Title	
Confirmation of the title of the project with the guides	
23/12/2023
3.	
Requirements Document	
Completing the User Requirement and System Requirement Documents	
28/12/2023
4.	
Design Document	Finalizing and Completing the Design Document	
29/12/2023
5.	
UI Design	Completing the UI Design for the project	
31/12/2023
6.	
Database Design	
Creating and Completing the Database Design for the project	
02/01/2024
7.	
Project Implementation	Implementation of the project and deployment are completed	
20/02/2024
8.	
Testing	
After Implementation, the testing process of the project is completed	
24/02/2024
9.	
Documentation	Completing the Project Documentation	
28/02/2024
10.	
  First Review	  First Review of the project	
  07/03/2024



1.5 ORGANIZATION PROFILE
CODENATIVES INDIA PRIVATE LIMITED 
	Codenatives India Private Limited is a Chennai-based IT company providing innovative web development and android application services solutions IT Services since 2002. We are innovative, hardworking, and excel at creating optimal experiences for our customers. Our enduring partnerships are forged by the skilled and dedicated team members who are truly committed to the success of our clients. From start to finish, we care and take pride in our long-lasting relationships.
	Headquartered out of Cupertino, California, we have a global network of staff and customers throughout the United States, Canada, the United Kingdom, and Singapore. We have over 200 consultants in our network in the United States alone. We have a dedicated talent sourcing & recruitment team who identify and recruit specialized talents across industry verticals and add to our select team of exceptional members. We groom our employee’s skills in our in-house training and career-building division.
OUR SERVICES:
	Data engineering and AI services are pivotal for success, transforming decision-making from user behaviour analysis to profit projection. With expert tag deployment and tracking, business owners gain insights into customer interests and shape feature development. Our dedicated data engineering team handles vast data volumes to optimize business value chains.
	We handle massive data volumes from IoT sensors, eCommerce, social media, CRM, and TMS platforms daily. Our skilled Data Engineering team creates robust infrastructure, efficient data cleansing, and optimization processes to extract actionable insights for your business success.
We integrate scalable solutions with your current data architecture to kickstart your data modernization journey, streamlining data preparation with automated workflows and modern data fabric.
1.Cloud Data Platform Transformation:
Codenatives empowers organizations to harness the full potential of cloud data warehouses and data lakes while pioneering cloud-first architectural solutions. Our comprehensive cloud data management services facilitate the acquisition, storage, and analysis of vast data volumes, delivering exceptional real-time data analytics performance. With our team of expert data analysts, organizations can optimize costs, streamline resource allocation, and craft a strategic approach to cloud adoption.
2.Data Operation Solution Services	
Our accelerators swiftly operationalize modern cloud-based data platforms, encompassing Data Ops essentials like data ingestion, provisioning, cataloging, quality assurance, testing, and deployment. Automated DataOps enhances data availability, accessibility, and integration, fostering synergy among individuals, processes, and technology for consistent, top-tier data accessible to all stakeholders. This collaborative approach revolutionizes data flow development, driving innovation in analytics models and intelligence systems.
3.AI Generative and Predictive Services
Looking ahead, we envision integrating advanced AI models, including regression, time series, random forests, neural networks, and clustering algorithms, to enhance various use cases like demand forecasting, sales prediction, sentiment analysis, dynamic pricing, personalized recommendations, churn predictions, future sales projections, marketing insights, and cross-channel customer understanding.

4.ML Operational Intelligence Services
Codenatives empower businesses with MLOps for tailored solutions, focusing on streamlined automated ML lifecycles, robust governance and monitoring, workforce insights, smarter finances, smarter procurement in your SCM, AI/ML workflows, and effortless model deployments.
5.Web App Development
We create and maintain Web Apps that add value to your business
We have a long history of building Web Apps for customers. We have learned over the years to pay attention to the user’s needs and design the Web Apps to be user-centric, performance-optimized, secure, and scalable. We also host, support, maintain, and continuously add features to the Web Apps to keep the technology and user experience current and relevant to the evolving business needs.
6.SaaS Development
We have the necessary expertise to make your ideas into a Software as a Service (SaaS) that can bring in significant revenue. We bring the right knowledge and expertise to architect solutions that are scalable, secure, reliable, configurable, and that fits your business needs 100%


CHAPTER III

REQUIREMENT SPECIFICATIONS
 
233.1 SYSTEM REQUIREMENT SPECIFICATION
 
               The System Requirement Specification provides requirement that are to be used in customer systems and customer environment. The Design, Coding, Implementation and the testing are prepared from the system requirement specification.
 
	Operating system 	: Windows
	Version		: Above 7
Database		: MySQL
 
WINDOWS SOFTWARE
 
Operating System	: Windows
Software		: PyCharm
Back End		: MySQL 		
	
3.2 HARDWARE REQUIREMENT SPECIFICATION
 
Processor	: Intel core i3 (with speed of 2.0 GHz and above)
RAM		: 4GB RAM
Memory	: 1 GB

 
3.3 MODULE DESCRIPTION
List of Modules:
               1. Admin Module
                      1.1 Authentication
                      1.2 Doctor Management
                      1.3 Patient Management
                     1.4 Appointment Management

              2. Patient Module
                       2.1 Authentication
                       2.2 Doctor Details
                       2.3 Appointment Booking

           3. Doctor Module
                      3.1 Authentication
                      3.2 Patient Management
                      3.3 Appointment Management


3.4 USER REQUIREMENT SPECIFICATION
   The Medical Appointment Booking System aims to provide a user-friendly platform for patients, doctors, and administrators to efficiently manage medical appointments, patient admissions, and doctor-patient interactions. This document outlines the functional and non-functional requirements of the system to meet the needs of all stakeholders.
1. User Profiles:
The system will support three user roles:
Administrator: Responsible for managing doctors, patients, appointments, and system configurations.
Patient: Individuals seeking medical care who can book appointments, view doctor details, and access their medical records.
Doctor: Healthcare professionals responsible for providing medical care to patients, viewing appointment schedules, and managing patient interactions.
2. Functional Requirements:
Administrator: Ability to sign up and login securely without requiring approval

 1. Manage doctor profiles:
Register new doctors with details such as name, specialization, and contact information.
View, approve, reject, or delete doctor registrations.

2. Manage patient admissions:
Admit new patients with necessary details such as name, age, and medical history.
View, approve, reject, or discharge patient admissions.

3. Manage appointments:
Book appointments for patients with available doctors.
View, approve, reject, or cancel appointment requests.
Generate and download invoice PDFs for appointments.
View and manage appointment schedules and patient records.

Patient:
Ability to sign up and login securely with approval required by the admin.
View assigned doctor details including name, specialization, and contact information.
View booked appointment status (pending, confirmed).
Book appointments with available doctors.
View and download invoice PDFs for attended appointments.
View and download prescription PDFs provided by doctors.



4.5 Table Design:
  Patient Table:
         Field Name	Data Type	NULL	     Key
id	Integer	No	Primary
user_id	Integer (FK)	No	Foreign
Patient_First_Name	Varchar(50)	No	
Patient_Last_Name	Varchar(50)	No	
gender	Char(10)	No	
contact	Char(10)	No	
address	Varchar(350)	No	
symptoms	Varchar(500)	No	
status	Boolean	No	
admitDate	Date	No	
assignedDoctorId	Integer	Yes	Foreign

Doctor Table:
Field Name	Data Type	NULL	Key
id	Integer	No	Primary
user_id	Integer (FK)	No	Foreign
Doctor_First_Name	Varchar(50)	No	
Doctor_Last_Name	Varchar(50)	No	
gender	Char(10)	No	
address	Varchar(40)	No	
contact	Char(10)	Yes	
department	Varchar(50)	No	
status	Boolean	No	



Appointment Table:

Field Name	Data Type	NULL	Key	
id	Integer	No	Primary	
patientId	Positive Integer	Yes	Foreign	
doctorId	Positive Integer	Yes	Foreign	
patientName	Char(40)	Yes		
doctorName	Char(40)	Yes		
appointmentDate	Date	No		
description	Text	No		
status	Boolean	No		
time	Char(10)	No		






PatientDischarge Table:
Field Name	Data Type	NULL	Key
id	Integer	No	Primary
patientId	Positive Integer	Yes	Foreign
patientName	Char(40)	No	
assignedDoctorName	Char(40)	No	
address	Char(40)	No	
mobile	Char(20)	Yes	
symptoms	Char(100)	Yes	
admitDate	Date	No	
releaseDate	Date	No	
daySpent	Positive Integer	No	
roomCharge	Positive Integer	No	
medicineCost	Positive Integer	No	
doctorFee	Positive Integer	No	
OtherCharge	Positive Integer	No	
total	Positive Integer	No	



CONCLUSION 
  The use of a medical appointment web application benefits patients and healthcare professionals alike by increasing efficiency and convenience. The appointment procedure is streamlined to save workload and free up hospital staff members to concentrate on patient care. By making it simple for patients to schedule appointments from the comfort of their homes, it also gives them the power to take charge of their healthcare experience. This digital technology encourages improved medical care administration and organization in addition to time savings. In the end, accepting these technological developments creates a standard for upcoming medical innovation and encourages a more patient-centered method of providing care.






















