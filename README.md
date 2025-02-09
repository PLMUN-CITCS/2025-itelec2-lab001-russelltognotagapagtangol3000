# ITELEC 2 - Python Programming
Laboratory Activity # 01 - Introduction to Git and a Python Hello World Program

---

## **Instructions**

### **Step 1.1: Accept the Assignment**

1. Click on the assignment link provided by your instructor.
2. GitHub Classroom will create a **private repository** under your GitHub account.
3. After the repository is created, click **"Go to Repository"** to view your assignment.

---

### **Step 1.2: Setup your Git Environment**
1. Create a GitHub Account:
```bash
https://github.com/signup?source=login
```
   
2. Download and Install Git on your Laptop/Desktop:
```bash
https://git-scm.com/downloads
```

3. Create a Folder in your Laptop/Desktop
4. Right-click anywhere in the created folder and select "Open Git Bash Here".
5. In the Git Bash Terminal, set your git name, perform command:
```bash
git config --global user.name "Your Name"
```

6. In the Git Bash Terminal, set your git email, perform command:
```bash
git config --global user.email "your.email@example.com"
```

7. Create your SSH Key, just follow the instructions, no need to provide filename and passphrase. In the Git Bash Terminal, perform command:
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

8. Copy your SSH Keys into clipboard. In the Git Bash Terminal, perform command:
```bash
clip < ~/.ssh/id_rsa.pub
```

9. Log in to your GitHub account.
10. In the upper-right corner of GitHub, click your profile picture and select Settings.
11. In the left sidebar, click on SSH and GPG keys.
12. Click the New SSH key button.
13. In the Title field, give the key a recognizable name (e.g., "My Windows Laptop").
14. In the Key field, CTRL + V or paste the keys copied into your clipboard. Save the key.
15. Go Back to terminal, use command:
```bash
ssh -T git@github.com
```

### **Step 2: Clone the Repository to Your Local Machine**

1. On your repository page, click the green **"Code"** button.
2. Copy the repository URL (choose HTTPS for simplicity).
3. Open your terminal (or Git Bash, Command Prompt, or PowerShell) and run:

```bash
git clone <remote_repo_folder>
```

4. Navigate into the cloned folder:

```bash
cd <local_repo_folder>
```

### **Step 3: Complete the Assignment**


# **Hello World Assignment**

Welcome to your first GitHub Classroom assignment! Follow the instructions carefully to complete and submit your work.
**Objectives**
- Learn Basic Python: Write a simple Python program that prints output to the console.
- Practice File Management: Create and update files (hello.py and intro.txt) within your GitHub Classroom repository.
- Integrate Details: Ensure your program echoes both a standard greeting and your personal introductory information.
- Develop Version Control Skills: Commit and push changes to your repository according to assignment guidelines.

**Folder Structure and Naming Conventions**
- Repository Root: All files should reside in the root folder of your cloned repository.
- Python File:
   - Name: hello.py
   - Purpose: Contains your Python code that prints the desired output.
- Text File:
   - Name: intro.txt
   - Purpose: Contains your personal information in a specified format.

**Desired Output**
When `hello.py` is executed, the console output should be:
```txt
Hello world!
Name: [Your Full Name]
Course: [Your Course Name]
Interests in programming: [Your Interests]
```
Make sure that your program exactly prints these lines (replacing the placeholders with your actual information).

**Notable Observations**
- Consistency is Key: Both hello.py and intro.txt must be located in the repository’s root directory to ensure proper recognition during grading.
- Naming Conventions: Stick to the provided file names (hello.py and intro.txt) to avoid any issues with automatic grading.
- Program Execution: Verify that your Python script runs correctly without errors before submission.
- Information Duplication: Note that the details provided in intro.txt are also printed in hello.py—this redundancy is intentional to reinforce file editing and output formatting skills.
- Version Control: Regular commits with clear messages help track your progress and make it easier to identify issues if any arise.

**Step-by-Step Instructions**
1. Write a "Hello World" Program
Create a simple program in Python programming language. Save the file inside the repository folder.

2. Create and Edit `hello.py`
- Initial Code: Create or open hello.py and add the following code to print a simple greeting:
   ```python
   print("Hello world!")
   ```
- Update Code: Later, modify hello.py to include your personal details. The final version should be:
   ```python
   print("Hello world!")
   print("Name: [Your Full Name]")
   print("Course: [Your Course Name]")
   print("Interests in programming: [Your Interests]")
   ```
   *Replace [Your Full Name], [Your Course Name], and [Your Interests] with your actual details.*

3. Create and Populate `intro.txt`
   - File Creation: In the repository root, create a file named intro.txt.
   - Add Details: Open intro.txt in a text editor and include:
   ```txt
   Name: [Your Full Name]
   Course: [Your Course Name]
   Interests in programming: [Your Interests]
   ```
   *Again, replace the placeholders with your actual information.*

**Conclusion**
By following these refined instructions, you will:
- Successfully complete a foundational programming assignment.
- Learn the importance of folder organization, file naming, and version control.
- Develop a better understanding of how to integrate multiple file formats (code and text) to create a cohesive project.

### **Step 4: Push Changes to GitHub**
Once you've completed your changes, follow these steps to upload your work to your GitHub repository.

1. Check the status of your changes:
Open the terminal and run:

```bash
git status
```
This command shows any modified or new files.

2. Stage the changes:
Add all modified files to staging:

```bash
git add .
```

3. Commit your changes:
Write a meaningful commit message:

```bash
git commit -m "My first Python program"
```

4. Push your changes to GitHub:
Upload your changes to your remote repository:

```bash
git push origin main
```

### **Step 5: Submit Your Repository Link**
Once your changes have been pushed:
1. Visit your GitHub repository online.
2. Copy the repository URL from your browser (e.g., https://github.com/PLMUN-CITCS/your-repo.git).
3. Submit the repository link to your instructor via the classroom portal or as instructed.

