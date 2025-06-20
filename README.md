Collecting workspace informationFiltering to most relevant information```md
# HighLife Hotel Management System

<div align="center">
<strong><p>Desktop Application to Manage Reservations and Guest Check-in/Check-Out Using JavaFX and SQL Database with Hibernate ORM.</p></strong>
</div>

---

## Features

- Manage hotel guests and reservations
- Check-in and check-out functionality
- Room management (types, capacity, availability)
- User authentication with admin and regular user roles
- Data persistence using MySQL and Hibernate ORM
- JavaFX-based modern desktop UI

## Requirements

1. [Oracle JDK 8](https://www.oracle.com/java/technologies/javase/javase8u211-later-archive-downloads.html)
    - [Download and install Tutorial](https://youtu.be/XsdvQD_SDvw)
2. [XAMPP](https://www.apachefriends.org/index.html) for MySQL server
    - [Tutorial: How To Install](https://youtu.be/N43oVPkrTg8)

## Getting Started

### 1. Database Setup

- Start `Apache` & `MySQL` services from the XAMPP control panel.
- Import the provided [`hotel.sql`](hotel.sql) file into your MySQL server.
    - [How to Import .sql file to Database](https://youtu.be/GHSis3KwnkM)

### 2. Build and Run

- Open the project in NetBeans or any compatible IDE.
- Build the project using the provided [build.xml](build.xml) Ant script.
- Run the application using the main class: [`src/project/Project.java`](src/project/Project.java).

### 3. Configuration

- Database connection settings are defined in [`hibernate.cfg.xml`](src/hibernate.cfg.xml).
- Ensure your MySQL server is running and the credentials match those in the configuration file.

### 4. Login Details

Use one of the following credentials to log in:

| Username  | Password |
|-----------|----------|
| mugu      | 1994     |
| thanees   | 3333     |
| veytri    | 9991     |
| bryon     | 2002     |

> Additional users can be found in the `user` table in the database.

## Project Structure

```
.
├── build.xml
├── hotel.sql
├── manifest.mf
├── README.md
├── lib/                # External libraries (JARs)
├── nbproject/          # NetBeans project files
├── src/                # Source code (Java, resources, hibernate.cfg.xml)
└── build/              # Build output (classes, resources)
```

## Libraries Used

- JavaFX
- Hibernate ORM
- MySQL Connector/J
- JFoenix, FontAwesomeFX, Charm Glisten

## Screenshots

Screenshots are available in the [`screenshots/`](screenshots/) directory.

## License

This project is for educational purposes. Please refer to individual library licenses for third-party dependencies.

