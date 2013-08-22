puppet-module-runner
====================

Run puppet modules without a top-level manifest.

Features
========

* Automatically discovers `include`-able modules
* Applies all modules installed on the system
* Detects configuration drift

Syntax
======

```
puppet-module-runner - Run puppet modules

Options:

  -h, --help
    Display this message

  -a, --apply
    Applies all modules

  -t, --test
    Runs all modules in noop mode
```
