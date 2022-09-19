# Shadowrocket Rules

DIRECT-IP: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-ip.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-ip.txt)

DIRECT-NAME: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt)

REJECT: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt)

PROXY: [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt)

MMDB(CN): [https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/Country.mmdb](https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/Country.mmdb)

## Example

```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/reject.txt,REJECT
DOMAIN-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/direct-name.txt,DIRECT

RULE-SET,https://gita.cool/carrnot/shadowrocket-rules/release/direct-ip.txt,DIRECT,no-resolve
# GEOIP,CN,DIRECT

# Add this rule to save a DNS lookup
DOMAIN-SET,https://raw.githubusercontent.com/carrnot/shadowrocket-rules/release/proxy.txt,PROXY

FINAL,PROXY
```

## Credits

* [https://github.com/carrnot/china-ip-list](https://github.com/carrnot/china-ip-list)
* [https://github.com/carrnot/china-domain-list](https://github.com/carrnot/china-domain-list)
* [https://github.com/carrnot/dnscrypt-proxy-ads](https://github.com/carrnot/dnscrypt-proxy-ads)
* [https://github.com/v2fly/domain-list-community](https://github.com/v2fly/domain-list-community/tree/release)
