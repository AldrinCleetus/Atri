# Altri

To run:

```console
$ node shell.js
```

## Supported Commands: 

Lists all the files in the working directory

```console
$> ls 
```

Prints the current working directory

```console
$> pwd 
```

Executes the binary with arguments

```console
$> <path_to_binary> <args> 
```

Example: 

```console
$> bash testBashScript.sh 
```
```console
$> node test.js
```

Sends the process matching the id from background to foreground

```console
$> fg <process_id>
```

## Supported Key Events

CTRL + Z : Sends the active process to background (Only works in Linux currently)

CTRL + C : Kills the active program

## References Used

- [Nodejs - Readline](https://nodejs.org/api/readline.html)
- [Nodejs - ChildProcess](https://nodejs.org/api/child_process.html)
- [Linux signals](https://man7.org/linux/man-pages/man7/signal.7.html)
- [Foreground Process vs Background Process - Linux ](https://linuxconfig.org/understanding-foreground-and-background-linux-processes)