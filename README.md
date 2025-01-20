# Invoice_Generator.gothub.io

# Online Invoice Generator

A dynamic web application for creating, customizing, and managing invoices. This project integrates a user-friendly front-end with a robust Java Spring Boot backend to deliver a seamless experience for generating professional invoices.

---

## **Features**

### **Front-End**
- Built with **HTML**, **CSS**, and **AngularJS** for an interactive and responsive user interface.
- Provides options to select invoice types (e.g., Standard, Custom).
- Displays real-time invoice previews using an embedded `iframe`.
- Smooth navigation between pages using AngularJS routing.

### **Back-End**
- Developed using **Java Spring Boot** to handle RESTful API requests.
- Supports operations like:
  - Creating invoices.
  - Retrieving invoice details by ID.
  - Deleting invoices.
- API integration for dynamic PDF generation, ensuring real-time previews of invoices.
- Scalable architecture with clear separation of concerns (Controller, Service, and Model layers).

---

## **Technologies Used**

### **Front-End**
- HTML5, CSS3
- AngularJS
- JavaScript

### **Back-End**
- Java Spring Boot
- RESTful APIs
- Maven (for dependency management)

### **Tools**
- IDE: IntelliJ IDEA / Eclipse
- Version Control: Git
- Build Tool: Maven

---

## **Project Structure**
![image](https://github.com/user-attachments/assets/88695906-fbc3-478e-bf51-4be0e6ebc389)


### **Prerequisites**
1. Java Development Kit (JDK 17 or later)
2. Node.js (for AngularJS dependency management)
3. Maven (for managing backend dependencies)

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-invoice-generator.git
   cd online-invoice-generator
2. cd src/main/java/com/invoice/generator
3. mvn clean install
4. mvn spring-boot:run
Finally, open cd src/main/resources/static\index.html in browser
