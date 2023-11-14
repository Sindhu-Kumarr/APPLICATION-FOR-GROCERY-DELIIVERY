`      `**SOFTWARE REQUIREMENT SPECIFICATION                                               FOR** 

`         `**APPLICATION OF GROCERY DELIVERY** 

**PREPARED BY :-**  

ISHWARYA SAKTHI.S SINDHU.K           SWATHI.P.S          PONSELVI.V 

**ACADEMIC YEAR:2023-2024*** 

1. **Introduction** 
1. **Purpose** 

The main objective of this document is to illustrate the requirement of the project is application for grocery development. This document gives the detailed description of the both functional and non-functional requirement proposed by the client. The purpose of this project  is  to  provide  a  friendly  environment  to  maintain  the  details  of  customers  and shopkeeper. The main purpose of this project is to maintain easy circulation system using computer and to provide different reports. This project describes the hardware and software interface requirements using ER diagrams and UML diagram. 

2. **Document Convention** 
- Entire document should be justified.** 
- Convention for main tittle** 
- Font face: Times New Roman 
- Font style: Bold 
- Font size: 20 
- Convention for sub tittle 
  - Font face: Times New Roman 
  - Font Style: Bold 
  - Font size:16 
- Convention for body 
- Font face: Times New Roman 
- Font size:14 
3. **Scope of Devlopment Project** 

`            `Developing a grocery delivery service offers several significant benefits and serves various purposes, both for businesses and consumers. Here are some key uses and advantages of developing a grocery delivery service:  Time saving, Freshness, Home delivery, Offline Access, Barcode Scanning. It is especially useful for getting  for  the grocery without going to the and also without the involvement of offline. 

`          `The project can be implemented under various situations. We can add new features as when we require, making reusability, possible as there is flexibility in all the modules. The language  used for developing the project is java as it is quite advantageous than other languages in term of performance, tools available, cross platform compatibility, libraries, cost(freely available) and development process. 

4. **Intended Audience and Reading Suggestions** 

This project is a prototype for the Online Grocery Management System and it is restricted within  the  college  premise.  This  has  been  implemented  under  the  guidance  of  college professors and professional IT individuals. This project is useful for the Grocery Staff, Admin and as well to be consumers and Customers. 

5. **Definitions, Acronyms and Abbreviations** 

` `JAVA -> platform independence 

` `SQL  -> Structured Query Language 

` `ER    -> Entity Relationship  

` `UML -> Unified Modeling Language  

` `IDE   -> Integrated Development Environment 

` `SRS   -> Software Requirement Specification 

` `IEEE  -> Institute of Electrical and Electronics Engineers 

6. **References**  

**Books**  

Software Requirements and Specifications: A Lexicon of Practice, Principles and Prejudices (ACM Press) by Michael Jackson Software Requirements (Microsoft) Second Edition By Karl E. Wiegers  Software  Engineering: A  Practitioner’s Approach  Fifth  Edition  By  Roger  S. Pressman  

**Websites** 

` `https://www.geeksforgeeks.org/how-to-write-a-good-srs [https://techcrunch.com/2020/03/16/grocery-delivery-apps-see-recorddownloads-amid- coronavirus-outbreak/ ](https://techcrunch.com/2020/03/16/grocery-delivery-apps-see-recorddownloads-amid-coronavirus-outbreak/)

2. **Overall Descriptions** 
1. **product perspective** 

`              `A  Use  Case  Diagram  is  a  visual  representation  used  in  the  field  of  software engineering and system analysis to depict the various interactions and functionalities of a system from the perspective of its users, known as actors. These diagrams are part of the Unified Modelling Language (UML) and help in understanding the system's requirements and how users or external entities interact with it.** 

![](Aspose.Words.fca26c38-9f78-4d53-8a2c-40e69f2cdfa4.001.jpeg)

**Fig 2.1 :Use case Diagram for Grocery Delivery** 

`    `This  is broad level diagram of the project showing a basic overview.The user can be either staff or student.This System will provide a search functionality to facilitate the search of resource.This search will be based on various categories viz.buying and selling.Futher the shopkepper can add/update the resources and the resource user from the system.The user of the system can request issue/renew/return of goods for which they would have to follow certain criteria. 

