hello-world
===========

A test Hello World repository

This additional paragraph makes the README better.


Syntax Highlighting
-------------------

Using GitHub's triple backtick syntax for code blocks:

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

Using the more common triple tilde syntax for code blocks:

~~~ bash
$ make
$ make install

# Enable custom bash completions:
if [ -d ~/.bash_completion.d ]; then
    for f in ~/.bash_completion.d/*.sh; do
        . "$f"
    done
    unset f
fi
~~~


Fenced Code Blocks in Lists (and Nested Lists)
----------------------------------------------

1.  This is code:

    ```bash
    $ cd ~/Desktop && ls -l
    ```

2.  This is the exact same thing:

    ```bash
    $ cd ~/Desktop && ls -l
    ```

    Does GitHub render nested lists correctly or does it have the Redcarpet
    3.2.1 bug (230)?

    * item 1

    * item 2

    * item 3

3.  Using regular Markdown indentation instead of fenced code blocks:

        $ cd ~/Desktop && ls -l

That's it.


Relative links in READMEs
-------------------------

See [file](file.md).

See [file].

  [file]: file.md


SmartyPants
-----------

Em dash --- usually three ASCII dashes

En dash -- usually two ASCII dashes like 2014--2015.

