# Starsky · 桌面版发布仓

这里只放 **Starsky 亚马逊运营 Agent 系统 · DSH 桌面版** 的安装包和自动更新元数据，不放源码。源码仓是私有的，学员机拉不到私有仓的 Releases，所以发布物统一挂在这个公开仓的 [Releases](../../releases) 页。

## 下载

到 [Releases](../../releases/latest) 取最新版：

| 文件 | 用途 |
| --- | --- |
| `Starsky-Setup-<版本>.exe` | Windows 安装包（双击安装；未买微软签名证书，弹「已保护你的电脑」时点「更多信息 → 仍要运行」） |
| `Starsky-<版本>-mac-arm64.dmg` / `-x64.dmg` | Mac 安装包（Apple 芯片 / Intel；首次打开右键 → 打开） |
| `starsky-assets.zip` + `starsky-assets-manifest.json` | 学员包资产（技能 / 角色 / 模板），程序「更新中心 → 资产更新」自动取 |
| `latest.yml` / `latest-mac.yml` / `*.blockmap` | 程序自动更新用，不用手动下载 |

装完的程序默认就指向本仓库：菜单「系统 → 更新中心」（`Ctrl+U`）能直接检查外壳更新和资产更新。

## 授权码（1.5.2 起）

Starsky 按年授权、绑定电脑。装好后安装向导（或菜单「系统 → 授权与续费」`Ctrl+L`）会显示**本机指纹**，点「复制指纹」发给坚哥（公众号「跨境者说干货」后台，或星球私信，注明会员号），换回一行以 `STARSKY1.` 开头的授权码粘贴进去即可。到期后已装内容照常使用，只是不再接收更新；续费换新码，不用重装。换电脑需按新指纹重新申请。

## 老学员从「星空亚马逊运营Agent系统」升级

产品自 2026-09-04 起更名 Starsky，appId 变了，Windows 会把它当成新程序：先在旧版菜单「系统 → 彻底退出」，到「设置 → 应用」卸载「星空亚马逊运营Agent系统」（不删数据），再装 Starsky。首次打开自动接上原来的数据目录，对话、Key、工作区、已装插件全部保留。

## 关注与联系

作者坚哥。这套系统的更新说明、实战案例和踩坑记录都先发在公众号，圈子里答疑。

<p align="center">
  <img src="docs/assets/公众号_跨境者说干货.png" alt="微信搜一搜：跨境者说干货" width="640">
</p>

- 公众号：**跨境者说干货**（微信搜一搜，或扫上图二维码）
- 知识星球：[星空的跨境圈子](https://wx.zsxq.com/group/28882244282441)
- 同源的其他平台版本：[Codex 版 starsky-amazon-plugins-codex](https://github.com/wenjiany312-hub/starsky-amazon-plugins-codex) ｜ [Antigravity 版 starsky-amazon-agent-antigravity](https://github.com/wenjiany312-hub/starsky-amazon-agent-antigravity) ｜ [ZCode 版 starsky-amazon-agent-zcode](https://github.com/wenjiany312-hub/starsky-amazon-agent-zcode)；四版业务方法论同源，安装方式与目录结构各按平台适配，不要混装
- 问题反馈：本仓库 Issues，或公众号后台留言

—— 跨境者说干货 · 星空的跨境圈子 · 作者坚哥
