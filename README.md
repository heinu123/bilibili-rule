# 哔哩哔哩IP归属地分流规则

仅代理ip归属地
upos等视频cdn均不会代理

# ip归属地
```
  bilibili:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/heinu123/bilibili-clash/main/bilibili.yaml
    path: ./rule_providers/bilibili.yaml
    interval: 86400
```

# pcdn
```
  bilibili-pcdn:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/heinu123/bilibili-clash/main/bilibili-pcdn.yaml
    path: ./rule_providers/bilibili-pcdn.yaml
    interval: 86400
```
