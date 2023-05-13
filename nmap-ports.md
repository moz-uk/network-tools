# nmap stuff

1. scan a specific set of ports
1. define ports within a file
1. customize name of ports/service names
1. multiple targets within files
  1. documents
  2. applicaton

we want to do the following
- dont do a ping to check the target is up
- print to screen pass/fail

```bash
nmap -Pn   // dont ping to see if the target is up
```

```bash
nmap -p T:33962,33966,33969 // TCP list of ports to scan
```

```bash
namp  // read in list of targets to scan
```

## investigate
what is              -PS/PA/PU/PY[portlist]: TCP SYN/ACK, UDP or SCTP discovery to given ports
custom nmap-services file
--servicedb *servicesfile*   // this uses -F fast scan


