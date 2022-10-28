# Tinney-Unix-Operating-System-Shell
Tiny Shell:
<br />eval — the main routine, which parses and interprets the command line
<br />builtin_cmd — recognizes and interprets the built-in commands: quit, fg, bg, and jobs
<br />do_bg — implements the bg built-in command
<br />do_fg — implements the fg built-in command
<br />waitfg — waits for a foreground job to complete or change its state
<br />sigchld_handler — catches SIGCHLD signals
<br />sigint_handler — catches SIGINT (ctrl-c) signals
<br />sigtstp_handler — catches SIGTSTP (ctrl-z) signals
<br /><img width="574" alt="Tiny_Shell" src="https://user-images.githubusercontent.com/95834784/187071821-ede5bdd7-73b5-48a4-8963-b2e46675934e.png">
