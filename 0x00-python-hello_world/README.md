Write a Shell script that runs a Python script.

The Python file name will be saved in the environment variable 

guillaume@ubuntu:~/py/0x00$ cat main.py 
print(Best School)

guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py
guillaume@ubuntu:~/py/0x00$ ./0-run
Best School
guillaume@ubuntu:~/py/0x00$
