# multi-v2ray
a tool to manage v2ray/xray config json, support multiple user && group manage  
![](https://img.shields.io/pypi/v/v2ray-util.svg) 
![](https://img.shields.io/docker/pulls/jrohy/v2ray.svg)
![](https://img.shields.io/github/license/Jrohy/multi-v2ray.svg)


## Feature
- Support Xray manage, different commands (v2ray/xray) enter different core management
- V2ray && Iptables Traffic Statistics
- Command line to manage
- Multiple user && port manage
- Cloudcflare cdn mode
- Support pure ipv6 VPS
- Support Docker
- Dynamic port
- Ban bittorrent
- Range port
- TcpFastOpen
- Vmess/VLESS/Socks5/MTproto share link
- Support protocol modify:
  - TCP
  - Fake http
  - WebSocket
  - mkcp
  - mKCP + srtp
  - mKCP + utp
  - mKCP + wechat-video
  - mKCP + dtls
  - mKCP + wireguard
  - HTTP/2
  - Socks5
  - MTProto
  - Shadowsocks
  - Quic
  - VLESS_TCP
  - VLESS_TLS
  - VLESS_WS
  - VLESS_REALITY
  - Trojan

## How To Use

**SC-Build Script**

## :heavy_exclamation_mark: Requirements

* A Linux-based operating system (Debian/Ubuntu) 
* Preference: Debian 11
* Preference: Ubuntu 20.04
* It is recommended to use a new or formatted distro

# Installation
```
curl https://raw.githubusercontent.com/Nortondb12/multi-v2ray/main/v2ray > v2ray; chmod 777 v2ray; ./v2ray
```


uninstall
```
source <(curl -sL https://raw.githubusercontent.com/Nortondb12/multi-v2ray/main/v2ray) --remove
```

## Command Line
```bash
v2ray/xray [-h|help] [options]
    -h, help             get help
    -v, version          get version
    start                start V2Ray
    stop                 stop V2Ray
    restart              restart V2Ray
    status               check V2Ray status
    new                  create new json profile
    update               update v2ray to latest
    update [version]     update v2ray to special version
    update.sh            update multi-v2ray to latest
    add                  add new group
    add [protocol]       create special protocol, random new port
    del                  delete port group
    info                 check v2ray profile
    port                 modify port
    tls                  modify tls
    tfo                  modify tcpFastOpen
    stream               modify protocol
    cdn                  cdn mode
    stats                v2ray traffic statistics
    iptables             iptables traffic statistics
    clean                clean v2ray log
    log                  check v2ray log
    rm                   uninstall core
```




## Dependent
v2ray docker: https://hub.docker.com/r/jrohy/v2ray  
xray docker: https://hub.docker.com/r/jrohy/xray
pip: https://pypi.org/project/v2ray-util/  
python3: https://github.com/Jrohy/python3-install  
acme: https://github.com/Neilpang/acme.sh
