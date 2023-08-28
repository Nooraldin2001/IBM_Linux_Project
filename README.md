# IBM_Linux_Project
Hands-on Introduction to Linux Commands and Shell Scripting Course (Final project)

**Project Description: Simplified Automated Backup Script**

The `backup.sh` Bash script automates the backup of files from a source directory to a destination directory. It ensures that recently modified files are backed up. Here's a quick rundown of what the script does:

1. Checks if the correct number of arguments (source and destination directories) is provided.

2. Verifies if the provided directory paths are valid.

3. Stores source and destination paths, displaying them for clarity.

4. Calculates the current timestamp.

5. Generates a backup file name with the current timestamp.

6. Navigates between directories, noting original and destination paths.

7. Calculates a timestamp from 24 hours ago.

8. Selects files modified within the last 24 hours for backup.

9. Creates a compressed backup file with selected files.

10. Moves the backup file to the destination directory.

The script aims to streamline the process of keeping important files backed up, saving you time and effort. After successful execution, you'll receive a congratulatory message, indicating the completion of the backup process.
