# Custom-linux-shell

Developed an application shell functioning atop the Linux kernel, accepting user commands for execution. Key functionalities encompass:

a) Executing external commands stored as files, involving child processes and system calls like execlp().

b) Executing external commands with input redirection from files using "<."

c) Executing external commands with output redirection to files using ">".

d) Combining input and output redirection ("<" and ">").

e) Running commands in the background with possible input/output redirection.

f) Executing multiple commands in pipe mode with standard output redirection.

g) Implementing command interruption using signal calls (Ctrl-C) and moving commands to the background (Ctrl-Z).

h) Creating a searchable shell history of 10,000 commands, accessible via the "history" command for the most recent 1,000 commands.

i) Implementing file name auto-complete for the working directory.
