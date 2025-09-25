# Usage Guide

## Run the Application

1. Ensure that you have the Java JDK 8 or later version installed
2. Clone the repository
3. Navigate to project directory
4. Compile: `javac -d bin src/**/*.java`
5. Run: `java -cp bin edu.ccrm.Main`



## Sample of Operations performed

### Add a Student
1. Select "Manage Student" from main menu
2. Choose "Add Student"
3. Enter details of the student when prompt appears

### Enroll a Student
1. Select "Manage Enrollments" from the main menu
2. Choose "Enroll Student in Course"
3. Enter student's ID and the course code

### Add a Course
1. Select "Manage Course" from main menu
2. Choose "Add Course"
3. Enter details of course and select the semester


### Generate a Transcript
1. Select "Manage Students" from main menu
2. Choose "Generate Transcript"
3. Enter the student's ID

### Import Data
1. Place CSV files in data directory
2. Select "Import/Export Data" from the main menu
3. Choose import option

### Create Backup
1. Select "Backup Operations" from main menu
2. Choose "Create Backup"
3. Backups are stored in the timestamped folders