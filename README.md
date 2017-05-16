# initial

## Installation

Download and save the script

```
wget -P /usr/local/bin https://raw.githubusercontent.com/ianklemm/initial/master/initial
```

```
chmod u+x /usr/local/bin/initial
```

## Usage

```
initial [IP] [FQDN]
```

```
initial  192.0.2.10 srv.mydomain.tld
```
    
The following entries will be inserted to the config files:  
address: 192.0.2.10  
gateway: 192.0.2.1  
hostname: srv.mydomain.tld  


## Warning

Remove the existing address and gateway entries in the ```/etc/network/interfaces``` as well as the hostname in the ```/etc/hosts``` and ```/etc/hostname```
