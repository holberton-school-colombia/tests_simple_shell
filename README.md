# tests_simple_shell

This repository is created for Holberton School Colombia Students, the porpuose of this repository
is to create a test suit for the Shell project.

1. type this in your prompt
`echo "qwerty" | ./shell`\
you should get :
`./shell: 1: qwerty: not found`
2. when you type `crtl + c ` it should not crash your shell\
expected output: `^C`
3. when you type `ctrl + d` your shell should close
4. if you type `ls -` or `ls +` you should get an error\
`ls: cannot access -: No such file or directory`
5. write a script that executes three times `ls` command
```sh
#!/bin/bash
ls && ls && ls
```
it should execute `ls` command three times.
