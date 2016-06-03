## packet IP request-more

Request more IP space for a project in order to have additional IP addresses to assign to devices

### Synopsis


Request more IP space for a project in order to have additional IP addresses to assign to devices

```
packet IP request-more
```

### Options

```
      --comments string     Comment to Packet team
      --project-id string   Project ID
      --quantity int        How many IPv4 you want to request. Options: 1, 2, 4, 8, 16, 32, 64, 128, 256 (default 1)
      --type string         public_ipv4 || global_ipv4 (default "public_ipv4")
```

### Options inherited from parent commands

```
  -k, --key string   Specify the api key
```

### SEE ALSO
* [packet IP](packet_IP.md)	 - Manage device IP addresses

###### Auto generated by spf13/cobra on 4-Jun-2016