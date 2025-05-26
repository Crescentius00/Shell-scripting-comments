# Shell-scripting-comments

## Comments

A comment in shell scripting is a line or part of a line that is ignored by the computer when the script runs. It's written only for humans to read.

Comments are used to explain code, making it easier to understand and maintain. They are not executed by the shell.

They are used to document what the script does, why decisions were made, or how tricky parts work.

Comments are usually started with '#'

### Single-line Comments

The screenshot below illustrates single-line comments as used in a script.

![](./img/1.single-line.png)

When the script is executed, the line that started with '#' was not executed.

![](./img/2.execute_single-line.png)

### Multiple Single-line Comments

To comment multiple lines, each line is started with '#' as illustrated below:

![](./img/3.multiple-line.png)

When the script is executed all the lines starting with '#' are ommited by the interpreter.

![](./img/4.execute_multiple-line.png)