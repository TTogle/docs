title: goal clerk dryrun
---
## goal clerk dryrun



Test a program offline



### Synopsis

!!! warning
    As of AVMv8, `dryrun` will no longer work with any contract that uses box storage. A new endpoint that will replace `dryrun` is currently in development.

Test a TEAL program offline under various conditions and verbosity.



```

goal clerk dryrun [flags]

```



### Options



```

      --dryrun-accounts strings     additional accounts to include into dryrun request obj

      --dryrun-dump                 Dump in dryrun format acceptable by dryrun REST api instead of running

      --dryrun-dump-format string   Dryrun dump format: json, msgp (default "json")

  -h, --help                        help for dryrun

  -o, --outfile string              Filename for writing dryrun state object

  -P, --proto string                consensus protocol version id string

  -t, --txfile string               transaction or transaction-group to test

```



### Options inherited from parent commands



```

  -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation

```



### SEE ALSO



* [goal clerk](../../clerk/clerk/)	 - Provides the tools to control transactions 



