# 示例配置
```
[General]
internet-test-url = http://cn.aliyun.com
proxy-test-url = http://cp.cloudflare.com/generate_204

[Proxy Group]
Proxy = smart, policy-path=订阅链接, policy-priority=香:0.2;台:0.4;新:0.6;日:0.8;美:1.2

[Rule]
RULE-SET,http://github/Bilibili,Proxy
RULE-SET,http://github/Apple,DIRECT
RULE-SET,LAN,DIRECT
FINAL,Proxy

[URL Rewrite]
^https?://(www.)?(g|google)\.cn https://www.google.com header
^http://github/(.*?)$ https://github.com/Anchen520i/Dynamic/raw/Surge/$1.list 302

[MITM]
client-source-address = 127.0.0.1
```
