Date: 2025-06-13
Tags: [[bash]] [[linux commands]]


# Variables in Bash

- Variables are containers that can store a value
- Types of variables:
	- System Defined
	- User Defined


```bash
> env

ANDROID_HOME=/home/mthanuj/Android/Sdk
CLUTTER_BACKEND=wayland
COLORTERM=truecolor
COMPOSE_BAKE=true
CONDA_EXE=/home/mthanuj/anaconda3/bin/conda
CONDA_PYTHON_EXE=/home/mthanuj/anaconda3/bin/python
CONDA_SHLVL=0
DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/bus
```

## Types of variables
- Local variables
	- only works in the current shell session
- Global variables
	- works in the any shell session, until the system gets turned off

### Syntax to define local variables
```bash
> variable_name=value
```

```bash
> NAME=mThanuj
```

### Syntax to define global variables
```bash
> export course=bash_course
```
## Access variables
```bash
> echo $NAME
```

OR

```bash
> echo ${NAME}
```


# References
- [19:18](https://www.youtube.com/watch?v=9T2nEXlLy9o&list=PLxLRoXCDIalcosmDOQizh31EIHEK1njfO&index=1)