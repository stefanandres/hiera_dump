# hiera_dump
Dump all hiera variables for a specific node
It only works for the hiera yaml backend. It may work with hiera-eyaml, will probably fail for hiera-gpg at the moment.

## Usage
### install
```
git clone https://github.com/stefanandres/hiera_dump.git
PATH=$PWD:$PATH
```

### use
- Dump all local variables
```
./hiera_dump
```

- Dump all variables for specific node by facts
```
./hiera_dump fqdn=myhost.com osfamily=RedHat
```

- Dump all variables including the files where they originated from
```
./hiera_dump -s
```



