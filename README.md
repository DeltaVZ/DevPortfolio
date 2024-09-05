# My Portfolio

Welcome to my portfolio repository! Here, you will find a curated selection of my personal projects, coding challenges completed for fun or professional purposes, and significant projects from my career. Each open-source project is hosted in its own GitHub repository, where you can explore detailed information and source code. For closed-source projects, you will find links providing additional context and details.

Please note that coding challenges are anonymized and only published several months after completion to ensure no company-specific information is exposed.

## About Me

I am **Software Engineer** with a **Master's Degree in Space and Astronautical Engineering** and with a **5 years experience in Software Engineering in the Space Sector**. I am passionate about Space and have extensive experience in Java, Python, Dart and Typescript. This portfolio includes projects that highlight my skills and accomplishments in software engineering.

## Open Source Projects

Below is a list of selected open source projects. Click on the project names to visit their respective repositories.

### 1. [Risk Estimation Challenge](https://github.com/DeltaVZ/RiskEstimationChallenge)
**Description**: The challenge provided some JNI functions and asked to create Java code so that risk estimations with problematic theta values in their risk trend are not suggested

**Technologies**: Java, Maven, MongoDB, TestNG, Mockito, Docker, Test Container, UML

**Highlights**:
- **Java and MongoDB API**: Use of Java coupled with MongoDB API
- **Unit and Integration testing**: Extensive code coverage thanks to TestNG, Mockito and Test Containers that create a containerized instance of MongoDB
- **UML**: UML diagrams produced via PUML

### 2. [power-profiles-enhancer](https://github.com/DeltaVZ/power-profiles-enhancer)
**Description**: Power Profiles Enhancer is a tool designed to enhance the capabilities of the power profiles daemon on Linux systems. By leveraging a custom Python script and configuration through INI files, this project adds additional functionality and optimizations, allowing users to better manage power consumption based on their specific needs.

**Technologies**: Python, Bash, venv, configparser, subprocess, Linux, systemd, power-profiles-daemon

**Highlights**:
- **Python**: Clean code written in Python with the use of libraries such as subprocess and configparser
- **Linux Service**: Runs as a Linux service for seamless integration and automatic application of enhancements.
- **Bash**: Includes a bash install script
- **Power Optimization**: Optimizes power consumption for different use cases, improving battery life or performance.
- **Custom Profiles**: Supports multiple customizable power profiles for various scenarios.
- **User-Friendly**: Simple to configure and use, suitable for all levels of Linux users.


### 3. [Web Crawler Challenge](https://github.com/DeltaVZ/web_crawler_challenge)
**Description**: The challenge asked to create a performant web crawler

**Technologies**: Python, pipenv, asyncio, aiohttp, beautifulsoup, mockito, html, UML

**Highlights**:
- **Python and Asyncio**: Use of Python coupled with the asyncio library to write concurrent code
- **Event Loop**: Demonstrates the use of asyncio's event loop to manage and schedule asynchronous tasks, ensuring smooth handling of concurrent operations
- **Asynchronous HTTP Requests**: Utilizes aiohttp to perform asynchronous HTTP requests, allowing the application to handle multiple requests concurrently without blocking, which is essential for high-performance applications
- **Efficient I/O Handling**: Shows how to efficiently manage I/O-bound operations, such as API calls and data fetching, by utilizing asynchronous features to avoid traditional threading or blocking calls.
- **HTML parsing**: Efficient HTML parsing using beautifulsoup4
- **Unit testing**: Extensive code coverage thanks to pytest and mockito
- **Highly configurable**: Extensive configuration is possible for different kinds of uses
- **UML**: UML diagrams produced via PUML


### 4. [Gamestop EU Scraper](https://github.com/DeltaVZ/gamestop-eu-scraper)
**Description**: This MIT project is a scraper for EU Gamestop websites. It can be configured to:

- Check if any product is in stock
- Check if any search page has any given keyword or if the obtained results are different from the expected ones
- Check for all product IDs in given ranges if they contain any given keywords

During a time when certain tech products were in high demand and sold out everywhere, creating a secondary market with exorbitant prices, this tool was developed to help individuals acquire these products at their original retail prices.

**Technologies**: Python, asyncio, aiohttp, beautifulsoup, html, telethon API, unittest, mockito

