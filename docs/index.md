# pysftptail

pySFTPtail is a Python3 implementaion of the tail command over a sftp connection

For code visit [GitHub](https://github.com/tcvieira/pysftptail).

## Usage

    python3 pysftptail.py -h host -u username -p password -n 5

### Options

* `-h, --host TEXT` - SFTP host server, prompted if omitted.
* `-u, --username TEXT` - SFTP username, prompted if omitted.
* `-p, --password TEXT` - SFTP password, prompted if omitted.
* `-n, --lines INTEGER` - Output the last n lines.  [default: 5]
* `-f, --follow` - Output data as the file grows.
* `--version` - Show the version and exit.
* `--help ` - Show this message and exit.

## Tests
    pytest
