▎Open Wizard Command-Line Tool

Open Wizard is a command-line tool designed to manage your projects efficiently. With this tool, you can add new projects, list existing ones, and quickly open them in Visual Studio Code.

▎Features

• Add Projects: Easily add a new project with a name and path.

• List Projects: View all registered projects in a tabular format.

• Open Projects: Quickly open a specified project in Visual Studio Code.

▎Installation

1. Clone the Repository (if applicable):
      git clone https://github.com/yourusername/open_wizard.git
   cd open_wizard
   

2. Create the Script:
   Save the provided Bash script as open_wizard.sh in a directory of your choice.

3. Make the Script Executable:
      chmod +x open_wizard.sh
   

4. Optional: Move to a Directory in Your PATH:
   You may want to move the script to a directory that is in your system's PATH for easier access:
      mv open_wizard.sh /usr/local/bin/open_wizard
   

▎Usage

▎Commands

open_wizard [command] [options]


▎Available Commands

• add <project_name> <path>: Add a new project with the specified name and path.
  
  Example:
    open_wizard add MyProject /path/to/my/project
  

• list: List all registered projects.
  
  Example:
    open_wizard list
  

• help: Display help information about the commands.
  
  Example:
    open_wizard help
  

• <project_name>: Open the specified project in Visual Studio Code.
  
  Example:
    open_wizard MyProject
  

▎Configuration

The projects are stored in a configuration file located at $HOME/.config/project_wizard/projects.conf. The script automatically creates this file if it does not exist.

▎Error Handling

• The script will display error messages for invalid commands, missing arguments, or if a project already exists.

• If you try to open a project that does not exist, you will receive an appropriate error message.

▎Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to submit an issue or create a pull request.


▎Acknowledgments

Thanks to the contributors and users who help improve this tool! Your feedback is invaluable.

---

Feel free to customize this README further based on specific details about your project or any additional features you may want to include!