2. **Product Functions** 

`                           `Entity Relationship Diagram of Application of grocery delivery. 

![](Aspose.Words.fca26c38-9f78-4d53-8a2c-40e69f2cdfa4.002.jpeg)

**Fig 2.2  ER Diagram** 

`               `The ER diagram of a grocery store depicts all of the visual instruments of database tables and the relationships between customers, sales, stores, products, etc. It used structured data to define the relationships between structured data groups of supermarket management system functionalities 

3. **User Classes and characteristics** 

`      `For  grocery  delivery  applications,  there  are  different  entities  that  have  different characteristics, roles, and responsibilities to consider for a good environment setup such as 

- Individuals or households 
- Place grocery orders. 
- Contracted drivers or couriers. 
- Responsible for order deliveries 
- Grocery stores or suppliers** 
- Offer product listings and inventory.** 
- System administrators. 
- Manage the application, users, and vendors. 
- Manage user accounts and roles 
4. **Operating Environments** 

`      `The  Grocery  Delivery Application  will  operate  in  a Windows  environment,  ensuring compatibility  with  various  web  browsers,  including  Microsoft  Internet  Explorer,  Google Chrome, and Mozilla Firefox. It will be optimized for Internet Explorer 6.0 and support most features on Mozilla Firefox and Opera 7.0 or higher versions. The sole requirement for using this online product is a stable internet connection. In terms of hardware configuration, the system will function with a minimum of a 40 GB hard disk, a 15” color monitor, and a 122- key keyboard. Basic input devices such as a keyboard and mouse, as well as output devices like monitors and printers, will be supported by the application. This inclusive approach to operating and hardware environments ensures accessibility and usability for a broad range of users.

5. **Assumptions and Dependencies** 

`    `1ft   After this software system maintenance is done , the store IT personal addition / deletion process and update process will be done more quickly and smoothly. 

2ft   Store IT personal will not encounter a syncronization problem on the tablet screen. 3ft    Store IT personal will make requests of other customers faster and more comfortable. 

`    `Achieving these desired ssumption depends on the success of successful engineers, database administrators and front end developers 

.**2.6  System Feature** 

`      `Description of Feature: Customer’s purchase transaction. It is high priority. 

3. **Requirements**  
1. **Software Configuration**:- 

`       `This software package is developed using Java as the front end which is supported by Sun Microsystem. Microsoft SQL Server as the back end to store the database. Operating System: Windows  NT, Windows  98, Windows  XP  and  above.,  Language  &  IDE:  Java  Runtime Environment, Net beans 7.0.1 (front end), Database: MS SQL Server (back end). 

2. **Hardware Configuration:-**  

`      `Processor: Pentium(R)Dual-core CPU        Hard Disk: 40GB  

`      `RAM: 256 MB or more 

3. **Data requirements:-** 

`       `The inputs consist of the query to the database and the output consists of the solutions for the query. The output includes user details for registration, product information such as catalog listings and inventory, order specifics like order IDs and delivery details, reviews and ratings data to facilitate user feedback, and payment records for secure transactions. Location data, both for users and drivers, plays a crucial role in tracking and ensuring timely deliveries. Administrative data logs system activities and analytics provide insights into sales and user behaviour. 

