Date: 2025-06-13
Tags: [[linux]] [[linux commands]]



# Linux File Permissions



The things any permission group can do:
- READ
- WRITE
- EXECUTE

Permission Groups:
- Owner
- Group
- Others

Command to see all permissions:
```bash
ls -l
```

Output:
```bash
drwxrwxr-x
```

The output has four parts:
- d: Directory
- rwx: Owner Permissions 
- rwx: Group Permissions
- r-x: Others Permissions

Command to change the owner of the file:
```bash
chown mThanuj <file_name>
```

Command to change the privilages of the file:
```bash
chmod 774 <file_name>
```

Common Permissions:

- 644: File Baseline
- 755: Directory Baseline
- 400: Key Pair



# References
- [Travis Media about Linux File Permissions](https://www.youtube.com/watch?v=LnKoncbQBsM)