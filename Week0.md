## Lesson 1
The init command only runs on fresh workspaces, not stale ones that are restarted after a short stop. Now using the 'before' key in the gitpod.yml file.

## Lesson 2
We have created a bash script in ./bin/install_terraform_cli to install terraform, and added it to tasks in the gitpod.yml file. This is because bash scripts to install Terraform are more than what was initially used, and this was noticed when fixing depracation issues.
Keeps the gitpod file tidy.

### Points to note
- This version is built against Ubuntu. Check your Linux distribution [here](https://www.cyberciti.biz/faq/how-to-check-os-version-in-linux-command-line/) and work accordingly.