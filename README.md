# Homework Assignment #6 - Database Design and Queries

## Task Description

Implement a database schema with the following tables:

1. Students
2. Groups
3. Instructors
4. Subjects with an indication of the instructor who teaches the subject
5. Table where each student has grades for specified subjects with the indication of when the grade was received

Fill the obtained database with random data (approximately 30-50 students, 3 groups, 5-8 subjects, 3-5 instructors, up to 20 grades for each student in all subjects). Utilize the Faker package for data population.

Perform the following queries on the database:

1. Find 5 students with the highest average grade across all subjects.
2. Find the student with the highest average grade in a specific subject.
3. Find the average grade in groups for a specific subject.
4. Find the overall average grade.
5. Find the courses taught by a specific instructor.
6. Find the list of students in a specific group.
7. Find the grades of students in a specific group for a certain subject.
8. Find the average grade given by a specific instructor for their subjects.
9. Find the list of courses attended by a student.
10. Find the list of courses taught by a specific instructor to a specific student.

Create separate SQL query files for each query, named query_number.sql, where "number" is the query number. Each file contains the SQL instructions that can be executed in the database terminal or through cursor.execute(sql).

## Additional Task

For the additional task, create queries of increased complexity:

1. Average grade given by a specific instructor to a specific student.
2. Grades of students in a specific group for a specific subject on the last session.
