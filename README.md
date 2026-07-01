# no
Fork of the C implementation of the github repo mubaris/yes, but it outputs n rather than y
# Compile
Download the no.c file and run

```gcc -o no no.c```
# Install
With the compiled no executable, run

```sudo install no /usr/bin```
# Usage
Just like the original yes command, no is used by piping the no command to the command you want to run, as shown in this example:

```no | command-where-you-answer-a-lot-of-questions```

You can also specify a specific output, like this:



```no y | another-command-where-you-answer-a-lot-of-questions```

Dedicated to grandma
