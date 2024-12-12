# File management of class resources and assignments with Permission Control

## Content
- [Project introduction](#Project introduction)
- [Functional characteristics](#Functional characteristics)
- [Installation and use](#Installation and use)
- [License](#License)
- [Contact information](#Contact information)

## Project introduction
This Java-based file-sharing system enables teachers to upload and manage classroom resources, and collaborate with teaching assistants for file organization and grading. Students can securely view resources files and submit assignment files based on permissions, ensuring efficient and controlled file sharing in the classroom.
- **Purpose**：This file management system is designed to streamline educational file sharing and management within university classrooms. Its functionalities are structured into three main roles: teachers, students, and teaching assistants.
- **Programming language**：Java, Java Swing, AWT

## Functional characteristics
- **Teachers**：
    - Teachers can upload course materials such as lecture notes and assignment templates.
    - Teachers have full control over files, including uploading, deleting, and search files.
    - Teachers can view all students' assignments and grade them.
    - While grading, files are automatically locked to prevent simultaneous edits by other users, safeguarding grades and feedback integrity.
- **Students**：
    - Each student can upload their assignment submissions.
    - Their work can only be seen by themselves, teachers and teaching assistants, and other students cannot see it. This ensures privacy and security for assignment submissions.
    - Students can view class materials shared by teachers and their own grading status of the assignment.
- **Teaching Assistants (TAs)**：
    - TAs can assist teachers in grading assignments, with the system locking the grades to prevent any modifications by others.
    - They can review assignments and modify grades, with the system locking the grades to prevent any modifications by others.

## Installation and Usage
### Prerequisites

- Java Development Kit (JDK) 8 or higher
- A Java IDE (e.g., IntelliJ IDEA, Eclipse)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/classroom-file-management.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd ClassroomSystem
   ```

3. **Import the Project into Your Java IDE**:
  - Open your IDE and import the project as a Maven project.

4. **Configure Dependencies**:
  - Ensure all required libraries and dependencies are properly configured in the IDE.

### Usage

1. **Run the Application**:
  - Locate the `LoginFrame.java` file in your IDE and run it.

2. **Login as a User**:
  - Use the following credentials for testing:
    - Teacher: `Username: teacher1`, `Password: password1`
    - Student: `Username: student1`, `Password: password1`
    - Teaching Assistant: `Username: ta1`, `Password: password1`

3. **Explore Functionalities**:
  - Depending on the user role, interact with the system's features such as uploading, viewing, and managing files.


## License
This project is open source under the MIT License.

## Contact Information

For any inquiries or issues, feel free to contact:

- **Developer**: Longyi Yuan, Mingjie Fang, Leili Chen
- **Email**: yuanlo@kean.edu, fangmin@kean.edu, chenleil@kean.edu
