# git-worklog

`git-worklog` simplifies searching the commit history within a range of dates.

# Installation
Place the `git-worklog` executable somewhere in your `PATH`. It will then be
available through `git worklog`.

> **PRO TIP**
> Run `git worklog help` after installation to confirm everything works!


# USAGE

```
USAGE
    git worklog [help] [OPTIONS] START_DATE [END_DATE]

ARGUMENTS
    help
        Displays this message. This must be the first argument passed
        to git-worklog, e.g. 'git worklog help'

    START_DATE
        A date or string representative of a date.

    END_DATE
        optional
        A date or string representative of a date.

        If this argument is provided, commits made
        from the beginning of START_DATE until the end of END_DATE
        will be retrieved.

        If this argument is not provided, only commits made on the given
        START_DATE will be retrieved.

OPTIONS
    -d, --debug
        Print debugging information

    -a AUTHOR, --author AUTHOR
        Instead of auto-detecting the git author, use AUTHOR

    -s, --subjects-only
        Only show the commit message's first line
```
