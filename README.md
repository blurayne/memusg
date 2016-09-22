
# Note

Just forked to add output to file and CSV option.

The python script so far is thread safe (feel free to use it under nohup and so forth). 

# Original README.md

A 'time'-like utility for Unix that measures peak memory usage.

Works in both interactive and non-interactive environments.

Usage:

```bash
export PATH=$path_to_memusg
memusg my_command
```

Example:

```bash
memusg sleep 2
```
