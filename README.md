# iOS示例配置
```
[General]
# 𝐃𝐍𝐒
dns-server = 223.5.5.5
doh-skip-cert-verification = true
use-local-host-item-for-proxy = true
encrypted-dns-follow-outbound-mode = true
# 𝐔𝐧𝐢𝐯𝐞𝐫𝐬𝐚𝐥
all-hybrid = false
wifi-assist = false
compatibility-mode = 0
# 𝐂𝐨𝐦𝐩𝐚𝐭𝐢𝐛𝐢𝐥𝐢𝐭𝐲 𝐌𝐨𝐝𝐞（𝐢𝐎𝐒 𝐨𝐧𝐥𝐲）
# 𝟎: 𝐀𝐮𝐭𝐨（旧版本为𝟏、新版本为𝟑）
# 𝟏: 𝐒𝐲𝐬𝐭𝐞𝐦 𝐏𝐫𝐨𝐱𝐲 𝐚𝐧𝐝 𝐕𝐈𝐅
# 𝟐: 𝐒𝐲𝐬𝐭𝐞𝐦 𝐏𝐫𝐨𝐱𝐲 𝐎𝐧𝐥𝐲
# 𝟑: 𝐕𝐈𝐅 𝐎𝐧𝐥𝐲
# 𝟒: 𝐒𝐲𝐬𝐭𝐞𝐦 𝐏𝐫𝐨𝐱𝐲（𝐯𝐢𝐚 𝐕𝐈𝐅）𝐚𝐧𝐝 𝐕𝐈𝐅
# 𝟓: 𝐒𝐲𝐬𝐭𝐞𝐦 𝐏𝐫𝐨𝐱𝐲 𝐚𝐧𝐝 𝐕𝐈𝐅（𝐍𝐨 𝐃𝐞𝐟𝐚𝐮𝐥𝐭 𝐑𝐨𝐮𝐭𝐞）
udp-priority = true
internet-test-url = http://cn.aliyun.com
proxy-test-url = http://cp.cloudflare.com/generate_204
test-timeout = 2
geoip-maxmind-url = https://github.com/Hackl0us/GeoIP2-CN/raw/release/Country.mmdb
disable-geoip-db-auto-update = false
ipv6 = false
ipv6-vif = disabled
# 𝐀𝐥𝐥𝐨𝐰 𝐖𝐢-𝐅𝐢 𝐀𝐜𝐜𝐞𝐬𝐬（𝐢𝐎𝐒 𝐨𝐧𝐥𝐲）
allow-wifi-access = false
allow-hotspot-access = false
wifi-access-http-port = 6152
wifi-access-http-auth = Anchen:0410
wifi-access-socks5-port = 6153
# 𝐀𝐱𝐭𝐞𝐫𝐧𝐚𝐥 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐥𝐞𝐫 𝐀𝐜𝐜𝐞𝐬𝐬
external-controller-access = 980114@0.0.0.0:6170
http-api = 980114@0.0.0.0:6171
http-api-tls = false
http-api-web-dashboard = true
# 𝐀𝐝𝐯𝐚𝐧𝐜𝐞𝐝
loglevel = notify
show-error-page-for-reject = true
always-real-ip = *.lan, *.direct, *.msftconnecttest.com, *.msftncsi.com, *.srv.nintendo.net, *.stun.playstation.net, xbox.*.microsoft.com, *.xboxlive.com, *.logon.battlenet.com.cn, *.logon.battle.net, stun.l.google.com
hijack-dns = *:53
force-http-engine-hosts = *:8443, *:8080
# 𝐄𝐥𝐬𝐞
include-apns = false
hide-vpn-icon = false
read-etc-hosts = true
include-all-networks = false
include-local-networks = false
exclude-simple-hostnames = true
include-cellular-services = false
udp-policy-not-supported-behaviour = 𝐑𝐞𝐟𝐮𝐬𝐞

[Ponte]
client-proxy-name = 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠

[Proxy]
𝐃𝐢𝐫𝐞𝐜𝐭 = direct
𝐑𝐞𝐟𝐮𝐬𝐞 = reject

[Proxy Group]
𝐎𝐜𝐭𝐨𝐩𝐮𝐬 = smart, policy-path=订阅链接, policy-priority=香:0.5;台:0.6;新:0.7;日:0.8;美:0.9, icon-url=https://raw.githubusercontent.com/Irrucky/Tool/main/Surge/icon/surge1.png
𝐁𝐢𝐥𝐢𝐛𝐢𝐥𝐢 = select, 𝐃𝐢𝐫𝐞𝐜𝐭, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, icon-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/bilibili_3.png
𝐂𝐥𝐚𝐮𝐝𝐞 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞, icon-url=https://raw.githubusercontent.com/black2c7/TheMagic-Icons/main/Icons/UNI3.png
𝐂𝐨𝐩𝐢𝐥𝐨𝐭 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞, icon-url=https://raw.githubusercontent.com/fmz200/wool_scripts/main/icons/apps/Office.png
𝐂𝐡𝐚𝐭𝐆𝐏𝐓 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐃𝐢𝐬𝐧𝐞𝐲 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐍𝐞𝐭𝐟𝐥𝐢𝐱 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞, icon-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netflix.png
𝐒𝐩𝐨𝐭𝐢𝐟𝐲 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐓𝐰𝐢𝐭𝐭𝐞𝐫 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐘𝐨𝐮𝐓𝐮𝐛𝐞 = select, 𝐉𝐚𝐩𝐚𝐧, 𝐓𝐚𝐢𝐖𝐚𝐧, 𝐀𝐦𝐞𝐫𝐢𝐜𝐚, 𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠, 𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞
𝐉𝐚𝐩𝐚𝐧 = smart, include-other-group=𝐎𝐜𝐭𝐨𝐩𝐮𝐬, policy-regex-filter=🇯🇵|日|JP, icon-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/JP.png
𝐓𝐚𝐢𝐖𝐚𝐧 = smart, include-other-group=𝐎𝐜𝐭𝐨𝐩𝐮𝐬, policy-regex-filter=🇨🇳|台|TW, icon-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/CN.png
𝐀𝐦𝐞𝐫𝐢𝐜𝐚 = smart, include-other-group=𝐎𝐜𝐭𝐨𝐩𝐮𝐬, policy-regex-filter=🇺🇸|美|US, icon-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/US.png
𝐇𝐨𝐧𝐠𝐊𝐨𝐧𝐠 = smart, include-other-group=𝐎𝐜𝐭𝐨𝐩𝐮𝐬, policy-regex-filter=🇭🇰|港|HK, icon-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/HK.png
𝐒𝐢𝐧𝐠𝐚𝐩𝐨𝐫𝐞 = smart, include-other-group=𝐎𝐜𝐭𝐨𝐩𝐮𝐬, policy-regex-filter=🇸🇬|新|SG, icon-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/SG.png

[Rule]
# 𝐀𝐝𝐁𝐥𝐨𝐜𝐤
RULE-SET,http://octopus/AdBlock,𝐑𝐞𝐟𝐮𝐬𝐞,pre-matching
# 𝐈𝐏-𝐂𝐈𝐃𝐑
OR,((IP-CIDR,0.0.0.0/32), (IP-CIDR,95.161.76.100/31)),𝐑𝐞𝐟𝐮𝐬𝐞,pre-matching,no-resolve
# 𝐁𝐢𝐥𝐢𝐛𝐢𝐥𝐢
RULE-SET,http://octopus/Bilibili,𝐁𝐢𝐥𝐢𝐛𝐢𝐥𝐢
# 𝐂𝐥𝐚𝐮𝐝𝐞
RULE-SET,http://octopus/Claude,𝐂𝐥𝐚𝐮𝐝𝐞
# 𝐂𝐨𝐩𝐢𝐥𝐨𝐭
RULE-SET,http://octopus/Copilot,𝐂𝐨𝐩𝐢𝐥𝐨𝐭
# 𝐂𝐡𝐚𝐭𝐆𝐏𝐓
DOMAIN-SUFFIX,sentry.io,𝐑𝐞𝐟𝐮𝐬𝐞
RULE-SET,http://octopus/ChatGPT,𝐂𝐡𝐚𝐭𝐆𝐏𝐓
# 𝐃𝐢𝐬𝐧𝐞𝐲
RULE-SET,http://octopus/Disney,𝐃𝐢𝐬𝐧𝐞𝐲
# 𝐍𝐞𝐭𝐟𝐥𝐢𝐱
RULE-SET,http://octopus/Netflix,𝐍𝐞𝐭𝐟𝐥𝐢𝐱
# 𝐒𝐩𝐨𝐭𝐢𝐟𝐲
RULE-SET,http://octopus/Spotify,𝐒𝐩𝐨𝐭𝐢𝐟𝐲
# 𝐓𝐰𝐢𝐭𝐭𝐞𝐫
RULE-SET,http://octopus/Twitter,𝐓𝐰𝐢𝐭𝐭𝐞𝐫
# 𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦
RULE-SET,http://octopus/Telegram,𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦
# 𝐘𝐨𝐮𝐓𝐮𝐛𝐞
RULE-SET,http://octopus/YouTube,𝐘𝐨𝐮𝐓𝐮𝐛𝐞
# 𝐀𝐩𝐩𝐥𝐞
RULE-SET,http://octopus/Apple,𝐃𝐢𝐫𝐞𝐜𝐭
# 𝐒𝐩𝐞𝐞𝐝𝐭𝐞𝐬𝐭
RULE-SET,http://octopus/Speedtest,𝐃𝐢𝐫𝐞𝐜𝐭
# 𝐂𝐍
# 𝐋𝐚𝐧
# 𝐒𝐲𝐬𝐭𝐞𝐦
OR,((GEOIP,CN), (RULE-SET,LAN), (RULE-SET,SYSTEM)),𝐃𝐢𝐫𝐞𝐜𝐭
# 𝐅𝐢𝐧𝐚𝐥
FINAL,𝐎𝐜𝐭𝐨𝐩𝐮𝐬,dns-failed

[Host]
# 𝐋𝐚𝐧
*.lan = server:syslib
# 𝐂𝐮𝐬𝐭𝐨𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧
mtalk.google.com = 108.177.125.188
dl.google.com = server:119.29.29.29
dl.l.google.com = server:119.29.29.29
*.dl.playstation.net = server:119.29.29.29
update.googleapis.com = server:119.29.29.29

[URL Rewrite]
^http://(www.)?(g|google)\.cn https://www.google.com 302
^http://octopus/(.*?)$ https://github.com/Anchen520i/Dynamic/raw/Surge/Rule/$1.list 302

[MITM]
skip-server-cert-verify = true
tcp-connection = true
h2 = true
hostname = *.lrts.me, *.kuwo.cn, api.m.jd.com, www.google.cn, weixin110.qq.com, security.wechat.com
ca-passphrase = B6680118
ca-p12 = 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

[Script]
# 𝐊𝐮𝐰𝐨 𝐌𝐮𝐬𝐢𝐜
𝐊𝐮𝐰𝐨 𝐌𝐮𝐬𝐢𝐜 = type=http-response,pattern=^https?:\/\/(?:musicpay|nmobi|vip1|audiobookpay|tingshu)\.kuwo\.cn\/(?:music\.pay\?newver=\d+|mobi.s\?f=kwxs|vip\/(?:enc\/user\/vip\?op=ui&uid=|v2\/theme\?op=gd)|a\.p|v2\/api\/pay\/user\/info),requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/Yuheng0101/X/refs/heads/main/Scripts/kuwo.js,binary-body-mode=0,script-update-interval=0
# 𝐑𝐞𝐦𝐨𝐯𝐞 𝐖𝐞𝐂𝐡𝐚𝐭 𝐋𝐢𝐧𝐤 𝐑𝐞𝐬𝐭𝐫𝐢𝐜𝐭𝐢𝐨𝐧
𝐑𝐞𝐦𝐨𝐯𝐞 𝐖𝐞𝐂𝐡𝐚𝐭 𝐋𝐢𝐧𝐤 𝐑𝐞𝐬𝐭𝐫𝐢𝐜𝐭𝐢𝐨𝐧 = type=http-response,pattern=^https\:\/\/(weixin110\.qq|security.wechat)\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi\?,requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/Anchen520i/Dynamic/Surge/Script/UnblockURLinWeChat.js
```
