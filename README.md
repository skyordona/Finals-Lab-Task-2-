# [Finals Lab Task 2 - Transforming ER Model to Relational Tables](https://github.com/user-attachments/files/19642468/Finals.Lab.Task.2.-.Ordona.docx)
- This portfolio demonstrates my understanding of MySQL database creation using a simplified student assignment submission system. It covers the step-by-step creation of tables representing students, assignments, and their submissions. This exercise applies data types, relationships, and constraints like primary keys, foreign keys, and composite keys to build a fully functional relational schema.

# Step By Step Process
### 1. Create the student table:
- Define username as a VARCHAR(50).
- Set username as the Primary Key.

### 2. Create the assignment table:
- Define shortname as a VARCHAR(50) and set it as the Primary Key.
- Define due_date as a DATE NOT NULL.
- Define url as a VARCHAR(255), which can be null.

### 3. Create the submission table:
- Define username and shortname both as VARCHAR(50).
- Define version as an INT.
- Define submit_date as a DATE NOT NULL.
- Define data as TEXT.
- Set a composite primary key of (username, shortname, version).
- Add foreign keys referencing the student and assignment tables.

# Screenshots
## Query Statements
1. Student Table
- ![Image](https://github.com/user-attachments/assets/31bf974d-4a00-411b-8a8e-84a159f7ea74)

2. Assignment Table
- ![Image](https://github.com/user-attachments/assets/3ae89b77-3729-47e7-a889-d69e8110a052)

3. Submission Table
- ![Image](https://github.com/user-attachments/assets/173a02c8-de96-4f1b-b59a-f13d377ef8af)

## Table Structure
1. Student Table
- ![Image](https://github.com/user-attachments/assets/ffa8ad03-172d-4ee3-803b-1c1d161259f0)

2. Assignment Table
- ![Image](https://github.com/user-attachments/assets/1517a71a-5a84-42c0-8d83-86b8905d464c)

3. Submission Table
- ![Image](https://github.com/user-attachments/assets/2dec876b-0834-4045-befa-3b89b1cc2ca9)

## EER Diagram
- ![Image](https://github.com/user-attachments/assets/89d690f1-63e2-465a-9455-d46166a425d4)
- ![Image](https://github.com/user-attachments/assets/71d69680-01ec-4a9f-bcbe-7132f843f0eb)
