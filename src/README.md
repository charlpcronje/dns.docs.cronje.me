```sh
______ _   _  _____     _                 _____ ______ _____ _   _ _       ___  ___ _____ 
|  _  \ \ | |/  ___|   | |               /  __ \| ___ \  _  | \ | (_)      |  \/  ||  ___|
| | | |  \| |\ `--.  __| | ___   ___ ___ | /  \/| |_/ / | | |  \| |_  ___  | .  . || |__  
| | | | . ` | `--. \/ _` |/ _ \ / __/ __|| |    |    /| | | | . ` | |/ _ \ | |\/| ||  __| 
| |/ /| |\  |/\__/ / (_| | (_) | (__\__ \| \__/\| |\ \\ \_/ / |\  | |  __/_| |  | || |___ 
|___/ \_| \_/\____(_)__,_|\___/ \___|___(_)____/\_| \_|\___/\_| \_/ |\___(_)_|  |_/\____/ 
                                                                 _/ |                     
                                                                |__/                      
01000100 01001110 01010011 00101110 01100100 01101111 01100011 01110011 00101110 01000011 
01010010 01001111 01001110 01101010 01100101 00101110 01001101 01000101 
```

- This repo will become a sub-module of docs.CRONje.ME.
- Go to [./src/README.md](./src/README.md) for the root of this repo

# DNS Records

## Name Servers

The server where your domain's DNS Records are hosted, they usually look something like this:

- ns11.domaincontrol.com
- ns12.domaincontrol.com

or

jeff.ns.cloudflare.com
anne.ns.cloudflare.com

## DNS Categories

### Website Records -  (A Records)

These records a few fields

- IP Address
- Domain Name
- TTL - Time to live (How long the records will stay cached)

So basically for each domain there is a correspondingly IP Address for the server it is pointing to

### Mail Records - (MX Records)

This stands for mail Exchange Records, there are 2 - 5 Records for these

They can look something like this for Google Suite for example:

- aspmx.l.google.com
- alt1.aspmx.l.google.com
- alt2.aspmx.l.google.com
- alt3.aspmx.l.google.com
- alt4.aspmx.l.google.com

There are also a few fields

- TTL (Time to live)
- Name
- IP Address
- Priority

### CName Records

- The cname records are redirects
- Wildcard * is the wildcard and you can point
- *.devserv.com to devserv.com, all undefined sub-domains will point to the main domain

### Informational Records - (TXT Records)

This can be any data, can be used to verify the domain

## Tools for DNS

- [MX Toolbox](http://mxtoolbox.com)