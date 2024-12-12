# Instagram Database Project

## Description
This repository contains the SQL script `Instagram.sql` to create and manage a relational database inspired by Instagram. It includes tables, relationships, and possibly queries to handle core functionalities like user management, posts, likes, comments, and more.

## Features
- User management: Users, their profiles, and authentication.
- Post handling: Create, edit, delete, and retrieve posts.
- Engagements: Likes and comments functionality.
- Relationships: Follow/unfollow system.
- Data structure: Efficient table relationships and indexing.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PAVITRA1919/Instagram_database_clone.git
   ```

2. Set up a MySQL database server on your machine or use a remote database service.

3. Open the SQL script file `Instagram.sql` in a database client (e.g., MySQL Workbench) or a command-line interface.

4. Run the script to create the database and its tables:
   ```sql
   SOURCE /path/to/Instagram.sql;
   ```

5. Verify the database structure and relationships.

## Usage

1. Connect your application to the database using your preferred programming language (e.g., Python, Node.js, Java).

2. Use the database to:
   - Add, update, or retrieve user data.
   - Handle user posts and interactions.
   - Implement follow/unfollow functionality.

3. Extend the SQL script as needed to accommodate additional features.

## Database Design
The database includes the following key tables (assumptions based on functionality):
- `users`: Stores user details such as username, email, password, and profile information.
- `posts`: Contains details of user posts, including captions, media, timestamps, etc.
- `likes`: Tracks which users liked which posts.
- `comments`: Stores comments made on posts.
- `followers`: Tracks user follow/unfollow relationships.





