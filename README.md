Database Description:
This schema represents a School Management System. It outlines the structure of a
relational database intended to manage various entities within a school, including students,
teachers, grades, classes, subjects, and admin information. Here's a detailed description:
Entities and Attributes
1. Students
o Attributes:
▪ Student_name: Name of the student.
▪ Student_id: Unique identifier for the student (Primary Key).
▪ Grade_id: References the grade the student belongs to (Foreign Key). ▪
Date_of_birth: Date of birth of the student.
▪ Class_id: References the class the student belongs to (Foreign Key).
2. Teachers
o Attributes:
▪ Teacher_name: Name of the teacher.
▪ Teacher_id: Unique identifier for the teacher (Primary Key).
▪ Teacher_dept: Department of the teacher.
▪ Sub_id: References the subject taught by the teacher (Foreign Key).
3. Grades
o Attributes:
▪ Grade_id: Unique identifier for the grade (Primary Key).
▪ Grade_name: Name of the grade (e.g., Grade 1, Grade 2).
4. Classes
o Attributes:
▪ Class_id: Unique identifier for the class (Primary Key).
▪ Class_name: Name of the class.
▪ Teacher_id: References the teacher assigned to the class (Foreign
Key).
▪ Class_strength: Number of students in the class.
▪ Class_avg_grade: Average grade of the students in the class.
5. Subjects
o Attributes:
▪ Sub_id: Unique identifier for the subject (Primary Key).
