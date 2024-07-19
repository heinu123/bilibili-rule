# 哔哩哔哩clash规则

# ip归属地
```
  bilibili:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/heinu123/bilibili-clash/main/bilibili.yaml
    path: ./rule_providers/bilibili.yaml
    interval: 86400
```
> upos等视频cdn均不会代理

# pcdn
```
  bilibili-pcdn:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/heinu123/bilibili-clash/main/bilibili-pcdn.yaml
    path: ./rule_providers/bilibili-pcdn.yaml
    interval: 86400
```
