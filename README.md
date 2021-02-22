# ibviewer2
Tool to list switches, hosts and links in an infiniband fabric.

## Usage
```
usage: ibviewer2 [options] command

IB Fabric viewer!

positional arguments:
  {listswitches,listhosts,switch,host,json-dump}
                        Command to execute

optional arguments:
  -h, --help            show this help message and exit
  --id ID               IB identifier
  --name NAME           IB name
  --linked-switches     show linked switches
  --linked-hosts        show linked hosts
  --ibnetdiscover-input PATH
                        A file containing the output of `ibnetdiscover`
  --json-import PATH    json dump to import
  --json-export PATH    json dump to export
  --cmd-path PATH       The alternative path to the `ibnetdiscover` program
  --cmd-args ARGS       Additional arguments to be passed to the `ibnetdiscover` program (needs to be quoted)
  --no-header           Disable header lines for lists
```
