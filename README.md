ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list
ruleset=🌿 广告拦截,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
ruleset=🌸 应用净化,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list
ruleset=📲 电报消息,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Telegram.list
ruleset=🎬 油管视频,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTube.list
ruleset=🍺 巴哈姆特,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bahamut.list
ruleset=🍻 哔哩哔哩,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bilibili.list
ruleset=🍻 哔哩哔哩,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/BilibiliHMT.list
ruleset=🗺 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaIp.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list
ruleset=🧭 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list
ruleset=🧭 全球直连,[]GEOIP,CN
ruleset=🐟 漏网之鱼,[]FINAL
custom_proxy_group=🗺 节点选择`select`[]🇭🇰 香港节点`[]🇹🇼 台湾节点`[]🇸🇬 狮城节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]⛩️ 手动切换`[]🇺🇳 其他节点
custom_proxy_group=⛩️ 手动切换`select`.*
custom_proxy_group=📲 电报消息`select`[]🗺 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇹🇼 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🇺🇳 其他节点`[]⛩️ 手动切换
custom_proxy_group=🍻 哔哩哔哩`select`[]🧭 全球直连`[]🇹🇼 台湾节点`[]🇭🇰 香港节点`[]🇺🇳 其他节点`[]⛩️ 手动切换
custom_proxy_group=🍺 巴哈姆特`select`[]🇹🇼 台湾节点`[]🗺 节点选择`[]⛩️ 手动切换
custom_proxy_group=🎬 油管视频`select`[]🗺 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇹🇼 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🇺🇳 其他节点`[]⛩️ 手动切换
🗺 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇹🇼 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🇺🇳 其他节点`[]⛩️ 手动切换
custom_proxy_group=🌸 应用净化`select`[]REJECT`[]DIRECT
custom_proxy_group=🌿 广告拦截`select`[]REJECT`[]DIRECT
custom_proxy_group=🐟 漏网之鱼`select`[]🗺 节点选择`[]DIRECT`[]🇭🇰 香港节点`[]🇹🇼 台湾节点`[]🇸🇬 狮城节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🇺🇳 其他节点`[]⛩️ 手动切换
custom_proxy_group=🧭 全球直连`select`[]DIRECT`[]🗺 节点选择
custom_proxy_group=🇭🇰 香港节点`select`(港|HK|Hong Kong)
custom_proxy_group=🇯🇵 日本节点`select`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|[^-]日|JP|Japan)
custom_proxy_group=🇺🇲 美国节点`select`(美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United States)
custom_proxy_group=🇸🇬 狮城节点`select`(新加坡|坡|狮城|广新|SG|Singapore)
custom_proxy_group=🇹🇼 台湾节点`select`(台|新北|彰化|TW|Taiwan)
custom_proxy_group=🇰🇷 韩国节点`select`(KR|Korea|KOR|首尔|韩|韓)
custom_proxy_group=🇺🇳 其他节点`select`GCX`^((?!新|多伦多|哥伦布|纽约|弗里蒙特|Jap|Tai|Singa|广新|狮城|SG|港|HK|HONG|Hong|HGC|台|新北|彰化|TW|日本|川日|东京|大阪|泉日|埼玉|沪日|深日|JP|Jap|韩国|韩|京日|杭日|青日|美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United.*?States).)*$
;



enable_rule_generator=true
overwrite_original_rules=true

;clash_rule_base=https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GeneralClashConfig.yml

;luck
