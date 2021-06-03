# Proxy
HTTP proxy server written with python.

### Launching

Run 'main.py -p *port*', where *port* is number of port to run proxy.

Optional arguments: -mc for max connections, -dbl for domain blacklist.

Run 'main.py -h' for help.
  
### Domain blacklisting

List domains (or parts of domains) in domain_blacklist.txt to block connection to them via proxy or use another file and pass it as -dbl argument.
