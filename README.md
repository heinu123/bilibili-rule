# 哔哩哔哩IP归属地分流规则

仅代理ip归属地
upos等视频cdn均不会代理

# 规则组(rule-providers）
```
  bilibili:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/heinu123/bilibili-clash/main/bilibili.yaml
    path: ./rule_providers/bilibili.yaml
    interval: 86400
```

# 规则(rule)

proxy替换成你的代理组名称
```
  - RULE-SET,bilibili,proxy
```
