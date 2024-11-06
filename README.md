# inet_4031_adduser_script

# Program Decription
This Python script automates the process of creating and managing user accounts on a Unix-like system. It reads input from a file, with each line containing user details such as username, password, and groups. The script first filters out comments (lines starting with #) and lines that do not have exactly five fields. For valid lines, it extracts user information, including username, password, and group memberships, then constructs and executes system commands to create the user, set their password, and assign them to specified groups. This automation ensures consistent and efficient user account management, simplifying tasks that would otherwise require multiple manual commands.



# Program Operation
1. Ensure python is installed
2. Naviaget toi the script directory
3. Check script permissions
4. Prepare input file
5. Run the script
