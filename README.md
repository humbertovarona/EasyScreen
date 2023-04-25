# EasyScreen

# Version

1.0

# Release date

March, 14 2017

# DOI

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7864685.svg)](https://doi.org/10.5281/zenodo.7864685)


# License

MIT

# Description

Bash scripts that facilitate the use of the "screen" command through names

# How to install

```sh
# tar -xvf EasyScreen.tar.gz -C /home/user/bin
# chmod +x /home/user/bin/newscr
# chmod +x /home/user/bin/connscr
# chmod +x /home/user/bin/delscr
# nano ~/.bashrc

export PATH = $PATH:$HOME/bin

# source ~/.bashrc
```

# How to run

## Create a screen called "TEST1" and another "Simulation"

```sh
# newscr TEST1 <Enter>
# newscr Simulation <Enter>
```

## List the created screens

```sh
# screen -ls <Enter>

There are screens on:
        12099.Simulation        (04/25/2023 04:37:29 PM)        (Detached)
        11975.TEST1     (04/25/2023 04:37:20 PM)        (Detached)
```

## To reconnect to a screen

```sh
# connscr TEST1 <Enter>
# connscr Simulation <Enter>
```

## To delete a screen

```sh
# delscr TEST1 <Enter>
# delscr Simulation <Enter>
```

# Cite as

Humberto L. Varona (2023). EasyScreen. (1.0). Zenodo. https://doi.org/10.5281/zenodo.7864685
 
