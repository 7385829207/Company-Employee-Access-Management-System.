# Company Employee Access Management System

## 1. Project Overview
This project demonstrates Linux system administration concepts for managing user accounts, groups, file permissions, and access control. The objective is to understand how Linux administrators organize users and restrict access to files and directories.

## 2. Objectives
- Practice Linux user and group management.
- Configure file and directory permissions.
- Understand ownership and access control.
- Use basic shell commands for administration.
- Explore shell scripting for repetitive tasks, if implemented.

## 3. Technologies Used
- Linux
- Bash / Shell commands
- Linux file permissions
- User and group administration utilities

## 4. Key Concepts
- User creation and management
- Group creation and membership
- File ownership using `chown`
- Permissions using `chmod`
- File and directory access verification

## 5. Implementation Workflow
1. Set up or access a Linux environment.
2. Create test users and groups, if required.
3. Assign users to the appropriate groups.
4. Create a test directory and files.
5. Configure file ownership and permissions.
6. Verify permissions and access using Linux commands.
7. Record command outputs and screenshots as evidence.

## 6. Example Commands
```bash
sudo groupadd projectteam
sudo useradd -m employee1
sudo usermod -aG projectteam employee1
sudo mkdir -p /opt/employee-access
sudo chown root:projectteam /opt/employee-access
sudo chmod 770 /opt/employee-access
ls -ld /opt/employee-access
id employee1
```

These commands are examples. Run them only in a test Linux environment and document the results you actually observe.

## 7. Testing and Results
Document the actual output of user and group checks, file ownership, permissions, and access tests. Include screenshots of successful tests and any issues resolved.

## 8. Skills Demonstrated
- Linux command-line basics
- User and group administration
- File ownership and permissions
- Basic access control
- Shell scripting, if implemented

## 9. Conclusion
This project provides practical learning in Linux administration and file access management, relevant to entry-level Linux Support and Infrastructure roles.
