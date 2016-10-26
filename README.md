# Paco

This project uses Git Submodules to include the core LSTFilter library:
https://git-scm.com/book/en/v2/Git-Tools-Submodules

When you clone the repo, you will get the Paco source files and the directory containing the LSTFilter repo, but none of the files contained within.  The get the files contained therein, run the following commands:

```git submodule init```

```git submodule update```
