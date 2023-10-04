# Airbnb Clone Versions 📯

This repository contains different versions of the Airbnb Clone project, showcasing progressive development and various features.

## Project Overview

The Airbnb Clone project is a web application that replicates the functionality of Airbnb. It is developed as a learning project at ALX Africa to explore different web development concepts and technologies.

# Version 1: The Console

[GitHub Repository](https://github.com/Laban254/AirBnB_clone)

### Description
Version 1 marks the inception of the Airbnb Clone project, where the focus is on creating a command-line interface (CLI) to manage objects for the Airbnb (HBnB) website. This CLI serves as the foundation for building the entire project.

In Version 1, key features include:
- **Object Management:** The CLI enables the creation of new objects (e.g., users, places), retrieval of objects from files or a database, and performing various operations on objects (e.g., counting, computing statistics).
- **Attribute Updates:** Users can update attributes of objects, enhancing the flexibility of managing data.
- **Object Deletion:** The CLI allows for the removal of objects, supporting data cleanup and maintenance.

### Web static
#### Description
This phase of the project focuses on the development of static web pages using HTML and CSS. The `web_static` folder contains HTML files and CSS styles for the project's static pages. These static pages lay the visual groundwork for the project.

The `web_static` folder structure includes:
- **Images:** This folder holds icons used on the website, such as logos and room icons.
- **Styles:** CSS stylesheets are organized into categories (e.g., common, footer, header) for effective styling of different page components. The highest-numbered style files are most relevant to the finished product.

[link to the repo](https://github.com/Laban254/AirBnB_clone/tree/main/web_static)

# Version 2: User Interface Enhancement

### Overview
Version 2 of the Airbnb Clone project focuses on enhancing the user interface (UI) to improve aesthetics, styling, and responsiveness. This iteration aims to provide a visually appealing and user-friendly interface while ensuring compatibility across various devices and screen sizes.

### Key Enhancements
- **Visual Appeal:** In this version, significant efforts are invested in refining the project's UI. CSS styling is utilized to enhance the visual appeal of the web application, creating a more attractive user experience.

- **Responsiveness:** Version 2 places a strong emphasis on responsiveness. The UI is designed to adapt seamlessly to different devices and screen sizes. This responsiveness ensures an optimal viewing experience, regardless of the user's choice of device, enhancing accessibility and usability.

### Relevant Links
- [GitHub Repository - AirBnB_clone_v2](https://github.com/Laban254/AirBnB_clone_v2)
- ![Version 2 Screenshot](https://github.com/Laban254/AirBNB_Clone-versions/assets/64686919/fae608bd-2269-40e1-9a37-0b4f307dc5dc)

### Background Context
- **BNB_ENV:** This parameter defines the running environment and can be set to "dev" or "test," with "production" planned for the future.

- **HBNB_MYSQL_USER:** This is the username for MySQL, a vital component of the project.

- **HBNB_MYSQL_PWD:** The password associated with the MySQL user.

- **HBNB_MYSQL_HOST:** The hostname of the MySQL server where project data is stored.

- **HBNB_MYSQL_DB:** The name of the database in MySQL used for the project.

- **HBNB_TYPE_STORAGE:** This parameter determines the type of storage used, with options including "file" (utilizing FileStorage) and "db" (employing DBStorage).

### Database Schema
![AirBNB-SCHEMA](https://github.com/Laban254/AirBNB_Clone-versions/assets/64686919/f5c3581f-5a16-4869-a6d7-caad4fd35eea)

### Project Context
Version 2 represents a significant step forward in the Airbnb Clone project, improving the project's UI and making it more appealing to users. The enhanced UI sets the stage for further development, creating a solid foundation for the project's future.

### Deployment of Static Content
### Background
The deployment of static content is a critical aspect of project development. This phase ensures that static web pages, styles, and assets are delivered efficiently to end-users. In this context, project deployment involves making the project accessible to the public, utilizing two web servers and one load balancer.

### Deployment Methodology
The deployment process leverages Fabric, a Python library and command-line tool for streamlining SSH-based application deployment and system administration tasks. Fabric simplifies the execution of local or remote shell commands, including file transfers and other essential operations.

#### Key Steps in Deployment
1. **Cloning Repository:** Clone the project's GitHub repository to your local machine or server.

2. **Environment Configuration:** Set environment variables such as `BNB_ENV`, `HBNB_MYSQL_USER`, `HBNB_MYSQL_PWD`, `HBNB_MYSQL_HOST`, `HBNB_MYSQL_DB`, and `HBNB_TYPE_STORAGE` to configure the project environment.

3. **Deployment Strategy:** Determine the deployment strategy that aligns with your project goals, ensuring that static content is efficiently distributed to end-users.

#### Web Framework (web-flask)
- [GitHub Repository - web-flask](https://github.com/Laban254/AirBnB_clone_v2/tree/master/web_flask)

![web-flask-output](https://github.com/Laban254/AirBNB_Clone-versions/assets/64686919/de68b24f-1c70-428f-847d-8877d3c9cd0a)


# AirBnB_clone_v3
[AirBnB_clone_v3 GitHub Repository](https://github.com/FrankieVexx/AirBnB_clone_v3)

AirBnB_clone_v3 is an advanced version of the AirBnB clone project that focuses on building a powerful RESTful API. It serves as the backend for managing various functionalities and data associated with property rentals, similar to the AirBnB website.

This version includes features such as user authentication, property management, booking management, and more. The RESTful API is designed to handle requests from frontend applications, mobile apps, and other clients, making it a versatile and robust backend solution for property rental platforms.

## Key Features:
- User Authentication: Secure user registration and login functionality.
- Property Management: Create, update, and delete property listings.
- Booking Management: Handle property booking requests and reservations.
- Search and Filtering: Implement advanced search and filtering options for property listings.
- Robust API: A well-documented RESTful API with clear endpoints and data structures.
- Scalability: Designed to handle a large number of users and property listings.

![RESTful API Screenshot](https://github.com/Laban254/AirBNB_Clone-versions/assets/64686919/b63fb2cd-e1bf-4e78-b645-3d54f31b4bcd)

# AirBnB_clone_v4
[AirBnB_clone_v4 GitHub Repository](https://github.com/Laban254/AirBnB_clone_v4)

AirBnB_clone_v4 represents the evolution of the project into a web dynamic interface. This version combines the power of a backend RESTful API (as seen in AirBnB_clone_v3) with a responsive and interactive frontend. It aims to provide users with a seamless and engaging experience when exploring and booking rental properties.

### Key Features:
- Web Dynamic Interface: An intuitive and visually appealing web interface for users to search, view, and book rental properties.
- Integration with RESTful API: Seamlessly connects to the AirBnB_clone_v3 API to fetch property data and manage bookings.
- User-Friendly Experience: Responsive design ensures optimal viewing on various devices and screen sizes.
- Interactive Elements: Features like property sliders, real-time availability updates, and user reviews enhance user engagement.
- Modern Technologies: Utilizes HTML5, CSS3, JavaScript, and Flask for a contemporary web experience.

![Web Dynamic Interface Screenshot](https://github.com/Laban254/AirBNB_Clone-versions/assets/64686919/58e32eec-aebd-4b4b-bdd9-93da00566130)

# Contact Information
For any questions or inquiries related to these project versions, please don't hesitate to reach out:

- **Email:** labanrotich6544@gmail.com
- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/laban-rotich/)
- **Portfolio:** [My Portfolio](https://labankibet.netlify.app/)


