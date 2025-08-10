# PongaMQ LISTEN/NOTIFY Message Queue Monitor

### Overview
This Golang application automates the creation of a dedicated schema in a PostgreSQL database to manage and monitor events using the `LISTEN/NOTIFY` mechanism, simulating a message queue behavior.  
The application creates all required tables, functions, and triggers to store messages sent through PostgreSQL channels, enabling complete tracking and auditing of all events.

### Features
- 📦 Automatically creates a dedicated schema for event storage.
- ⚙️ Creates PostgreSQL functions for use in triggers.
- 🛠️ Stores all triggered events in the control schema.
- 🔍 Allows monitoring and auditing of all sent messages.
- 📊 Works like a message queue directly inside PostgreSQL.

### Requirements
- Golang
- PostgreSQL
