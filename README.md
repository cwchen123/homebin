# Michael's homebin

My own handy scripts.

## Usage

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

### mail

Send mail by Mailgun Ruby API.  You need a personal domain and a Mailgun account to use the script.  Besides, set the two environment variable **MAILGUN_API_KEY** and **MAILGUN_DOMAIN**.

## License

MIT
