# Basic Commands in Linux:

 Commands are nothing but executable programs which perform specific task written in it. These executable programs can be called using their name as per provided syntax. 
## General Syntax: 
     <commands>  - <options>  -<argument>  <multiple arguments>
  * Commands  - To run the command.
  * Options   - To adjust behavior of the commands.
  * Arguments - The behavior, file folder name.


1. This command displays current user terminal number.

       tty
   
2. Display current logged in all users with their details.

       Who
   
3. Display current user details.

       who am i
   
4. Display current user username.

       Whoami
   
5. Display all current user details with their time schedule.

        w
   
6. To see similar commands or autocomplete cmd.

        w <tab> <tab>
    
7. It clears screen but not background data.

        clear 
8. It displays current month of calendar.

        cal
    
9. It displays specified year calendar.

        cal <year>
    
10. It displays specific months calendar in particular year.

        cal <month> <year>
    
11. It displays previous, current and next month's calendar of current year.

        cal -3
    
12. It displays Julian days of particular year.

        cal -j <year>
    
13. It shows current date and time.

        date
    
14. It set date and time.

        date -s "DD MM YYYY  HH:MM:SS"

15. To restart the system.

        reboot

16. To poweroff the system.

        poweroff

17. It shutdown system after 1 min.

        shutdown

18. It shutdown system after 10 min and broadcast message to all users.

        shutdown -h 10

19. It cancels shutdown timer and broadcast message to all users.

        shutdown -c

20. It immediately shutdown system.

        shutdown now

21. Logout from currently logged in user.

        logout

22. Shows machine name.

        hostname

# Commands to view system information:

1. Show detailed information about system.

       hostnamectl

2. It displays operating system kernel name.

       uname -a

3. It display all information regarding system.

       uname -r

4. It display RAM information in human readable form.

       free -h

5. It lists all available USB devices.

       lsusb

6. It lists all PCI devices.

       lspci

7. It list processor information.

       lscpu

8. It display all hardware information (root).

       dmidecode

# GETTING HELP FROM COMMANDS:

1. Show manual of mentioned command.

       man <command>

2. Same as that of man command.

       info <command>

3. Display one line description of manual page. (#mandb command should use to update database manuals).

       whatis <command>

4. Show short description of manual page.

       <command> --help

5. To know path of command file.

       which <command>