**Highlights**:
- **Python and Asyncio**: Use of Python coupled with the asyncio library to write performant concurrent code
- **Event Loop**: Demonstrates the use of asyncio's event loop to manage and schedule asynchronous tasks, ensuring smooth handling of concurrent operations
- **Asynchronous HTTP Requests**: Utilizes aiohttp to perform asynchronous HTTP requests, allowing the application to handle multiple requests concurrently without blocking, which is essential for high-performance applications
- **Efficient I/O Handling**: Shows how to efficiently manage I/O-bound operations, such as API calls and data fetching, by utilizing asynchronous features to avoid traditional threading or blocking calls.
- **HTML parsing**: Efficient HTML parsing using beautifulsoup4
- **Unit testing**: Extensive code coverage thanks to unittest and mockito
- **Highly configurable**: Extensive configuration is possible for different kinds of uses
- **Telethon API**: Use of Telethon API to notify users via Telegram messages when needed

### 5. [ISS Tracker](https://github.com/DeltaVZ/iss-tracker)
**Description**: This full-stack challenge involved creating an API to store the ISS location and daylight windows in a database, making this data available for client queries. The project also included a client application developed providing a map that shows the ISS location updated every 20 seconds and a list on the site showing the ISS daylight windows



**Technologies**: Python, Typescript, FastAPI, SlowApi, SQLAlchemy, asyncio, aiohttp, uvicorn, Nuxt3, mapbox, axios, pytest, pytest-mock, UML

**Highlights**:
- **Python and FastAPI**: Use of Python coupled with FastAPI to build a high-performance, modern API with automatic interactive documentation.
- **TypeScript and Nuxt3**: Developed a modern, server-side rendered application using Nuxt3, with TypeScript to ensure type safety and enhance development efficiency. This combination improved performance, code quality, and maintainability while providing a robust interface for interacting with the API.
- **SlowApi**: Integrated SlowApi to handle API rate limiting and throttle requests effectively.
- **SQLAlchemy**: Employed SQLAlchemy for ORM-based database interactions, enabling efficient and flexible data handling.
- **Uvicorn**: Deployed the application using uvicorn, an ASGI server, to handle asynchronous web requests efficiently.
- **Mapbox**: Integrated Mapbox in the frontend to provide interactive and customizable mapping solutions, enhancing the visualization of geospatial data.
- **Axios**: Employed Axios in the frontend for making HTTP requests, ensuring efficient and reliable data fetching from the backend API.
- **Unit testing**: Extensive code coverage thanks to pytest and pytest-mock
- **Configurable**: Configuration is possible for different kinds of uses, such as enabling and disabling the API rate limit
- **UML**: UML diagrams produced via PUML

## Individual Closed Source Projects

### 1. [Neurodieta](https://play.google.com/store/apps/details?id=com.drcuzzola.nutrizioneconsapevole.neurodieta&hl=en_US)
**Description**: A project that I worked on for a small client of which I'm the only developer that consists of:

- A RESTful web service written using Java Spring and deployed using tomcat on a CentOS machine
- An Admin GUI written in Typescript + Nuxt3: a GUI used by admins to accomplish control and configuration tasks, deployed on a machine only available on the local network of the client and accessible via Wireguard VPN
- An Android/iOS app written with Dart + Flutter that is to be used by customers and is available on both Play Store and Apple Store for modern Android and iOS devices

**How It Works**:
- The RESTful web service acts as the central hub, handling interactions and data management for both the Admin GUI and the mobile app. Additionally, it manages the sending of daily and weekly Telegram messages to an Admin channel.
- The Admin GUI allows administrators to manage user tasks and configurations securely.
- The mobile app delivers a user-friendly experience, with notifications enhancing user engagement and interaction.

A demo of the product is available only upon request.


**Technologies**: Dart, Flutter, Java, Spring, Tomcat, Nuxt3, Telegram API, Typescript, PostgreSQL, Android Studio, XCode, VSCode, Wireguard, Linux, Android, iOS, CentOS, SSL

**Highlights**:
- **Java+Spring**: Backend written in one of the most popular Java frameworks
- **PostgreSQL**: Extensive use of PostgreSQL for handling large amount of data for all customers
- **Tomcat**: Efficient deployment via tomcat
- **Dart+Flutter and Typescript+Nuxt3**: Use of Dart + Flutter and Typescript + Nuxt3 that demonstrates my adaptability to learn and work with new languages and frameworks in very little time
- **Android and iOS**: Proven knowledge of Android and iOS inner workings
- **Linux System Administration**: Proven experience in CentOS and Linux system administration
- **Telegram API**: Use of Telegram API to send daily and weekly reports to an admin channel
- **Integration testing**: Extensive flutter code coverage thanks to patrol 

### 2. [Eurobenzina](https://play.google.com/store/apps/details?id=com.spacedev.eurobenzina&hl=en_US)
**Description**: A personal projects initially for exclusive personal use that I decided to publish so that friends can easily download it. It helps the user to easily see the average daily fuel prices per region in Italy (Gasoline, diesel and LPG) and also find the most convenient gas stations around. It uses freely available data from the Fuel Price Observatory of the Ministry of Business and Made in Italy.

