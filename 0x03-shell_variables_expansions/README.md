0x03. Shell, Variables, and Expansions
This directory contains solutions for the shell scripting tasks in the ALX System Engineering DevOps curriculum, focusing on shell variables, environment variables, and command expansions.
Tasks

0-alias: Creates an alias ls='rm *'.
1-hello_you: Prints hello followed by the current Linux username.
2-path: Adds /action to the end of the PATH environment variable.
3-paths: Counts the number of directories in the PATH.
4-global_variables: Lists all environment variables.
5-local_variables: Lists all local variables, environment variables, and functions.
6-create_local_variable: Creates a local variable BEST="School".
7-create_global_variable: Creates a global variable BEST="School".
8-true_knowledge: Adds 128 to the value of the environment variable TRUEKNOWLEDGE.
9-divide_and_rule: Divides the environment variable POWER by DIVIDE.
10-love_exponent_breath: Raises the environment variable BREATH to the power of LOVE.
11-binary_to_decimal: Converts a binary number in BINARY to decimal.
12-combinations: Prints all two-letter combinations (except oo) in alphabetical order.
13-print_float: Prints a number in NUM with two decimal places.

Setup

Clone the repository:
git clone https://github.com/<your-username>/alx-system_engineering-devops.git
cd alx-system_engineering-devops/0x03-shell_variables_expansions


Make scripts executable:
chmod +x *


Test scripts (e.g., for Task 0, in a safe directory):
mkdir test_dir
cd test_dir
touch file1 file2
source ../0-alias
ls  # Deletes files (caution!)
\ls  # Lists remaining files


