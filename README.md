# 哔哩哔哩规则

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
