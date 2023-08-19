# Cloning a GitHub Repository

Cloning a repository allows you to create a local copy of a GitHub repository on your computer. This is useful for making changes, experimenting, and collaborating with others. Here's how to clone a repository:

1. **Copy Repository URL**: Go to the repository you want to clone on GitHub. Click the green "Code" button and copy the repository's URL. You can use either HTTPS or SSH, depending on your preference and setup.

2. **Open Terminal**: Open your terminal or command prompt.

3. **Navigate to Your Desired Directory**: Use the `cd` command to navigate to the directory where you want to clone the repository. For example:

4. **Clone the Repository**: In your terminal, type the following command:
- For HTTPS:
  ```
  git clone https://github.com/username/repository-name.git
  ```
- For SSH:
  ```
  git clone git@github.com:username/repository-name.git
  ```
Replace `username` with the repository owner's username and `repository-name` with the actual repository name.

5. **Press Enter**: Press Enter to execute the command.

6. **Authenticate (If Using SSH)**: If you're using SSH and haven't previously connected to GitHub with SSH, you might be prompted to authenticate. Follow the prompts to authenticate using your SSH key.

7. **Repository Cloned**: Git will clone the repository into a folder named after the repository. You can now navigate into the repository's directory and start working on it.

Congratulations! You've successfully cloned a GitHub repository to your local machine.

