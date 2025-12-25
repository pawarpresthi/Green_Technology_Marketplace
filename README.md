# Green-Market-Place-Web_Application
The Green Super Market Web Application is a modern, eco-friendly online shopping platform designed to make grocery shopping sustainable, convenient, and user-friendly..  
Java-Web-Application
This is a Java Web Application project created with JSP and Servlet .  
  
### Recommended Tools and Versions  
--- **IDE :-**  IntelliJ Idea Community Edition  
--- **Java Version :-**  24.0.  
--- **Tomcat Version :-**  11.15.  
--- **Database :-**  MySQL  

### Demonstration: Green Market Place
<img width="1661" height="923" alt="image" src="https://github.com/user-attachments/assets/378e9057-ec47-4656-b29e-fba7868c35c4" />
<img width="1666" height="952" alt="image" src="https://github.com/user-attachments/assets/8769bce6-9b0a-4221-97f1-8d9c760a4053" />
<img width="1669" height="966" alt="image" src="https://github.com/user-attachments/assets/0cd73131-2184-4bf7-a9c5-869fe5fb0efa" />
<img width="1648" height="769" alt="image" src="https://github.com/user-attachments/assets/ec1c026a-2470-44a7-bc64-80a9e641887d" />
<img width="1662" height="759" alt="image" src="https://github.com/user-attachments/assets/6ba8e583-89ea-4bbc-b541-a0282afd3e37" />
<img width="1661" height="774" alt="image" src="https://github.com/user-attachments/assets/ae5c913f-97b6-4991-8136-c0fbdcec42c1" />
<img width="1661" height="801" alt="image" src="https://github.com/user-attachments/assets/e77d3ab6-3fce-41bd-af2b-4ebd4091ea40" />
<img width="1664" height="777" alt="image" src="https://github.com/user-attachments/assets/9a94c1d7-74fe-40c4-a4e3-6e19611b4b76" />
<img width="1662" height="759" alt="image" src="https://github.com/user-attachments/assets/bf3df7f9-6c2b-42a9-8875-c6b74971747d" />


## Project structure 
```
Green_Technology_Marketplace/
├── README.md
├── pom.xml OR build.gradle          # (if using Maven or Gradle)
├── .gitignore
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── pawarpresthi/greenmarket/      # replace with your base package
│       │           ├── controller/                # Servlets, controllers
│       │           ├── model/                     # POJOs / DTOs / entities
│       │           ├── dao/                       # DB access (JDBC/DAO classes)
│       │           ├── service/                   # Business logic
│       │           └── util/                      # Helpers, DB connection, constants
│       └── webapp/
│           ├── META-INF/
│           ├── WEB-INF/
│           │   ├── web.xml                        # servlet mappings, filters
│           │   └── lib/                           # optional: jars for Tomcat (if needed)
│           ├── views/                             # JSP pages (or put directly under webapp/)
│           │   ├── index.jsp
│           │   ├── login.jsp
│           │   ├── dashboard.jsp
│           │   └── fragments/                     # header/footer includes
│           └── assets/
│               ├── css/
│               │   └── styles.css
│               ├── js/
│               │   └── app.js
│               └── images/
├── sql/
│   ├── schema.sql                                # DB schema / sample data
│   └── seed.sql
├── config/                                       # optional config files (properties)
│   └── application.properties
├── lib/                                          # optional: 3rd-party jars if not using a build tool
├── scripts/                                      # helper scripts (start-db, deploy)
└── docs/                                         # design docs, ER diagrams, screenshots
```

## How to run (dev):
1.--- Create MySQL database and run `sql/schema.sql`.  
2.--- Configure DB connection in `config/application.properties` or `WEB-INF` context params.  
3.--- Build (if Maven): `mvn clean package` → deploy the generated WAR to Tomcat (e.g. Tomcat 11).  
4.--- Or run from IDE (IntelliJ): set up a Tomcat run configuration and use the project as a web application.  








