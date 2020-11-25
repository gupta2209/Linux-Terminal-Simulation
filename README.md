# Linux-Terminal-Simulation
Simulated bash shell with our own shell that can implement following Linux commands:
(A) Basic terminal navigation commands:
    a. ls (option: -a)
    b. cd
(B) Displaying the file content on the terminal:
    a. cat (option: -n)
(C) File and directory manipulation commands:
    a. mkdir (option: -m)
    b. cp (option: -u)
(D) Sort and filter data commands:
    a. sort (option: -r)
    b. grep (option: -n)

I. The shell looks exactly like normal linux terminal, where user can enter the
commands from standard input followed by its arguments.
II.The prompt should look exactly like linux shell prompt showing its current working
directory. (eg: user@system_pc:~$).
III. Any illegal command or unrecognized argument shows a meaningful error to the user
without crashing the shell.
IV. The shell also support exit command to smoothly exit the shell by printing a
meaningful message without forcefully exiting the process.
V. The shell also support up and down arrows and should implement command
history.


Dependency:
git clone https://github.com/jamiejennings/rosie-pattern-language.git
cd rosie-pattern-language/
make

Requirements:

Operating System: Ubuntu
Compiler: gcc

Compile:

g++ Linux_term_sim.cpp -w -lreadli

Run:

./a.out

