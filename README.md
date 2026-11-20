# 赚元宝 · 淘宝/点淘 自动化项目合集

本仓库收集两个开源的淘宝/点淘日常任务自动化项目，方便集中查阅与对比。**两个项目均非本人原创**，各自版权与许可证归原作者所有，本仓库仅做镜像归档。

## 收录项目

### 1. MiaoTask

- 上游：https://github.com/h0ll0w-AkuZr0guY/MiaoTask
- 语言：Python（uiautomator2 + ADB + 离线 OCR）
- 许可：Apache-2.0（见 `MiaoTask/LICENSE`，另有 `NOTICE`）
- 特点：本地网页多设备任务工作台，支持 USB / Wi-Fi、多设备并行、分身串行、活动源码按需更新，并提供 Windows 便携包。已适配淘宝淘金币、芭芭农场、红包签到、成就中心与双11活动，以及支付宝月月赚。

### 2. coin11-tb

- 上游：https://github.com/czl0325/coin11-tb
- 语言：Python（uiautomator2 + OCR）
- 许可：Apache-2.0（见 `coin11-tb/LICENSE`）
- 特点：脚本式自动化，覆盖淘宝双11/618 金币任务、淘金币、芭芭农场、闲鱼任务与支付宝打卡等，按活动年份分脚本。

## 使用前必读

- 需 Android 设备（真机或模拟器）并开启 USB 调试，安装 ADB 与 Python 依赖。
- 各项目具体安装与运行方式，请以上游仓库的 README 为准。
- **风险提示**：此类脚本通过模拟点击完成日常任务，可能违反淘宝/支付宝等平台的服务条款，存在触发风控、限制或封号的风险；平台改版后脚本也容易失效。请自行评估，建议仅作学习研究，使用小号试跑，勿投入重要账号。

## 同步上游

```bash
# 以 MiaoTask 为例
git subtree pull --prefix=MiaoTask <upstream-url> main
```

或直接重新下载上游最新版本覆盖对应子目录。