The app is freely available to download on both the Google Play Store and the Apple Store and a big update will be released at the end of 2024.


**Technologies**: Dart, Flutter, flutter_map, geolocator, google_mobile_ads

**Highlights**:
- **Dart+Flutter**: Use of Dart + Flutter, proving my experience in this framework
- **Flutter Map**: Proven experience in the use of Flutter Map and geolocation services
- **Google Mobile Ads**: Demonstrates my ability to integrate google mobile ads seamlessly in my mobile app

## Company Projects

### 1. [Pleniter Plan](https://www.cgi.com/en/solutions/pleniter)
**Description**: I was one of the lead developers of Pleniter Plan for almost 3 years. Pleniter Plan handles all of the regular and special task requirements for a mission system’s infrastructure, spacecraft platforms and payload. Produces consistent and conflict-free scheduling and payload process monitoring for multiple spacecraft, ground stations and control centers.


**Technologies**: Java, Ruby, MySQL, PostgreSQL, TestNG, JUnit, Mockito, Gitlab Pages

**Highlights**:
- **Java**: Considerable experience gained in this role
- **Ruby**: Used to write multiple scripts, especially for component tests
- **Gitlab Pages**: Set up and maintained the whole documentation infrastructure via Gitlab Pages
- **MySQL and PostgreSQL**: Gained considerable experience in the APIs for Java
- **Unit, Integration and Component tests**: I wrote unit tests with 90%+ coverage, as well as Integration and Component Tests that would test the interaction with external APIs (PostgreSQL) and different components of the Pleniter Suite.

### 2. [Aurora - Cloud Based Mission Control Software](https://www.dorbit.space/aurora)
**Description**: I was a developer of Aurora: a powerful cloud-based mission control software suite designed to control a single satellite or a complete constellation through a user-friendly, fully customizable control web interface.


**Technologies**: Python, unittest, Kotlin, Asyncio, Threading, FastAPI, Kubernetes, AWS (Amazon Web Services), Apache Kafka

**Highlights**:
- **Python and Kotlin**: Honed my skills in Python and learned Kotlin
- **Unit testing**: Gained considerable experience in Python unit testing using the unittest library
- **Asyncio and Threading**: I improved my skills in Asynchronous and Parallel programming,
- **FastAPI**: Developed one API based on FastAPI
- **Kubernetes and AWS**: Made use of Kubernetes and AWS on a daily basis
- **Apache Kafka**: Gained proficiency in event-driven architectures with substantial experience in designing and implementing scalable messaging systems using Apache Kafka

### 3. [Okapi:Aether, Okapi:Soteria and Okapi:Astrolabe](https://www.okapiorbits.space/)
**Description**: I am the lead developer of Okapi:Aether (Backend and API) and Backend developer of both Okapi:Soteria and Okapi:Astrolabe.

- **Okapi:Aether**: Offers Risk Prediction & Collision Avoidance services with unerring accuracy.
- **Okapi:Soteria**: Optimizes the design and ensures your a mission's compliance with all relevant space debris mitigation requirements.
- **Okapi:Astrolabe**: Streamlines collision avoidance cooperation between active satellites and minimize the requirement for constant oversight. The most efficient way to manage one or multiple satellites.


**Technologies**: Java, Python, Typescript, MongoDB, RabbitMQ, Docker, DevContainers, Mockito, Test Containers, TestNG, JUnit, pytest

**Highlights**:
- **Java and Python**: This role has advanced my Java and Python skills to a Senior level, reflecting extensive experience and expertise in both languages.
- **Typescript**: My skills in Typescript advanced to intermediate level thanks to the work on the API of Okapi:Aether
- **Unit and Integration Tests**: I applied Test Driven Development on every ticket I worked on. I mainly used TestNG and JUnit with Java and pytest with Python. I've used Mockito extensively, as well as Test Containers for integration tests in order to have containerized instances of both MongoDB and RabbitMQ for efficient integration testing
- **Docker and DevContainers**: I created DevContainers for both Okapi:Aether and Okapi:Soteria, thus allowing all developers to have the same development environment, configuration and plug-ins and to extremely reduce the time to set up the projects from scratch
- **MongoDB**: Gained considerable experience in NoSQL and MongoDB in particular, especially with its Java and Javascript APIs.
- **RabbitMQ**: Gained proficiency in event-driven architectures with substantial experience in designing and implementing scalable messaging systems using RabbitMQ


## Contact

Feel free to reach out if you have any questions or if you’d like to discuss potential opportunities:
- **Email**: gio.spacedev@pm.me
- **GitHub**: https://github.com/DeltaVZ/

Thank you for visiting my portfolio!

---

*This README was last updated on 2024.09.05.*
