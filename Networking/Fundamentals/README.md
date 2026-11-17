**1. What is Computer Networking?**

Computer networking is the process of connecting two or more devices to communicate and share resources such as files, data, and services.

**2. Types of Networks**

   **PAN** (Personal Area Network): Short-range connection between personal devices. Example: Mobile connected to Bluetooth earphones.
   
   **LAN** (Local Area Network): Connects devices within a limited area. Example: Your home Wi-Fi network or a college building.
   
   **WLAN** stands for Wireless Local Area Network, which is a computer network that links two or more devices together using radio waves instead of    physical cables within a limited area like a home, school, or office building
   
   **MAN** (Metropolitan Area Network): Connects multiple networks across a city. Example: Connecting different college branches across a city.
   
   **WAN** (Wide Area Network): Connects networks across large geographical areas, such as countries or continents. Example: A bank connecting its      branches across India.

**3. Network Architectures**

**CLIENT – SERVER Architecture**: REQUEST AND RESPONSE MODEL
1.	Client: Your web browser (Chrome) where you open Amazon.
2.	Frontend: The user interface displayed in your browser (products, images, search bar, login page).
3.	Server/Backend: Handles business logic, user authentication, product details, orders, and database operations.
4.	Communication: When you search for a product or place an order, your browser sends a request to the server. The server processes it and sends a response back to your browser.

**TYPES:**

**2-Tier Architecture**
•	Structure: A client-server model split into two layers: the Client Tier (user interface and presentation logic) and the Server Tier (database operations and sometimes core application logic).
•	How it works: The client application communicates directly with the database server using database APIs like ODBC or JDBC.
•	Pros: Simple to design, lower initial cost, faster data retrieval for smaller user bases.
•	Cons: Limited scalability, poor performance under high traffic, and security risks because the client connects directly to the database.
•	Example: A local Library Management System or a small-scale contact management tool

**3-Tier Architecture**
•	Structure: An expanded model divided into three distinct layers: the Presentation Tier (UI/web browser), the Application Tier (business logic and processing), and the Data Tier (database management and storage). 
•	How it works: The client never talks directly to the database; instead, it sends requests to an intermediate application/web server, which processes business rules and queries the database.
•	Pros: High scalability, improved security, better fault isolation, and independent maintenance of each layer.
•	Cons: Greater architectural complexity, higher development effort, and increased infrastructure cost.
•	Example: Large-scale e-commerce websites and enterprise web applications. 

**N-Tier Architecture (Multi-Tier)**
•	Structure: A generalized, distributed architecture where software functions are broken down into three or more independent logical tiers or physical servers (e.g., separating web servers, application servers, caching layers, and clustered database servers).
•	How it works: Components run across separate hardware, data centers, or cloud environments, communicating via APIs, message queues, or microservices.
•	Pros: Maximum scalability, high availability, superior disaster recovery, and the ability to scale individual components (like microservices) independently.
•	Cons: High operational overhead (DevOps complexity), network latency between distributed nodes, and steep infrastructure expenses.
•	Example: Distributed cloud-native apps hosted on or enterprise banking systems. 


