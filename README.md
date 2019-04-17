https://google.github.io/styleguide/shell.xml

# simple_shell
Simple Shell for Holberton School project.

ts_simple_shell


This command contains this code
1 |#!/bin/bash
2 |SHELL='./shell'
3 |echo exit | $SHELL | wc -l | awk '{ if($1 == 0) print "ok"; else print "ko"}'

Explanation:

The first line is the shebang,
The next line has a variable that indicate the file shell
The last line has the bash script that allow validate the command exit of your shell, if is correct this print 'ok' otherwise print 'ko'
=======
Some recommendations to contribute to the tests suit repo:
- Create a branch per team and work on your branch.
- Give your branch the name of the members in your group, example:
  "Robert-Martin".
- Put your test cases inside a folder.
- Give that folder a name that makes sense to everyone for instance:
 "ShellTest-task_0.1_[your-branch-name]".
  where the name of your folder should contain the number of task you're testing.
## **UPDATE** 
Inside your script add some description that everyone can understand.
- Create an **AUTHORS** file 
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

## For Help command

the help #advanced task, you need to implement the help command of sh
Simple shell 1.0 +

  - Implement the help built-in
  - Usage: help [BUILTIN]
  - Magic

# Test

The command
-       help
  - Display a usage message on standard output and exit successfully.

Display example 


      *MY SHELL HELP*
        Some information about your shell
        Bla Bla Bla
        description of commands implemented
        List of Commands supported:
        >pwd
        >ls
        >exit
        >etc 


-       -help-
  - should display nothing and [Your shell name]: 1: help: not found

-       echo "help" | [Your executable file]
  - Display a usage message on standard output and exit successfully.

-       help [BUILD-IN]
  - should display a message about your build-in function
=======

