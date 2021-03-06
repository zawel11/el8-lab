# All Open Enterprise Linux 8 Labs

Welcome to All Open Enterprise Linux 8 Labs!

If you have not already, read [the main page](/) first.

## Usage

RPM provides `all-open-lab` command capable of listing, preparing and grading labs.

To get help use no params:
```console
Usage:
/usr/bin/all-open-lab list              # list labs
/usr/bin/all-open-lab setup <lab-name>  # prepare system for <lab-name> lab
/usr/bin/all-open-lab grade <lab-name>  # grade <lab-name> lab
```

To list of available labs type:
```console
# all-open-lab list
(...)
```

In order to prepare your system for a given lab :
```console
# all-open-lab setup <lab-name>
```

After you complete the lab check results with:
```console
# all-open-lab grade <lab-name>
```

## `bash-completion`
To make your live easier `<tab>` completion thanks to `bash-completion` works!

If it does not:

* Close and open you console session
* Make sure you have `bash-completion` RPM installed
