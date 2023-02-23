# Shadowrocket Rules

DIRECT-IP: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-ip.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-ip.txt)

DIRECT-NAME: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt)

REJECT: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt)

PROXY: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt)

MMDB(CN): [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/Country.mmdb](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/Country.mmdb)

HOSTS(CN): [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/hosts.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/hosts.txt)

## Example

```
[Rule]
RULE-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt,REJECT
DOMAIN-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt,DIRECT

GEOIP,CN,DIRECT
# RULE-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-ip.txt,DIRECT

# Add this rule to save a DNS lookup
RULE-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt,PROXY

FINAL,PROXY
```

## Credits

* [https://github.com/carrnot/china-ip-list](https://github.com/carrnot/china-ip-list)
* [https://github.com/carrnot/china-domain-list](https://github.com/carrnot/china-domain-list)
* [https://github.com/bigdargon/hostsVN](https://github.com/bigdargon/hostsVN)
* [https://github.com/v2fly/domain-list-community](https://github.com/v2fly/domain-list-community/tree/release)
