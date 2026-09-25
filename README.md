geospatial-civic-db
MySQL-based geospatial database for connecting citizens and public management through location-based data on urban issues, services, and infrastructure.

🌎 Geospatial Civic Database

A geospatial database project designed to organize and connect **citizen demands, geographic data, and public management**.

The project explores how spatial data can be used to better understand local public issues and support the interaction between citizens and municipal administration.

📌 About the Project

Public issues are strongly connected to location.

Infrastructure problems occur on specific streets. Public transportation affects particular routes and neighborhoods. Health services serve geographic areas. Municipal projects and public actions also take place within defined locations.

Based on this idea, the **Geospatial Civic Database** aims to structure public information using both **relational and geospatial data**.

The project was initially conceived in an academic context involving municipal public management and citizen participation, with the goal of creating a database capable of registering, locating, classifying, and monitoring public demands.

🎯 Objectives

The database is designed to support the management of information related to areas such as:

- 🏗️ Public infrastructure
- 🚌 Transportation and urban mobility
- 🏥 Public health
- 🛣️ Roads and streets
- 🏘️ Neighborhood issues
- 🏛️ Municipal management
- 👥 Citizen reports and participation

The central idea is to connect:

Citizen → Demand → Location → Public Management → Action

This structure allows reported problems to become organized and geographically referenced data.

🗺️ Why Geospatial Data?

Location is one of the main components of the project.

In addition to conventional relational data, the database uses spatial information to represent real-world geographic elements.

Examples include:

| Geometry | Application |
| POINT | Reports, occurrences and specific locations |
| LINESTRING | Roads, streets and transportation routes |
| POLYGON | Neighborhoods, municipalities and geographic areas |

This makes it possible to perform spatial analysis and understand not only **what** is happening, but also **where** it is happening.

🗃️ Database Model

The database model includes entities related to territorial organization, infrastructure, citizen participation and public management.

Some of the main entities include:

- State
- Municipality
- Neighborhood
- Location
- Road
- Citizen
- Issue Report
- Infrastructure Issue
- Issue Category
- Public Administration
- Public Manager
- Infrastructure Action
- Project
- Project Stage
- Company
- Professional

The Entity-Relationship Model defines the entities, attributes, relationships and cardinalities required to represent the system.

🔎 Geospatial Analysis

The database architecture is intended to support spatial queries such as:

- Finding public issues within a specific neighborhood;
- Identifying reports near a road or geographic point;
- Analyzing the distribution of issues across a municipality;
- Identifying areas with a high concentration of reports;
- Connecting infrastructure projects with affected geographic areas;
- Comparing different categories of public issues by location.

🛠️ Technologies

- MySQL
- SQL
- Geospatial Databases
- Entity-Relationship Modeling
- GitHub
- Draw.io 

📂 Repository Structure

```
geospatial-civic-db/
│
├── README.md
│
├── docs/
│   └── minimundo.docx
│
├── diagrams/
│   └── geospatial-civic-model.drawio
│
└── sql/
    └── schema.sql
```

🎓 Academic Context

This project was initially developed as part of a Geospatial Database course and is being expanded as a portfolio project focused on database modeling, spatial data and civic information systems.
