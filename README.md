# dsh-xiaofu-widget-v1.0.0

小弗余额挂件：白色椭圆气泡、暗红文字、可拖动的 Q 版角色

> DeepSeek Harness（dsh）第三方插件。本仓库提供可直接安装的发布包。

## 下载

- [`dsh-xiaofu-widget-v1.0.0.zip`](./dsh-xiaofu-widget-v1.0.0.zip) —— 完整发布包（5.4 MB）

## 安装

1. 解压 `dsh-xiaofu-widget-v1.0.0.zip`，得到目录 `dsh-xiaofu-widget`
2. 把 `dsh-xiaofu-widget` 整个目录放到：

   ```
   %USERPROFILE%\.dsh\external\
   ```

3. 在 dsh 的 profile 配置里启用（`%USERPROFILE%\.dsh\profiles\desktop\package.json` 的 `dsh.profile.bundles` 加入 `@dsh-external/dsh-xiaofu-widget`），
   或使用 dsh 的插件管理面板安装。
4. 重启 DeepSeek Harness。

> 提示：皮肤类插件同一时间只能启用一个，同时启用多个会导致启动卡在 Loading。

## 兼容性

| 项目 | 值 |
| --- | --- |
| 插件版本 | 1.0.0 |
| 声明的宿主版本范围 | `0.1.0-rc.6 - 0.2.1-rc.5` |
| 宿主平台 | web |
| 许可 | MIT |

超出声明范围运行不保证稳定，可能出现加载失败或界面异常。

## 主要文件

| 文件 | 大小 |
| --- | --- |
| `assets/audio/待机2.mp3` | 972.3 KB |
| `assets/audio/待机4.mp3` | 955.8 KB |
| `assets/audio/待机5.mp3` | 917.2 KB |
| `assets/audio/待机语音1.mp3` | 873.7 KB |
| `assets/audio/待机3.mp3` | 841.3 KB |
| `assets/audio/喏，没忘记指挥棒的手感吧.mp3` | 101.1 KB |

## 说明

本仓库仅托管发布包与说明文档，源码与问题反馈请在仓库 Issues 中提出。
