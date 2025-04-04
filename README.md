# Introduction-to-Git-and-GitHub
Introduction to Git and GitHub

## Git & GitHub Exercise Assignment

This assignment is designed to help you practice using Git and GitHub. Each task is worth one point. Please complete the following tasks:

0. **Fork the Repository**  
   Fork the repository on GitHub to your own account.

1. **Clone the Repository**  
   Clone the repository to your local machine.

2. **Create an Exercise File**  
   Create a simple text file (e.g., exercise.txt) that will serve as the primary file for the exercise. Add a few initial lines of text to the file.

3. **Make an Initial Commit**  
   Stage and commit the exercise file to the repository with an appropriate commit message.

4. **Create a Branch Called "feature1" with Detailed Changes**  
   - Create a new branch named "feature1" from the main branch.
   - Switch to the "feature1" branch.
   - Open the exercise.txt file and add a line indicating this branch's changes; for example, include your name or a descriptive note.
   - Be specific with your change so that you can clearly see the differences from the main branch later.
   - Commit the changes in the "feature1" branch with a clear commit message explaining what you did.

5. **Create Another Branch Called "feature2" with a Conflicting Change**  
   - Switch back to the main branch.
   - Create a new branch named "feature2" from the main branch.
   - Switch to the "feature2" branch.
   - Open the same line in exercise.txt that you modified in "feature1" and deliberately change it in a different way to create a merge conflict.
   - Include a unique message or note that highlights the difference.
   - Commit the changes in the "feature2" branch with a descriptive commit message.

6. **Merge the Branches to Create and Resolve a Merge Conflict**  
   - Switch to the main branch.
   - Merge "feature1" into main; this merge should complete without any conflict.
   - Next, merge the remaining branch ("feature2") into main. This merge should trigger a conflict because both branches modified the same line.
   - Open the exercise.txt file and review the conflict markers (`<<<<<<< HEAD`, `=======`, and `>>>>>>> feature2`).
   - Resolve the conflict by editing the file to choose or combine the changes from both branches, then remove the conflict markers.
   - Stage and commit the resolved file with a clear message indicating that the merge conflict has been resolved.

7. **Review Your Work**  
   Use Git commands such as checking the repository status, viewing the commit history, and examining file differences to verify that your changes and merge conflict resolution are correct.

Good luck with the exercise and happy coding!