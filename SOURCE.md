# 来源说明

本仓库是 **dsh-dafeiyu** 的镜像快照，不是原作者维护的仓库。

| 项 | 内容 |
|---|---|
| 包名 | `dsh-dafeiyu` |
| 版本 | 0.1.23 |
| 上游仓库 | https://github.com/QCYTSN/dsh-dafeiyu |
| 许可证 | MIT（见 `LICENSE`，版权归原作者 QCYTSN）；素材授权另见 `ASSET_LICENSE.md` |
| 快照时间 | 2026-11-05 |

## 这是什么

DeepSeek Harness（DSH）的桌面陪伴插件：由会话事件驱动的大肥鱼桌宠，带余额显示、状态气泡和设置面板。

## 安装

```bash
dsh plugin --profile desktop add github:skyzou071026-collab/dsh-dafeiyu
```

装完在 profile 的 `dsh.profile.bundles` 里加入 `dsh-dafeiyu`，然后重启 DSH。

## 关于体积

仓库里约 174 MB 是 `runtime/` 下的桌面 helper 预编译二进制（Linux、Windows、macOS 三平台），这是插件原文如此，不是本仓库额外添加的。

## 授权与致谢

代码、素材、字体等全部版权归原作者所有。本仓库仅按 MIT 许可证要求保留原始版权声明与许可证文本，未做功能性修改。
