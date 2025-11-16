# Project Report - IT110 Project 1 
## File Review and Organization Plan
**Author:** Bertnah Nerjuste  
**Date:** November 2025 

---

## 1. Introduction 
The purpose of this project was to review the content of a ZIP archive containing student submissions with inconsistent and unclear file names. The objective was to examine the files, document findings, and create a proposed solution for organizing them in a clean and scalable structure.

## 2. Observations 
- Many filenames consisted of long, random, hash-like strings.
- No directory structure was present.
- Files contained identifiable student information.
- Data for different courses and assignments was mixed together.
- No naming conventions existed.

## 3. Tools & Commands Used
I evaluated the files using various Linux commands:
- `ls` – list filenames
- `head` – preview file contents 
- `cd` – navigate directories
- `scp` – transfer files to remote server
- `mkdir` – create new directories
- `mv` – reorganize files

## 4. Proposed Directory Structure
The following structure organizes files by:
- Course
- Assignment/Project
- Student Name

**Example:**  
`IT110/Python_Assignment4/JohnDoe_Python_Assignment4.py`

## 5. Proposed Naming Conventions 
A consistent naming system:  
`LastName_FirstName_Project#.txt`  
This improves readability, searchability, and scalability.

## 6. Conclusion 
Although the files were not reorganized directly, this project demonstrates the ability to analyze unstructured data, plan an organizational structure, and document technical processes—all valuable skills in IT and System Administration.

---

## 7. Project Findings and Reflection

### 1. Problem Definition

After unzipping `student_files.zip`, our group found many text files with random, hash-like names. There were no folders separating classes or assignments, and the filenames did not indicate their subject or project. This disorganization, caused by non-descriptive filenames and lack of directory structure, made it difficult to quickly identify which file corresponded to which assignment. Our goal was to develop a consistent, logical naming and folder system for these files to make retrieval and grading more efficient.

---

### 2. Significant Questions

Throughout our process, we considered important organizational questions, such as:
- How should we organize the files: by class, project, or student?
- What naming convention should we use?
- Should we create a folder for each class or combine all under one directory?
- How can we ensure our structure is easy to maintain in the future?

---

### 3. Evolving Perspectives

At the beginning of this project, I viewed file organization mainly as a matter of convenience, something that made it easier to find files later. As I explored the disorganized student files, I realized that proper file structure is actually essential for clarity, collaboration, and long term maintenance. A second shift came when I learned how naming conventions can communicate meaning. Initially, I didn't think much about filenames, but after seeing a directory full of random hashes, I understood how meaningful names can drastically improve usability and make automation or searching much easier.

---

### 4. Personal Participation and Group Dynamics

In our group, my role is to help organize and rename files systematically. I focused on developing a logical folder structure and testing different naming patterns to ensure they were consistent and clear. Referring to Exercise 2.7, I tend to play the role of the "analyzer". I like to assess problems throughly before acting. My teammates, on the other hand, contributed strengths like efficiency and creativity, which balanced our workflow. Together, we discussed multiple strategies, decided on one that grouped files by class and project and verified the results collaboratively.

---

### 5. Personal Impact

This project has definitely influenced how I approach file and folder organization. Before, I would often save files with vague names in one large folder. Now, I recognize the value of structured directories and consistent naming conventions. Going forward, I plan to create separate folders for each course or project, label files with meaningful names and include version numbers when appropriate. This will make my work easier to track, share, and back up both in academic and professional environments.
