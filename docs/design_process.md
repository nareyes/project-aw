# Database/Datawarehouse Design Process

<br>

## High-Level Design Overview
- Requirements Gathering: Understanding the business needs and data requirements for the database or data warehouse.
- Conceptual Design: Developing a high-level design that outlines the entities, attributes, and relationships between them.
- Logical Design: Creating a detailed representation of the database or data warehouse, including data types, constraints, and relationships.
- Physical Design: Specifying the hardware and software requirements, data storage options, and performance considerations.
- Data Modeling: Creating a dimensional data model that organizes data into facts and dimensions for efficient querying and reporting.

<br>

# Detailed Design Steps

<br>

## Define Mission Statement and Mission Objectives
- The mission statement defines the purpose of the database
- The mission objectives defines the tasks performed by users against the database

## Analyze Current Database
- Identify requirements by reviewing how the organization currently collects and presents data
- *Not applicable to this project*

## Create Data Structures
- Establish tables by identifying subjects
- Associate each table with fields the represent distinct characteristics of the tables subject
- Designate particular field(s) as the primary key
    - Primary and Composite Keys

## Determine and Establish Table Relationships
- Identify relationship and establish logical relationships
    - Primary/Foreign Keys
    - Linking Tables

## Determine and Define Business Rules
- Identify constraints that must be imposed on the data
- Declare these constraints as business rules 
- Establish various levels of data integrity based on these business rules

## Determine and Establish Views
- Identify which view will be appropriate for end-users
- Define each view using appropriate tables and fields
- Define criteria for views
- Establish views based on business rules

## Review Data Integrity
- Ensure tables meet design criteria
- Review field specifications
- Test validity of relationships
- Review and confirm business rules

## Determine and Establish Data Model (Data Warehouse Design)
- Organize data into facts and dimensions