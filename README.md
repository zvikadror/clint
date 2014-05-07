clint
=====

Command Line Interactive Navigation Tool

Summary:
When you have command line parameters, you can run the same tool with -i (interactive).
If using a wrapper, ANY CLI tool can be executed against a resource file to interactively select commands and parameters.

>> Aiming for multi-platform script (PHP / Python / Ruby) called natively by bash and batch (Windows) <<

This will include clint library, which will parse a params file and load ascii menu with params to toggle or input.

clicking on 1 for example, will toggle a 'v' near "1. option name", clicking 1 again will toggle it off.
clicking on an option with input will toggle input field.

clicking on 0, or x, or 99, will start execution with the toggled options as commandline parameters.
