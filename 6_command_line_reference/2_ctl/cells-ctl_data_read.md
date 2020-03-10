## cells-ctl data read

Reads information about an indexed node

### Synopsis

Reads information about an indexed node.

This will grab all information for a given node in indexed. If going through the tree service, it will also
compute metadata stored for this node.


```
cells-ctl data read [flags]
```

### Options

```
  -h, --help          help for read
  -p, --path string   Path to the data
  -u, --uuid string   UUID of the data
```

### Options inherited from parent commands

```
      --registry string   Registry used to manage services (default "nats")
      --source string     Source where the data resides
```

### SEE ALSO

* [cells-ctl data](cells-ctl-data)	 - Commands for managing indexed data

###### Auto generated by spf13/cobra on 19-Jun-2018