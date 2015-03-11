# hiera_dump
Dump all hiera variables for a specific node

## Usage
### install
```
git clone git@github.com:stefanandres/hiera_dump.git
PATH=$PWD:$PATH
```

### use
- Dump all local variables
```
./hiera_dump
```

- Dump all variables for specific node by facts
```
./hiera_dump fqdn=myhost.com
```

- Dump all variables including the files where they originated from
```
./hiera_dump -s
```



