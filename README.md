# ezsql-mysqli #
This is forking from the Justin Vincent's ezSQL, with only selected: mysqli.
$ Added prepare() function from wpdb ~ (Prepares a SQL query for safe execution. Uses sprintf()-like syntax.)

To see full range SQL supported, please visit 

http://justinvincent.com/ezsql

https://github.com/ezSQL/ezSQL


## Add reference to this repo in composer.json ##
```
    ...
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/kidzen/ezsql-mysqli"
        }
    ]
    ...

```

## Run via composer ##

```
$ composer require sunaryohadi/ezsql-mysqli
```


