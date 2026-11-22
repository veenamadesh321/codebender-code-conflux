<div align="center">
  
# Code Conflux

| Details | Information |
|---|---|
| **Team Name** | Code Conflux|
| **Team Members** | Veena.M, Priya S N |
|  **Tier**| Online|
| **Organisation** | Codebenders ACE Builders|

---

## 📌 Table of Contents

- [Team Members]
  (#-team-members-github-ids)
- [Problem Statement]
  (#-problem-statement)
- [Proposed Solution]
  (#-proposed-solution)
- [Approach & Architecture]
  (#-approach--architecture)
- [Tech Stack](
  #-tech-stack)
- [Project Structure](
  #-project-structure)

---


The Problem
Millions of underprivileged students study in regional-language schools with too few teachers, no tutoring and, for 
some, unreliable access to school itself. Almost all good digital learning content is in English and assumes a 
personal smartphone, steady data and a parent who can guide the child. The students who need help the most are 
the ones ed-tech reaches the least.

3.  Architecture and Approach

System Architecture

LearnLink consists of the following main components:

1. User Interface: Provides a simple and easy-to-use platform for students.
2. Language Module: Provides learning materials in different regional languages.
3. AI Tutor Module: Helps students understand concepts and clear doubts.
4. Offline Storage: Stores lessons for learning without internet access.
5. Backend System: Manages student details, educational content, and learning activities.
6. Database: Stores learning materials and student progress.

Working Approach

- Step 1: Students open the LearnLink platform.
- Step 2: Select their preferred language.
- Step 3: Choose their class and subject.
- Step 4: Access lessons, notes, and educational materials.
- Step 5: Ask questions and receive simple explanations.
- Step 6: Download lessons for offline learning.
- Step 7: Track their learning progress.

---

4. 💻 Tech Stack

Technology| Purpose
Python| Backend programming and AI integration
C Language| Basic programming and student management
HTML| Web page structure
CSS| User interface design
JavaScript| Interactive features
Flask| Backend development
SQLite| Database management
AI / NLP| Understanding student questions
Text-to-Speech| Converting text into audio
GitHub| Code management and collaboration

---

5. 📂 Program Structure

The project will be organised into the following structure:

LearnLink/
│
├── README.md
│
├── Python/
│   ├── main.py
│   ├── ai_tutor.py
│   ├── language.py
│   └── progress.py
│
├── C/
│   └── student_learning.c
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   └── app.py
│
├── database/
│   └── students.db
│
└── content/
    ├── kannada/
    ├── english/
    └── lessons/

---

6. 👨‍💻 Coding and Programming

A. Python Programming

Python is used to develop the learning system, manage educational content, and provide basic student support.

Program: LearnLink – Student Learning Platform

print("================================")
print("       WELCOME TO LEARNLINK")
print(" Learning for Everyone")
print("================================")

name = input("Enter Student Name: ")

print("\nSelect Your Language:")
print("1. English")
print("2. Kannada")

language = int(input("Enter your choice: "))

if language == 1:
    lang = "English"
elif language == 2:
    lang = "Kannada"
else:
    lang = "English"

print("\nSelect Your Subject:")
print("1. Mathematics")
print("2. Science")
print("3. Computer Science")

subject = int(input("Enter your choice: "))

subjects = {
    1: "Mathematics",
    2: "Science",
    3: "Computer Science"
}

if subject in subjects:
    print("\nWelcome", name)
    print("Language:", lang)
    print("Subject:", subjects[subject])
    print("Your learning lesson is ready!")
else:
    print("Invalid subject selection.")

print("\nThank you for using LearnLink!")

B. C Programming

C language is used to develop a basic student learning program with language and subject selection.

Program: Student Learning System

#include <stdio.h>

int main()
{
    int language, subject;

    printf("================================\n");
    printf("       WELCOME TO LEARNLINK\n");
    printf(" Learning for Everyone\n");
    printf("================================\n");

    printf("\nSelect Your Language:\n");
    printf("1. English\n");
    printf("2. Kannada\n");

    printf("Enter your choice: ");
    scanf("%d", &language);

    printf("\nSelect Your Subject:\n");
    printf("1. Mathematics\n");
    printf("2. Science\n");
    printf("3. Computer Science\n");

    printf("Enter your choice: ");
    scanf("%d", &subject);

    if (language == 1)
        printf("\nLanguage: English\n");
    else if (language == 2)
        printf("\nLanguage: Kannada\n");
    else
        printf("\nInvalid language choice\n");

    switch(subject)
    {
        case 1:
            printf("Subject: Mathematics\n");
            break;

        case 2:
            printf("Subject: Science\n");
            break;

        case 3:
            printf("Subject: Computer Science\n");
            break;

        default:
            printf("Invalid subject choice\n");
    }

    printf("\nWelcome to LearnLink!");
    printf("\nHappy Learning!\n");

    return 0;
}

---

7. 🎯 Expected Outcome

LearnLink aims to provide affordable, multilingual, and accessible education to students who lack proper learning facilities.

By combining regional languages, AI-based tutoring, and offline learning, the platform aims to:

- Reduce the educational gap between students.
- Support students from rural and underprivileged backgrounds.
- Improve access to quality educational materials.
- Encourage independent learning.
- Make digital education accessible to everyone.

---

🌟 Conclusion

LearnLink is designed to bridge the educational gap by making learning simple, affordable, and accessible.

It aims to ensure that every student gets an equal opportunity to learn, grow, and succeed.
