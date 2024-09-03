## How to connect Obsidian to a GitHub repository
- Create a repository on GitHub:
		Go to GitHub and create a new repository (can be public or private).
  ![newRepositorio](https://github.com/user-attachments/assets/bad4c10c-af9e-4627-b3b4-d06b3bdeea6a)
  
- Clone the Repository to your Computer:
		Open the terminal and clone your repository with: git clone URL(URL of your repository)
  ![clonarRepositorio](https://github.com/user-attachments/assets/a3084eb2-6c87-4908-a9b8-11cc1b756e4a)
  
- Setting up Obsidian: 
		Open Obsidian and select the cloned folder as your vault.
  ![obsidian](https://github.com/user-attachments/assets/4fd69788-d0b2-4b3e-b482-a34e8afddd1f)
  
- Initialize Git (if necessary):
		If using an existing vault, start Git in the folder: -git init -git remote add origin URL(URL of your repository)
  ![iniciar git](https://github.com/user-attachments/assets/0183a727-af7e-4dd7-8985-35fb4b02587b)

- Organize your folders using the PARA method:
		Organize your Obsidian vault by creating folders, either from Obsidian or Visual Studio Code, following this structure: (Projects, Areas, Resources, Archives)
  ![organizar carpetas](https://github.com/user-attachments/assets/7c4e6854-f286-458c-95ea-811fc56c70e0)

- Connect Visual Studio Code to Edit Obsidian Files:
		Download and install Visual Studio Code.
  
		Open Visual Studio Code, go to the extensions section and search for and install the Obsidian.md extension
  ![extension vsc](https://github.com/user-attachments/assets/69eb96bd-8a08-42ed-92d7-ba131769e626)

		Open your vault folder in VSCode to edit your .md files directly from there
  ![vsc con la carpeta de obsidian](https://github.com/user-attachments/assets/accd1d6c-b6db-44b2-abbb-7c8c7653b3b1)
  
- That’s it! You can now edit your Obsidian notes directly from VSCode.
  ![edit vsc and obsidian](https://github.com/user-attachments/assets/21eca488-1970-438d-9ba8-fe6d369f3270)

		It automatically changes to obsidian.
  ![cambio obsidian](https://github.com/user-attachments/assets/644c773c-f0da-434c-a8c3-55ff454be058)

- You can use plugins in Obsidian, such as "Obsidian Git", to automate the commit and push process directly from the Obsidian interface.
  ![plugins](https://github.com/user-attachments/assets/4d599f53-019a-40fc-b227-ebf7aba00dec)

