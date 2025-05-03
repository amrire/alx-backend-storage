# alx-backend-storage

This repository contains projects and exercises focused on backend storage systems, including MySQL, NoSQL (MongoDB), and Redis. It is part of the ALX Backend curriculum and aims to provide hands-on experience with various storage technologies.

## Directory Structure

### [0x00-MySQL_Advanced](0x00-MySQL_Advanced/README.md)
This directory contains advanced MySQL tasks, including creating tables, stored procedures, triggers, and views. It focuses on optimizing database queries and implementing complex database operations.

Key Highlights:
- Creating and managing indexes.
- Writing stored procedures and triggers.
- Designing views for specific use cases.

### [0x01-NoSQL](0x01-NoSQL/README.md)
This directory focuses on NoSQL databases, specifically MongoDB. It includes tasks to perform CRUD operations, write queries, and analyze data stored in MongoDB collections.

Key Highlights:
- Listing databases and collections.
- Inserting, updating, and deleting documents.
- Aggregation and query optimization.
- Writing Python scripts to interact with MongoDB using `pymongo`.

### [0x02-redis_basic](0x02-redis_basic/README.md)
This directory introduces Redis, a fast, in-memory key-value store. It includes tasks to implement caching, track function calls, and manage data using Redis.

Key Highlights:
- Implementing caching for HTTP requests.
- Tracking function call history and counts.
- Storing and retrieving data using Redis.

## Requirements

- Python 3.8 or higher
- MongoDB 4.4 or higher
- Redis 5.0 or higher
- MySQL 5.7 or higher
- Required Python packages: `pymongo`, `redis`, `requests`

## Installation

1. **Set up Python Environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

2. **Install and Configure Databases**
   - Follow the official installation guides for [MySQL](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/), [MongoDB](https://www.mongodb.com/docs/manual/installation/), and [Redis](https://redis.io/docs/getting-started/installation/).

## Usage

Each directory contains specific tasks and scripts. Navigate to the respective directory and follow the instructions in the `README.md` file.

Example:
```bash
cd 0x01-NoSQL
python 8-all.py
```

## Learning Objectives

By working through this repository, you will:
- Gain proficiency in MySQL, MongoDB, and Redis.
- Understand the differences between SQL and NoSQL databases.
- Learn to optimize database queries and implement advanced database features.
- Use Python to interact with databases programmatically.

## Author

This repository is part of the ALX Backend curriculum.
