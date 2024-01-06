

# Database System Consolidation Project

This project involves the consolidation of three small overlapping database systems to create a unified database system that supports various functions related to teaching, registration, and student records.

## Table of Contents
- [Description](#description)
- [Getting Started](#getting-started)
- [Database Schema](#database-schema)
- [Installation](#installation)

## Description

This project aims to consolidate the functionality of three small overlapping database systems into a single, integrated database system. The resulting system will support various functions such as instructor assignment and evaluation, course registration, transcript generation, and more.

## Getting Started

To get started with this project, you will need to set up the database system using the provided SQL script and sample data. Follow the installation instructions below to create the necessary tables and insert sample data.

## Database Schema

The database schema for this project includes the following tables:

1. `Professors`: Attributes include SSN (Primary Key), Name, and other relevant information.
2. `Students`: Attributes include SSN (Primary Key), Name, Rank, and other relevant information.
3. `Classes`: Attributes include Department Name, Course Number, Prerequisite Class, and other relevant information.
4. `Sections`: Attributes include Section Number, Class Department, Class Course Number, and other relevant information.
5. `Instructors`: Attributes include SSN (Primary Key), Class Department, Class Course Number, and other relevant information.
6. `Grades`: Attributes include Student SSN, Section Section Number, and Grade.
7. `Waitlist`: Attributes include Student SSN, Section Section Number, and Rank.
8. `TeamRatings`: Attributes include Section Section Number and Rating.

Additional constraints, foreign keys, and not null constraints are applied as needed to ensure data integrity.

## Installation

1. Clone this repository to your local machine.
2. Execute the SQL script on your database system (e.g., Oracle) to create the necessary tables and constraints.


