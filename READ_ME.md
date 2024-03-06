# TverfagligDrift

## mål med oppgaven

i denne oppgaven skal jeg lage et spill og hoste det på en sørver.
jeg skal også prøve og holde telle på hvor mange som spiller spillet.

## hvordan koble opp github og GODOT

Using GitHub with Godot on Mac involves a series of steps to manage your Godot projects with version control. Here's a basic guide to help you get started:

### 1. Install Git:

Make sure you have Git installed on your Mac. You can download it from the official website: [Git Downloads](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### 2. Create a GitHub Account:

If you don't have a GitHub account, create one at [GitHub](https://github.com/).

### 3. Create a New Repository on GitHub:

1. Log in to your GitHub account.
2. Click on the "+" icon in the top right corner and select "New repository."
3. Fill in the repository name, add a description, choose public or private, and initialize with a README if you want.
4. Click on the "Create repository" button.

### 4. Clone the Repository:

Open the terminal on your Mac and navigate to the directory where you want to store your Godot project.

```bash
cd path/to/your/projects
```

Clone the GitHub repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
```

### 5. Set Up Godot Project:

Create a new Godot project or use an existing one. Ensure that the project is properly set up and functional.

### 6. Initialize Git in Your Godot Project:

Navigate to your Godot project's root directory using the terminal:

```bash
cd path/to/your/projects/your-repository
```

Initialize Git:

```bash
git init
```

### 7. Add Godot Project Files:

Add your Godot project files to the repository:

```bash
git add .
```

### 8. Commit Changes:

Commit the changes to the local repository:

```bash
git commit -m "Initial commit"
```

### 9. Connect to GitHub:

Link your local repository to the GitHub repository:

```bash
git remote add origin https://github.com/your-username/your-repository.git
```

### 10. Push Changes to GitHub:

Push the changes to GitHub:

```bash
git push -u origin master
```

Replace "your-username" and "your-repository" with your GitHub username and repository name.

Now, your Godot project is connected to a GitHub repository, and you can use Git commands to manage versions and collaborate with others. Remember to commit changes and push them to GitHub regularly.

Keep in mind that this is a basic guide, and you might need to adapt it to your specific project structure and collaboration needs. Additionally

, you may want to add some files or directories to your `.gitignore` file to exclude them from version control. For a Godot project, you might want to ignore the `*.import` and `*.tscn` files generated by Godot. Create a `.gitignore` file in your project's root directory and add the following lines:

```plaintext
*.import
*.tscn
```

This helps keep your repository clean and prevents unnecessary files from being tracked by Git.

Remember to adapt these instructions based on your specific project requirements and collaboration workflow. If you plan to work with others, consider creating branches, using pull requests, and following best practices for collaborative development with Git and GitHub.