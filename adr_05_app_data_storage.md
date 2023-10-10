# Data storage 
### Status
- *Decision Made*
### Context
- *The app needs to store user account information, order history, and restaurant menu data.*
### Decision
- *We will use a combination of relational databases (e.g., PostgreSQL) for structured data and NoSQL databases (e.g., MongoDB) for semi-structured data.*
### Consequences
- *Relational databases are suitable for managing user account data and order history.*
- *NoSQL databases are flexible for handling menu data, which may vary between restaurants.*
- *Data synchronization between the app and restaurant inventory systems will require robust APIs and data transformation processes.*
