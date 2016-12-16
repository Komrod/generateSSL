# generateSSL

A simple script to automatically generate local SSL files
Require commands "openssl" and "hostname".

# use

```
./generateSSL.sh
```

This command will generate "test.key" and "test.crt" on the hostname of the current server.

You can add parameters for additional features :
- first parameter is the directory output for the files
- second parameter is the name of the files, default "test"

```
./generateSSL.sh ssl/ iamgroot
```
This command will generate in the directory "ssl/" the files "iamgroot.key" and "iamgroot.crt".


