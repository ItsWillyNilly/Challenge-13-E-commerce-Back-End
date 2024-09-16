# Challenge-13-E-commerce-Back-End
This is an exployee tracker application that utilizes Express.js, File System(fs) node module, Postgres and databases.

## Description
This is an employee tracker that lets users view and manage an employee's role, salary and department. This program ustilizes a SQL database to store information. When the program is run, the user is prompted with a menu where they can select to view employees, update an employee, and add a role, employee or department.

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Technologies Used
**Node.js** <br>
**dotenv**<br>
**Express.js**<br>
**Insomnia**<br>
**PostgreSQL**<br>
**Sequelize**

## Installation Instructions
**Clone the repository**
```bash
git clone git@github.com:ItsWillyNilly/Challenge-13-E-commerce-Back-End.git
```

**Navigate to the project directory**
<br>EXAMPLE:
```
cd /Users/williamlee/bootcamp/challenge-13/Challenge-13-E-commerce-Back-End
```
**Install the Node package**
```bash
npm init -y
```

**Install dependencies**
```bash
npm install
```

**Create a `.env` file**
```bash EXAMPLE: <br>
DB_NAME='db_name'
DB_USER='user'
DB_PASSWORD='pass'
```

**Create and seed the database**
```bash
psql -U postgres
\i Develop/db/schema.sql
node seeds/index.js
```

**Run the program**
```bash
node server.js
```

**Utilize Insomnia**
After you can use Insomnia to test the functionality of the routes.

## Program Demonstration
<img src="assets/videos/Untitled Video September 16, 2024 3_39 PM.gif">
Video Link:<br> https://drive.google.com/file/d/1CmiCWo1_jqPjOys-1YSH0QCRisZQq14H/view?usp=sharing

## GitHub Repo Link
https://github.com/ItsWillyNilly/Challenge-13-E-commerce-Back-End