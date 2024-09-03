## How to connect Obsidian to a GitHub repository
- Create a repository on GitHub:
		Go to GitHub and create a new repository (can be public or private).
- Clone the Repository to your Computer:
		Open the terminal and clone your repository with: git clone URL(URL of your repository)
-Setting up Obsidian: 
		Open Obsidian and select the cloned folder as your vault.
- Initialize Git (if necessary):
		If using an existing vault, start Git in the folder: -git init -git remote add origin URL(URL of your repository)
- Organize your folders using the PARA method:
		Organize your Obsidian vault by creating folders, either from Obsidian or Visual Studio Code, following this structure: (Projects, Areas, Resources, Archives)
- Connect Visual Studio Code to Edit Obsidian Files:
		Download and install Visual Studio Code.
		Open Visual Studio Code, go to the extensions section and search for and install the Obsidian.md extension
		Open your vault folder in VSCode to edit your .md files directly from there
- That’s it! You can now edit your Obsidian notes directly from VSCode.
- You can use plugins in Obsidian, such as "Obsidian Git", to automate the commit and push process directly from the Obsidian interface.
