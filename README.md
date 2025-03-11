Custom Shell Project
====================

Overview:
---------
This project is a simple Unix shell that supports:
  - Simple commands (e.g., echo hello)
  - Conditionals (using && and ||)
  - Pipelines (using |)
  - Background commands (using &)
  - Redirections (<, >, 2>)
  - Built-in command: cd

Getting Started:
----------------
1. Prerequisites:
   - Unix-like system (Linux, macOS, etc.)
   - GNU Make
   - A C/C++ compiler

2. Clone the repository:
      git clone <repository-url>
      cd <repository-directory>

3. (Optional) Merge latest code (if needed):
      git pull handout main

4. Build the project:
      make

Running the Shell:
------------------
To start the shell, run:
      ./sh61

When at the prompt, you can enter commands. To exit the shell, press Ctrl-D.

Testing:
--------
You can run tests to verify your shell implementation:

  - Simple Commands:
        make check-simple
  - Command Lists:
        make check-list
  - Conditionals:
        make check-cond
  - Pipelines:
        make check-pipe
  - Background Commands:
        make check-bg
  - Zombie Processes:
        make check-zombie
  - Redirections:
        make check-redir
  - cd Command:
        make check-cd

To run all tests at once:
      make check

