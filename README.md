# Ajanu  

# A basic template for shell scripts

This repository as a whole is a template of shell scripts and configuration files that I use when I start to write some bash shells. The reason of this template is to avoid re-write similar structure of scripts, and instead pull this template and make the modification as the project needs.

It represents a reference only as every project is different. However, there are common features that can be re-used by downloading.

# Test

```bash
$ sh main.sh
```

# Expected output

```bash

Usage: main.sh [-hv] [-o[file]] args ...

 SYNOPSIS
    main.sh [-hv] [-o[file]] args ...

 DESCRIPTION
    This is a script template
    to start any good shell script.

 OPTIONS
    -o [file], --output=[file]    Set log file (default=/dev/null)
                                  use DEFAULT keyword to autoname file
                                  The default value is /dev/null.
    -t, --timelog                 Add timestamp to log ("+%y/%m/%d@%H:%M:%S")
    -x, --ignorelock              Ignore if lock file exists
    -h, --help                    Print this help
    -v, --version                 Print script information

 EXAMPLES
    main.sh -o DEFAULT arg1 arg2

 IMPLEMENTATION
    version         main.sh (www.uxora.com) 0.0.4
    author          Michel VONGVILAY
    copyright       Copyright (c) http://www.uxora.com
    license         GNU General Public License
    script_id       12345


 IMPLEMENTATION
    version         main.sh (www.uxora.com) 0.0.4
    author          Michel VONGVILAY
    copyright       Copyright (c) http://www.uxora.com
    license         GNU General Public License
    script_id       12345

```

# References

The content of these files are a mix of my own thoughts and what I could find on internet  such as the one for the usage, which credits goes to the following [link](https://stackoverflow.com/questions/430078/shell-script-templates)
