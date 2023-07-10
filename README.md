[custom]
;不要随意改变关键字，否则会导致出错
;acl4SSR规则

;去广告：支持
;自动测速：支持
;微软分流：支持
;苹果分流：支持
;增强中国IP段：支持
;增强国外GFW：支持

;设置规则标志位
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list
ruleset=⛔ 此路不通,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
ruleset=⛔ 此路不通,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/NetEaseMusic.list
ruleset=📢 谷歌,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/GoogleFCM.list
ruleset=Ⓜ️ 微软,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/OneDrive.list
ruleset=Ⓜ️ 微软,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Microsoft.list
ruleset=🍎 Apple,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Apple.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/SteamCN.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/BilibiliHMT.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bilibili.list
ruleset=📹 Youtube,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTube.list
ruleset=📲 吹水圣地,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Telegram.list
ruleset=🎥 奈飞,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Netflix.list
ruleset=🎥 奈飞,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/AmazonIp.list
ruleset=💬 Ai,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/OpenAi.list
ruleset=🎶 Spotify,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Spotify/Spotify.yaml
ruleset=🌍 外媒,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyMedia.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaMedia.list
ruleset=🇨🇳 台湾节点,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bahamut.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Epic.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Origin.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Sony.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Steam.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Nintendo.list
;ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaIp.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list
;ruleset=🎯 全球直连,[]GEOIP,LAN
ruleset=🎯 全球直连,[]GEOIP,CN
ruleset=🐟 漏网之鱼,[]FINAL
;设置规则标志位

;设置分组标志位
custom_proxy_group=🚀 节点选择`select`[]♻️ FastTest`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡`[]🇨🇳 湾湾`[]🇺🇲 美国`[]🔮 负载均衡`[]🌍 其它地区`[]🚀 手动切换
custom_proxy_group=🚀 手动切换`select`.*
custom_proxy_group=📲 吹水圣地`select`[]♻️ FastTest`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡`[]🇨🇳 湾湾`[]🇺🇲 美国`[]🇰🇷 泡菜国`[]🔮 负载均衡`[]🚀 手动切换
custom_proxy_group=📹 Youtube`select`[]♻️ FastTest`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡`[]🇨🇳 湾湾`[]🇺🇲 美国`[]🇰🇷 泡菜国`[]🔮 负载均衡`[]🚀 手动切换
custom_proxy_group=🎥 奈飞`select`[]🇸🇬 新嘎坡`[]🇭🇰 香港`[]🇨🇳 湾湾`[]🇯🇵 日本`[]🇺🇲 美国`[]🚀 手动切换
custom_proxy_group=💬 Ai`select`[]🇺🇲 美国节点`[]🌍 其它地区`[]🚀 手动切换
custom_proxy_group=🌍 外媒`select`[]♻️ FastTest`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡`[]🇨🇳 湾湾`[]🇺🇲 美国`[]🔮 负载均衡`[]🌍 其它地区`[]🚀 手动切换
custom_proxy_group=🎶 Spotify`select`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡
custom_proxy_group=🐟 漏网之鱼`select`[]♻️ FastTest`[]🇭🇰 香港`[]🇯🇵 日本`[]🇸🇬 新嘎坡`[]🇨🇳 湾湾`[]🇺🇲 美国`[]🇰🇷 泡菜国`[]🔮 负载均衡`[]🚀 手动切换
custom_proxy_group=♻️ FastTest`url-test`.*`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🔮 负载均衡`load-balance`(🇭🇰)`.*`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🇭🇰 香港`url-test`(港|HK|Hong Kong)`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🇯🇵 日本`url-test`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|[^-]日|JP|Japan)`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🇸🇬 新嘎坡`url-test`(新加坡|坡|狮城|SG|Singapore)`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🇨🇳 湾湾`url-test`(台|新北|彰化|TW|Taiwan)`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🇺🇲 美国`url-test`(美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United States)`http://www.gstatic.com/generate_204`150,,150
custom_proxy_group=🇰🇷 泡菜国`url-test`(KR|Korea|KOR|首尔|韩|韓)`http://www.gstatic.com/generate_204`150,,50
custom_proxy_group=🌍 其它地方`url-test`(🇦🇺|🇨🇦|🇩🇪|🇬🇧|🇮🇳|🇳🇱|🇵🇱|🇹🇭|🇧🇷|🇫🇷|🇹🇷|🇦🇷|🇷🇺)`http://www.gstatic.com/generate_204`150,,50  
custom_proxy_group=📢 谷歌`select`[]DIRECT`[]🇭🇰 香港`[]🇯🇵 日本
custom_proxy_group=Ⓜ️ 微软`select`[]DIRECT`[]🇭🇰 香港节点
custom_proxy_group=🍎 Apple`select`[]DIRECT`[]🇭🇰 香港节点
custom_proxy_group=🎯 全球直连`select`[]DIRECT`
custom_proxy_group=⛔ 此路不通`select`[]REJECT`
;设置分组标志位

enable_rule_generator=true
overwrite_original_rules=true

;clash_rule_base=https://raw.githubusercontent.com/Oklasu/Clash-config/main/GeneralClashConfig.yml


;luck
