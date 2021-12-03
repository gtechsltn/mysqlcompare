![Downloads](https://img.shields.io/packagist/dt/lloadout/mysqlcompare.svg?style=flat-square)

<p align="center">
    <img src="https://github.com/LLoadout/assets/blob/master/LLoadout_mysqlcompare.png" width="500" title="LLoadout logo">
</p>

# mysqlcompare
a command line tool to compare two mysql databases


## Requirements

mysqlcompare is a command line tool to compare two database schema's and retreive the difference in an sql file.

## Installation

```shell
composer global require lloadout/mysqlcompare
```

# Usage

## Init

Connection data can be defined in a connections.json file , to create the connection file you run the following command

```shell
mysqlcompare init
```

a `connections.json` file will be created , specifying a source and target connection and an sqlfile to store the sql statements in.

## Compare

The execution of comparison is done via 

```shell
mysqlcompare compare
```
