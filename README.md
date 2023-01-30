<div align="center">
    <hr>
    <img src="https://raw.githubusercontent.com/ShizukuWorld/rin-asf-bot/master/resource/headshot.png" width="200" height="200" alt="MiaBot"> 
    <h1>MiaBot</h1>
    <b>Mia mia mia mia...</b>
</div>

[![Github Issue](https://img.shields.io/github/issues/MashiroSA/MiaBot)](https://github.com/MashiroSA/MiaBot/issues)
[![Github Forks](https://img.shields.io/github/forks/MashiroSA/MiaBot)](https://github.com/MashiroSA/MiaBot/fork)
[![Github Stars](https://img.shields.io/github/stars/MashiroSA/MiaBot)](https://github.com/MashiroSA/MiaBot)
[![GitHub License](https://img.shields.io/github/license/MashiroSA/MiaBot)](https://github.com/MashiroSA/MiaBot/blob/master/LICENSE)

---

![Alt](https://repobeats.axiom.co/api/embed/0bd4a1fd0e4f9bd885de668ab99c0b5813cb6388.svg "Repobeats analytics image")

---

## 介绍
这是一个部署库，意味着这并非开发仓库，只是作为快速部署镜像而存在。本库包含了可以快速可用的采用Onebot协议的Nonebot机器人，并使用GoCQHttp作为实现，其目的只是为了快速的完成一个能查询求生之路2的服务器信息的机器人，并将它懒人化。

你不应在该Repo中反馈除部署以外的问题，所有的插件均是借物，请移步相应的Repo反馈问题。

## 部署
> Python > 3.7
```bash
   screen -S miabot
   python -m pip install --user pipx
   python -m pipx ensurepath
   pipx install nb-cli
   cd miabot && nb run
```
```bash
   screen -S go-cqhttp-linux
   cd gocqhttp && ./go-cqhttp
```

## 借物表
- [Nonebot2](https://github.com/nonebot/nonebot2)
- [GoCQHttp](https://github.com/Mrs4s/go-cqhttp)
- [Nonebot插件-L4D2查询](https://github.com/Umamusume-Agnes-Digital/nonebot_plugin_l4d2_server)