4. **External Interface Requirement** 
1. **User Interfaces:** 
- Define the user interfaces (UI) for the mobile app and website. 
- Specify the layout, design, and navigation elements. 
- Detail the user interactions, including buttons, forms, and menus. 
2. **Hardware Interfaces:** 
**
`          `Describe any hardware devices or peripherals the application interacts with (e.g., GPS for location tracking, camera for barcode scanning. 

3. **Software Interfaces:** 
**
`           `Identify any third-party software components or APIs that the application integrates with: 

- **Payment Gateways:** Specify the interfaces for processing payments securely. 
- **Mapping and Location Services:** Describe the integration with mapping services like Google Maps. 
- **SMS and Push Notification Services:** Detail how the app sends notifications to users. 
5. **Non-Functional Requirements** 
1. **Security:** 

**User  Authentication**:  Define  the  authentication  mechanisms  (e.g.,  multi-factor authentication) to ensure secure user access. 

**Authorization:** Detail access control rules and permissions for different user roles. 

2. **Usability:** 

**User  Interface  Guidelines**:  Specify  adherence  to  user  interface  design  principles  and guidelines for consistency and ease of use. 

**Accessibility**: Ensure the application is accessible to users with disabilities, complying with WCAG standards. 

3. **Error Handling:** 

` `Define how errors and exceptions should be handled, including error codes and messages for ease of debugging and user communication. 

4. **Legal and Compliance:** These requirements ensure that the application complies with relevant laws and regulations: 

**Data Protection Regulations**: Ensures compliance with data protection laws (e.g., GDPR, CCPA) and specifies data retention and deletion policies. 

**Payment Card Industry (PCI) Compliance:** If processing payments, requires adherence to PCI DSS standards. 

5. **Performance**: This requirement ensures that the application performs efficiently and responds quickly. It includes: 

**Response Time**: Specifies the maximum acceptable time for various operations (e.g., product search, order placement) to complete. 

**Scalability:** Defines how the application should scale to handle increased user loads, such as the ability to add more servers or resources as needed. 

6. **Other Requirements:** 
1. **Data and Category Requirements:** 

`     `Data and category requirements are integral to the Grocery Delivery Application, governing how information is structured and utilized. This includes defining data types (user profiles, products, orders), schemas, and category hierarchies for product organization. User profiles' collection, roles, and data privacy measures are also specified. The application ensures real- time  data  synchronization,  implements  data  security,  and  enforces  compliance  with  data protection regulations. Additionally, it addresses data backup, reporting, and analytics needs. Finally, it supports localization and internationalization for a global user base, enriching the user experience.** 

2. **Appendix** 

`           `A: Admin, Abbreviation, Acronym, Assumptions; 

`           `B: Business rules; 

`           `C: Class, Client, Conventions; 

`           `D: Data requirement, Dependencies; 

`           `G: GUI, Grocery; 

`           `K: Key; 

`           `M: Member; 

`           `N: Non-functional Requirement; 

`           `O: Operating environment; 

`           `P: Performance, Perspective, Purpose; 

`           `R: Requirement, Requirement attributes; 

`           `S: Safety, Scope, Security, System features; 

`           `U: User, User class and characteristics, User requirement 

3. **Glossary** 
**
`          `Here is a glossary of terms and definitions commonly used in the context of a grocery delivery application:** 

**User:** A person who accesses and uses the grocery delivery application to browse, shop for groceries, and place orders.** 

**Customer:** A user who places an order and receives grocery deliveries from the application. 

**User  Profile**:  A  user's  account  information,  including  name,  contact  details,  delivery addresses, payment methods, and order history. 

**Product  Catalog**: A  comprehensive  list  of  grocery  items  available  for  purchase  in  the application, including product names, descriptions, prices, and images. 

**Category**: A grouping of similar products within the application to facilitate user navigation and search, such as "Fresh Produce" or "Dairy and Eggs." 

**Cart**: A  virtual  shopping  cart  where  users  can  add,  remove,  and  modify  items  before proceeding to checkout 

**Order:** A user's request to purchase a specific set of grocery items with delivery to a specified address and delivery time.. 

4. **Class Diagram** 
- This class diagram serves as a blueprint for the application's structure, illustrating how classes interact to deliver a seamless grocery shopping and delivery experience while accommodating user management, feedback, and administrative control.The class diagram for the Grocery Delivery Application depicts the essential classes and their relationships within the system.  

**Fig 6.4  Class Diagram for Grocery Delivery** 

![](Aspose.Words.fca26c38-9f78-4d53-8a2c-40e69f2cdfa4.003.jpeg)

- This class diagram outlines the key classes and their relationships in a grocery delivery application. Users can interact with the system by adding items to their cart, placing orders, and tracking the status of their deliveries.**         
