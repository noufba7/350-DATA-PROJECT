# CS350 - Database Project

### Important Notes

1. **Using Git:** If you prefer to use Git, that is completely fine and may make managing your changes easier. However, since not everyone is familiar with Git, we will mainly use the GitHub website to upload and manage our files. Installing Git is optional.

2. **Main Branch:** The `main` branch will contain the final and approved version of our project. We will create a separate branch for ongoing work so everyone can contribute without affecting the main project. Once the work is reviewed and completed, we can merge it into `main`.

## 🐾 PawCare Management System

**Course:** CS350 - Introduction to Databases  
**Project:** Database Design and Implementation  
**Platform:** GitHub  
**Database:** MySQL

---

## 1. Project Overview

PawCare Management System is a database project designed for a veterinary clinic.

The goal is to create a relational database that organizes information about pet owners, pets, veterinarians, appointments, medicines, and prescriptions.

This repository is our shared workspace for storing project files, tracking progress, and collaborating as a team.

## 3. Project Requirements

The project is divided into eight parts:

| Part | Task | Description |
|---|---|---|
| A | Entities, Attributes, and Keys | Identify database entities and their attributes |
| B | Relationships and Cardinalities | Define how entities are connected |
| C | ERD Design | Create the Entity-Relationship Diagram |
| D | Schemas Before Normalization | Convert the ERD into relational schemas |
| E | Schemas After Normalization | Apply 1NF, 2NF, and 3NF |
| F | Create SQL Tables | Write SQL statements to create database tables |
| G | Populate Tables | Insert sample data into the database |
| H | Sample Queries | Execute SQL queries and document results |

**Important:** Always follow the official course project instructions for detailed requirements and final submission.

## 4. Task Distribution

| Member | Assigned Parts | Responsibilities |
|---|---|---|
| Member 1 | A & B | Entities, attributes, keys, and relationships |
| Member 2 | C & D | ERD design and schemas before normalization |
| Member 3 | E & F | Normalization and SQL table creation |
| Member 4 | G & H | Sample data and SQL queries |

Each member is responsible for completing and uploading their assigned work.

## 5. Tools Required

Before starting, prepare the following:

- **GitHub Account:** To access and update the shared repository.
- **Web Browser:** To upload and manage files on GitHub.
- **MySQL Workbench:** To create tables and execute SQL queries.
- **Microsoft Word or Google Docs:** To prepare documentation.
- **ERD Tool:** To create the database diagram.

### Do We Need to Install Git?

**No.**

We will use the GitHub website directly.

You do not need to:

- Install Git.
- Use Git Bash.
- Write Git commands.
- Use the terminal.
- Install GitHub Desktop.

All file uploads and updates can be done through the GitHub website.

## 6. Getting Started with GitHub

### Step 1: Create a GitHub Account

1. Visit https://github.com
2. Click **Sign up**.
3. Create your account.
4. Verify your email address.
5. Share your GitHub username with the team leader.

### Step 2: Accept the Repository Invitation

The team leader will invite you to the project repository.

1. Open your GitHub invitation.
2. Click **Accept invitation**.
3. Open the shared project repository.

You can now access the project files.

### Step 3: Download the Project

1. Open the GitHub repository.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the ZIP file on your computer.
5. Open the extracted project folder.

You can now work on the files locally.

**Note:** Downloading a ZIP creates a local copy. Your changes will not automatically appear on GitHub.

## 7. How to Work on Your Assigned Task

Each team member should follow these steps:

1. Check your assigned project parts.
2. Open the downloaded project folder.
3. Create or open the files related to your task.
4. Complete your work using the appropriate software.
5. Save your files.
6. Review your work before uploading.
7. Upload your completed files to GitHub.

### Example

If you are responsible for Parts E and F:

1. Prepare the normalized relational schemas.
2. Write the SQL CREATE TABLE statements.
3. Test the SQL statements in MySQL Workbench.
4. Save the SQL file.
5. Upload the file to the correct GitHub folder.

## 8. How to Upload Files to GitHub

### Uploading a New File

1. Open the project repository on GitHub.
2. Navigate to the correct folder.
3. Click **Add file**.
4. Select **Upload files**.
5. Choose your file from your computer.
6. Add a short description of your changes.
7. Select **Commit changes**.

Your file will now be available in the repository.

### Updating an Existing File

For files such as Word documents, diagrams, or SQL scripts:

1. Download the latest version from GitHub.
2. Open and edit the file on your computer.
3. Save your changes.
4. Return to the correct folder on GitHub.
5. Select **Add file → Upload files**.
6. Upload the updated file with the same name.
7. Review the changes and commit them.

**Important:** Make sure nobody else is editing the same file before replacing it.

For small text changes, GitHub also allows you to edit supported text files directly in the browser.

## 9. Project Folder Structure

```text
CS350-DATA-PROJECT/
│
├── README.md
│
├── Documentation/
│   ├── Part-A-Entities.docx
│   ├── Part-B-Relationships.docx
│   ├── Part-D-Schemas-Before.docx
│   └── Part-E-Normalization.docx
│
├── ERD/
│   └── PawCare-ERD.png
│
├── SQL-Scripts/
│   ├── Create-Tables.sql
│   ├── Insert-Data.sql
│   └── Queries.sql
│
└── Results/
    └── Query-Screenshots/
```

This is our proposed folder structure. Files can be adjusted based on the official project requirements.

## 10. Team Collaboration Rules

To keep the project organized, everyone should follow these rules:

1. Work only on your assigned tasks unless the team agrees otherwise.
2. Use clear and descriptive file names.
3. Upload your latest completed work.
4. Do not delete another member's files.
5. Do not overwrite another member's changes without checking.
6. Inform the team after uploading or updating files.
7. Always download the latest version before editing shared files.
8. Keep the project files organized in their correct folders.

### Recommended Commit Messages

When uploading files, use short descriptions such as:

- `Add Part A - Entities and Attributes`
- `Complete Part C - ERD`
- `Update Normalization`
- `Add SQL Create Tables`
- `Insert Sample Data`
- `Complete SQL Queries`

## 11. How to Check Project Progress

We can use GitHub to review the team's work.

### Files

Check which project files have been uploaded.

### Commits

Open the repository's commit history to see when files were changed and who uploaded them.

### Issues (Optional)

GitHub Issues can be used to track tasks.

Examples:

- Complete ERD
- Review Normalization
- Test SQL Tables
- Verify Sample Queries
- Prepare Final Submission

## 12. Final Project Checklist

Before submitting the project, verify the following:

- [ ] Part A - Entities, Attributes, and Keys
- [ ] Part B - Relationships and Cardinalities
- [ ] Part C - ERD Design
- [ ] Part D - Schemas Before Normalization
- [ ] Part E - Schemas After Normalization
- [ ] Part F - SQL CREATE TABLE Statements
- [ ] Part G - Sample Data
- [ ] Part H - SQL Queries and Results
- [ ] All files are uploaded to GitHub
- [ ] SQL scripts have been tested
- [ ] Documentation has been reviewed
- [ ] Final submission matches the course requirements

## 13. Important Notes

- GitHub is used for file sharing and team collaboration.
- MySQL Workbench is used to execute and test SQL code.
- GitHub does not automatically execute our database scripts.
- Downloading files does not automatically synchronize changes.
- All changes must be uploaded and committed to the repository.
- The final submission must follow the instructor's requirements.

## 14. Useful Links

- [GitHub](https://github.com)
- [GitHub Documentation](https://docs.github.com)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- [GitHub File Upload Guide](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

---

**PawCare Management System**  
CS350 - Introduction to Databases  
Developed for educational purposes.
