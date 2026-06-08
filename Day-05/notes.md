# Day 5 Notes

1. Users
   - Linux supports multiple users.
   - Each user has their own files and directories.

2. Root User
   - Administrator of the Linux system.
   - Has complete access to the server.

3. sudo
   - Execute commands with root privileges.
   - Example:
     sudo apt update

4. File Permissions
   - Linux controls who can access files and directories.

5. Read Permission (r)
   - Allows viewing/opening a file.

6. Write Permission (w)
   - Allows modifying/editing a file.

7. Execute Permission (x)
   - Allows running a file as a program or script.

8. Permission Groups
   - Owner
   - Group
   - Others

9. Permission Structure

   Example:
   rwxr-xr--

   Owner  -> rwx
   Group  -> r-x
   Others -> r--

10. chmod
    - Used to change file permissions.

    Example:
    chmod +x deploy.sh
    read - 4
    write - 2
    execute - 1

    chmod 755 deploy.sh
    7 = rwx = 4+2+1
    5 = r-x = 4+0+1
    5 = r-x = 4+0+1

12. chmod +x
    - Adds execute permission.

    Before:
    rw-

    After:
    rwx

13. Why Permissions Matter
    - Protect files from unauthorized access.
    - Control who can read, modify, or execute files.
    - Important for server security.
