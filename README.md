# cols
forget using awk to extract columnar data... 

Just say which columns you want to see... 

ps -ef | cols 1,4

# Usage
```
usage: cols [-h] [--delim DELIM] [--replace REPLACE] [--skip-first SKIP_FIRST] [--not] cols

this is to address a frustration with using awk and cut

positional arguments:
  cols                  the columns you want to display

optional arguments:
  -h, --help            show this help message and exit
  --delim DELIM, -d DELIM
                        delimiter string
  --replace REPLACE, -r REPLACE
                        replace X with Y: e.g. --replace "\s \t" to replace all spaces with tabs
  --skip-first SKIP_FIRST, --skip SKIP_FIRST
                        skip first N lines; omit a header
  --not, -n, --hide     show all columns except these columns; hide these cols

```
