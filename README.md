
[General]
loglevel = notify

[Rule]
# Swiftgram 的分流规则
DOMAIN-SUFFIX,telegram.org,PROXY
DOMAIN-SUFFIX,t.me,PROXY
DOMAIN-KEYWORD,telegram,PROXY
DOMAIN-SUFFIX,telesco.pe,PROXY
IP-CIDR,149.154.160.0/20,PROXY
IP-CIDR,91.108.4.0/22,PROXY

# 其他流量默认规则
FINAL,DIRECT
