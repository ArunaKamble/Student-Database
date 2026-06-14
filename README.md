# Student Resume Management System

## Project Description

Student Resume Management System is a Java Swing-based application that allows users to upload resumes, extract candidate information, store records, search records, and display saved resume data.

The system supports PDF resume upload using Apache PDFBox and automatically extracts important details such as:

* Resume ID
* Name
* Email
* Phone Number
* Education
* Skills

---

## Technologies Used

* Java 21
* Swing GUI
* File Handling
* Apache PDFBox
* Eclipse IDE

---

## Features

### Upload Resume

* Upload PDF or text resumes.
* Extract resume content automatically.
* Parse Email, Phone Number, Education, and Skills.

### Save Resume

* Save extracted details into a file named `resumes.txt`.

### Search Resume

* Search candidate records using Resume ID.

### Display Resumes

* View all stored resumes from the database file.

---

## Project Structure

com.students

├── StudentApplet.java

├── StudentMain.java

└── resumes.txt

---

## Required Libraries

Apache PDFBox

Required JAR:

pdfbox-app-3.0.7.jar

Download from:

https://pdfbox.apache.org/download.cgi

---

## How to Run

### Step 1

Import the project into Eclipse.

### Step 2

Add PDFBox JAR file:

Right Click Project

Build Path

Configure Build Path

Libraries

Add External JARs

Select pdfbox-app-3.0.7.jar

### Step 3

Run:

StudentMain.java

as

Java Application

---

## Sample Output

Resume ID : 1

Name : Aruna Kamble

Email : [kamblearuna96@gmail.com](mailto:kamblearuna96@gmail.com)

Phone : 7204908162

Education : B.E Computer Science & Engineering

Skills : Java, SQL, HTML, CSS

---

## Future Enhancements

* MySQL Database Integration
* Update and Delete Resume
* Resume Ranking System
* Skill Matching
* Interview Recommendation System
* AI-Based Resume Analysis

---


