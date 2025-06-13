Date: 2025-06-13
Tags: [[bash]]



# SYSINFO script in Bash
```bash
#!/bin/bash

echo "Username: $USER"

echo -e "Today's date and time is: \c"; date

echo -e "Users login: \c"; who | wc -l

cal
```

Output:
```bash
❯ ./sysinfo.sh
Username: mthanuj
Todays date and time is: Fri Jun 13 06:59:57 PM IST 2025
Users login: 3
      June 2025
Su Mo Tu We Th Fr Sa
 1  2  3  4  5  6  7
 8  9 10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30
```


# References
- [13:26](https://www.youtube.com/watch?v=9T2nEXlLy9o&list=PLxLRoXCDIalcosmDOQizh31EIHEK1njfO&index=1)