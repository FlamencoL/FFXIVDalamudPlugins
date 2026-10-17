# FFXIVDalamudPlugins
个人维护的《最终幻想 XIV》Dalamud 第三方插件源。

## 订阅地址

```
https://raw.githubusercontent.com/FlamencoL/FFXIVDalamudPlugins/main/pluginmaster.json
```

### MeowZWR 仓库镜像（无代理前缀）

[MeowZWR/DalamudPlugin](https://github.com/MeowZWR/DalamudPlugin) 的 `pants.json`，去掉了 DownloadLink 中的 `https://meowrs.com/` 代理前缀，由 GitHub Actions 每天北京时间 08:00、12:00、18:00、23:00 自动同步：

```
https://raw.githubusercontent.com/FlamencoL/FFXIVDalamudPlugins/main/pants.json
```

## 使用方法

1. 游戏内输入 `/xlsettings` 打开卫月设置
2. 进入"测试版"页签，在"自定义插件仓库"中粘贴上面的地址，勾选启用并保存
3. 输入 `/xlplugins` 打开插件安装器，搜索插件名安装

## 插件列表

### Hotbar Font
将国服技能栏上带修饰键、字母或小键盘键的快捷键改为游戏内置的其他字体（默认 MiedingerMed，与国际服一致），并可转为大写。

- `/hbfont config` 打开设置窗口，可切换字体、开关大写转换
- `/hbfont` 开 / 关（关闭后恢复原样）

### MeowZWR 镜像（pants.json）
以下插件由 [MeowZWR](https://github.com/MeowZWR/DalamudPlugin) 汉化维护，本仓库仅镜像其插件列表并去除下载链接的代理前缀，插件本身不做任何修改。下载直连 GitHub Releases，国内网络可能需要自备代理。列表随上游自动更新，以 [pants.json](pants.json) 为准。

| 插件 | 原作者 | 简介 |
| --- | --- | --- |
| [NecroLens](https://github.com/MeowZWR/NecroLens) | Jukka | 深层迷宫助手，显示巡逻怪、仇恨、视线等信息的雷达视图 |
| [Wrath Combo](https://github.com/MeowZWR/WrathCombo) | Team Wrath | 将连击与互斥技能整合至单个按键，可配置完整的职业循环 |
| [IINACT](https://github.com/MeowZWR/IINACT) | Usagi | 在类 ACT 环境中运行 FFXIV_ACT_Plugin 的伤害统计插件，内置为现代 .NET 重写的 Overlay Plugin |

## 免责声明
本仓库插件均为第三方工具，与 Square Enix 及 Dalamud 官方无关，使用风险自负。镜像插件的版权与问题反馈归原作者及 MeowZWR 所有，请前往对应仓库反馈。
