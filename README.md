# Smart Event Ticket Booking System

A Java console-based Smart Event Ticket Booking System that simplifies customer registration, event management, ticket booking, booking cancellation, and reservation tracking. Built using Core Java, JDBC, and MySQL, the project demonstrates Object-Oriented Programming, database connectivity, SQL operations, and modular application design.

## Features :

- Customer Registration
- View Available Events
- Event Management (Admin)
- Admin Login Authentication
- Book Event Tickets
- View Customer Bookings
- Cancel Ticket Bookings
- Automatic Ticket Availability Update
- Booking Amount Calculation
- MySQL Database Integration
- Exception Handling
- Menu-Driven Console Interface

## Technologies Used :

- Core Java (Java 17)
- JDBC (Java Database Connectivity)
- MySQL
- Maven
- Object-Oriented Programming (OOP)
- DAO (Data Access Object) Pattern
- Eclipse IDE / VS Code

## Project Structure :

```text
Smart-Event-Ticket-Booking-System/
│
├── src/
│   └── com/
│       └── eventbooking/
│           ├── Main.java
│           ├── Customer.java
│           ├── CustomerDAO.java
│           ├── Event.java
│           ├── EventDAO.java
│           ├── BookingDAO.java
│           └── DBConnection.java
│
├── pom.xml
├── README.md
└── .gitignore
```

## How to Run :

1. Clone the repository.
2. Install Java 17 and Maven.
3. Install MySQL and create the required database and tables.
4. Configure your MySQL username and password in `DBConnection.java`.
5. Open the project in VS Code or IntelliJ IDEA.
6. Run the following Maven command:

```bash
mvn compile exec:java -Dexec.mainClass=com.eventbooking.Main
```

7. Follow the menu options displayed in the console.

## Admin Login :

- Username: `admin`
- Password: `admin123`

## Future Enhancements :

- Spring Boot Integration
- Web-Based User Interface
- Online Payment Gateway Integration
- Email Booking Confirmation
- User Login and Authentication
- Event Search and Filtering
- Booking History and Reports

## 📸 Screenshots

### Main Menu

### Customer Registration

### View Available Events

### Book Event Tickets

### View My Bookings

### Cancel Booking

### Admin Login

### Add New Event

### Exit

## Author :

**Praveen Galanki**

B. Tech – Electronics and Communication Engineering

Full Stack Java Developer

---
