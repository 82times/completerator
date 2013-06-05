##A tab-completion generation tool
Basic tool for generating a bash completion function based on a command
name and a list of arguments for that command.

Usage:

    completerator foo verb_list.txt > foo_completion.bash
    source foo_completion.bash

So far, this will only give you first-level completions for the "verbs"
listed in the file passed as the second argument.

##Contributions
This is a real back-of-the-napkin implementation. My hope is to make
this full-featured and robust. Contributions are welcome!
