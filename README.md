# UPM

The Universe Package Manager is a package manager for multivalue. Currently it only supports installing the latest packages and packages that are all in a single file.

## Installation Instructions

Get the UPM file.

```
$ curl https://raw.githubusercontent.com/Krowemoh/upm/main/UPM -o /home/SYSPROG/MPROCLIB/UPM
```

In UniVerse or D3, compile and catalog the program.

```
> LOGTO SYSPROG
> BASIC BP UPM
> CATALOG BP UPM
```

Make sure it is installed.

```
> UPM SHOW UPM
```
