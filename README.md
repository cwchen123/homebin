# Michael's homebin

My own handy scripts.

## Usage

Add the *bin* sub-directory to PATH variable.

## Available Commands

### bitly

(Deprecated) Generate short url.  Two environment variables **BITLY_USERNAME** and  **BITLY_API_KEY** are needed to use the command.

### check

Check whether a process is running.  `grep` is excluded.

### elisp

Use Emacs as an interpreter.  By default, error message is suppressed.

```
# Show stdout only.
$ elisp script.el

# Show stdout and stderr.
$ DEBUG=1 elisp script.el
```

### mailto

Send mail by Mailgun Ruby API.  You need a personal domain and a Mailgun account to use the script.  Besides, set the two environment variable **MAILGUN_API_KEY** and **MAILGUN_DOMAIN**.

### pid

Check the pid of the process by name.  Use `check` internally.

### podweb

Call `podwebserver` if no podwebserver process initiated.  Perl module `Pod-Webserver` needed.

### removepkg

Remove pkg package on Mac.

### start

Start a persisting background process.  It changes to home root directory and left log files there.  Use the command `pid` internally.

### stop

Stop a persisting background process.  Use the command `pid` internally.

## License

MIT
