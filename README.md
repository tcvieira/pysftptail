             ___________ ___________ _        _ _ 
            /  ___|  ___|_   _| ___ \ |      (_) |
 _ __  _   _\ `--.| |_    | | | |_/ / |_ __ _ _| |
| '_ \| | | |`--. \  _|   | | |  __/| __/ _` | | |
| |_) | |_| /\__/ / |     | | | |   | || (_| | | |
| .__/ \__, \____/\_|     \_/ \_|    \__\__,_|_|_|
| |     __/ |                                     
|_|    |___/                                      

# pysftp-tail
pySFTP-tail is a Python3 implementaion of the tail command over a sftp connection

# Usage

```
# pysftptail script

python3 pysftptail.py -h host -u username -p password -n 5

Usage: pysftptail.py [OPTIONS] FILE_PATH

Options:
  -h, --host TEXT      SFTP host server, prompted if omitted.
  -u, --username TEXT  SFTP username, prompted if omitted.
  -p, --password TEXT  SFTP password, prompted if omitted.
  -n, --lines INTEGER  Output the last n lines.  [default: 5]
  -f, --follow         Output data as the file grows.
  --version            Show the version and exit.
  --help               Show this message and exit.

# Execute tests
pytest

```
