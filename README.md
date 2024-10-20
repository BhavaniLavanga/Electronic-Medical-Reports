
---

# Electronic-Medical-Reports

## Project Overview
This project explores the implementation and benefits of Electronic Medical Records (EMRs) in healthcare settings. It examines the limitations of paper-based medical records and the advantages of digital EMRs. The project covers technical considerations, such as data storage, interoperability, security, and privacy, as well as different technologies used for EMR creation and management. 

The benefits of EMRs for healthcare providers, patients, and researchers are discussed, including:
- Improved diagnosis
- Coordinated care
- Patient empowerment
- Research insights

Challenges such as data security, interoperability, user adoption, and ethics are also addressed, along with potential strategies for mitigating them. Overall, the project highlights the transformative potential of EMRs in enhancing healthcare delivery and calls for collaboration among stakeholders to ensure successful implementation.

## Technology Stack
- **Frontend:** Java Swing
- **Database:** Oracle Database (SQL)

### 1. Architecture

#### 1.1 Java Swing
Java Swing is a part of Java Foundation Classes (JFC) that is used to create window-based applications. It is built on top of the Abstract Windowing Toolkit (AWT) API and is entirely written in Java. Java Swing provides platform-independent and lightweight components. The `javax.swing` package provides classes for the Java Swing API, such as:
- `JButton`
- `JTextField`
- `JTextArea`
- `JCheckbox`
- `JOptionPane`

These components are utilized to perform various functions in our project.

#### 1.2 SQL
Structured Query Language (SQL) is a database query language used for storing and managing data in Relational Database Management Systems (RDBMS). SQL was the first commercial language introduced for E.F. Codd's Relational model of the database. Today, almost all RDBMS (MySQL, Oracle, Informix, Sybase, MS Access) use SQL as the standard database query language. SQL is used to perform all types of data operations in RDBMS. We have used Oracle Database to implement our project.

### 2. Software Requirements
The following software is required for our project:
- **Java SE version 15.0.2**
- **Oracle Database 11g (SQLPLUS 11.2.0.2.0)**

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/BhavaniLavanga/Electronic-Medical-Reports.git
   cd Electronic-Medical-Reports
   ```
   
2. **Setup Oracle Database:**
   - Install Oracle Database 11g.
   - Configure your database instance and create the necessary tables for EMR.

3. **Compile and run the Java Swing application:**
   - Make sure you have Java SE installed.
   - Compile the Java files using the command:
     ```bash
     javac -d bin src/*.java
     ```
   - Run the application:
     ```bash
     java -cp bin MainClass
     ```

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions for improvements or if you encounter any problems.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to the developers of Java Swing and SQL for providing the tools necessary to implement this project.

---

