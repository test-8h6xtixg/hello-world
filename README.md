hello-world
===========

A test Hello World repository

This additional paragraph makes the README better.


Syntax Highlighting
-------------------

```bash
$ make
$ make install

# Enable custom bash completions:
if [ -d ~/.bash_completion.d ]; then
    for f in ~/.bash_completion.d/*.sh; do
        . "$f"
    done
    unset f
fi
```


Fenced Code Blocks in Lists
---------------------------

1.  This is code:

    ```bash
    $ cd ~/Desktop && ls -l
    ```

2.  This is the exact same thing:

    ```bash
    $ cd ~/Desktop && ls -l
    ```

3.  Using regular Markdown indentation instead of fenced code blocks:

        $ cd ~/Desktop && ls -l

That's it.


Relative links in READMEs
-------------------------

See [file](file.md).

See [file].

  [file]: file.md

