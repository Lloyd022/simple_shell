simple_shell is a command line interpreter. The shell has a prompt($) and it is displayed again each time a command has been executed. This is a project made for the ALX software engineering program, project 0x16. C - Simple Shell.

File Structure
File Name	Description and contents
man_1_simple_shell	This is the manpage for the simple_shell, where we can find examples and the correct syntax of the commands.
shell.h	This is the header file with the struct and prototypes of the functions.
shell.c	main function - Prints the prompt in a loop and calls the functions to accept arguments and executes the command.
AUTHORS	List of contributors to this repository.
_dollar_special.c	the function - Returns the address at which EXIT_CODE is stored and Sets the value for EXIT_CODE var.
_get_history_lines_count.c	the function - Counts the lines in a previo and Returns the lines count of history file.
_getenv.c	the function - Returns a pointer to a env var value.
_handle_var_replacement.c	the function - Handles dollar vars '$'.
_help.c	the function - print a line of fd.
_history.c	the function - Return the address of history head.
_own_memory.c	the function - Reallocates a memory block.
_puts.c	the function - Prints a string to stdout.
_strcpy.c	the function - Copies the string source to destination.
_strncpy.c	the function - Copies n amount of string.
_strtok.c	the function - Divides a string into tokens.
_write_history.c	the function - Writes the history to a file in home dir.
alias_list.c	the function - Checks if the alias input is meant to set an alias.
builtin_utils.c	the function - Validates a env var name.
builtins.c	the functions - Prints the environment variables to stdout, Sets or adds an environment variable and Removes an evironment variable.
f_command_handlers.c	the functions - Buidls an array of strings as arguments, Counts the number of arguments in a command string, Checks if the command to execute could be found in PATH's dirs and Creates a string representing a full path to file.
f_error.c	the function - Dispatches an error.
f_exit.c	the function - Checks if the user entered the exit command.
f_handle_builtins.c	the function - Executes the builtin funtions in case the command is one.
f_handle_comment.c	the function - deletes a comment from the buffer.
f_handle_enter.c	the function - Check if no command was entered.
f_handle_shell_logical_operators.c	the function - Handle semicolon and logical op, Handles
f_linked_lists.c	the function - Print the lists and add a new node at the end.
f_memory.c	the function - Manages the memory allocation.
f_special.c	the function - Builds the "env vars" array using dynamic memory.
f_strings.c	the function - copy a strings with a malloc, Convert a number to string format and returns the length of a string.
f_strings_creation.c	the function - concatenates string substract a paragraph.
f_strings2.c	the function - for string scanning operation.
