Stuff (Simple CLI Password Manager)
=======================

Stuff is a Python library for managing your own passwords in a CLI-based manner.


## Description

This library was first created to satisfy my own needs of handling my passwords. Because
I tend to change my passwords pretty frequently I usually find myself in a position of 
having to reset them kinda often.


## How it works and what it does

Each time you run a command, you'll have to enter your database password. This is the only
password that you'll have to remember so make sure it's a **strong** one! Behind the
scenes, Stuff will do changes to this database. One important thing to keep in mind is
that the passwords **ARE STORED IN CLEAR TEXT**. I don't expect this to get to much
attention but if it will, I'll eventually add a way to securely encrypt everything.

You can do the following:

* List all your passwords
* Delete all your passwords
* Create a new password
* Update an existing password
* Retrieve an existing password
* Delete an existing password


## Usage

```shell script
Usage: cli.py [OPTIONS] COMMAND [ARGS]...

  Simple CLI Password manager for personal use

Options:
  --help  Show this message and exit.

Commands:
  all     List all credentials.
  create  Create a new credential with a specific name and password.
  delete  Delete a specific credential by name.
  get     Get a specific credential by name.
  purge   Purge all credentials.
  update  Update a credential field matching a specific condition with a
          new value


All the arguments are mutually exclusive
```

**Pull requests are encouraged!**

License
-------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any means.