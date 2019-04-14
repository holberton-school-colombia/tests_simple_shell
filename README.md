# tests_simple_shell

This repository is created for Holberton School Colombia Students, the porpuose of this repository
is to hold a test suit for the Shell Project.

Some recommendations to contribute to the tests suit repo:
- Create a branch per team and work on your branch.
- Give your branch the name of the members in your group, example:
  "Robert-Martin".
- Put your test cases inside a folder.
- Give that folder a name that makes sense to everyone for instance:
 "ShellTest-task_0.1_[your-branch-name]".
  where the name of your folder should contain the number of task you're testing.
**UPDATE** 
Inside your script add some description that everyone can understand.
- After you're done with your contribution open a pull request to the branch master, please set either Robert Sebastian, Abdel Giovanny or Andres Martin to review your merge request.  

Remember this task is not mandatory, it's one of the advanced tasks, the idea is that everyone can contribute to the repository and earn extra points doing this task.
If you have some doubts, don't hesitate to contact us.
Have a great day!

1. type this in your prompt
`echo "qwerty" | ./shell`\
you should get :
`./shell: 1: qwerty: not found`
2. when you type `crtl + c ` it should not crash your shell\
expected output: `^C`
3. when you type `ctrl + d` your shell should be closed
4. if you type `ls -` or `ls +` you should get an error\
`ls: cannot access -: No such file or directory`
5. write a script that executes three times `ls` command
```sh
#!/bin/bash
ls && ls && ls
```
it should execute `ls` command three times.
