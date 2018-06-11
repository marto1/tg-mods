Patches and scripts for telegram-cli.

exec_command.patch
==================

Allows you to run "!" command in telegram-cli.
`! <path to script> <arg>`

For example: `! ./send_photos MyChat`

Which will execute the script send_photos with chat#123123 as argument.


TODO
====

* TODO ! cmd variable arg parsing with composite tab completion
* TODO send all files in a folder
* TODO help strings for all script commands

