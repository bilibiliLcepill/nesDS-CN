# nesDS 中文汉化版 (nesDS-CN)

任天堂 DS / DSi 上的 FC（红白机/NES）模拟器 nesDS 的中文汉化修改版。

## 汉化内容

- **ROM 文件列表中文显示**：FC 游戏文件名（UTF-8 中文）在菜单中直接正常显示，不再乱码/问号
- **游戏内触摸菜单汉化**：暂停后下屏触摸菜单（文件 / 游戏 / 金手指 / 设置 / 调试 / 关于等）全部中文化
- **修复选中项镜像**：原版菜单选中项被错误地水平翻转的问题

### 菜单对照

| 原版 | 汉化 |
|------|------|
| File | 文件 |
| Game | 游戏 |
| Cheat | 金手指 |
| Settings | 设置 |
| Debug | 调试 |
| About | 关于 |
| Display | 显示 |
| Config | 配置 |
| Short-Cuts | 快捷键 |
| ... | 其余全部中文 |

## 构建

需要 [devkitARM](https://devkitpro.org/)（r43+）：

```
make
```

产物：`nesDS.nds`

## 使用

- 烧录卡（R4 等）需要打对应 DLDI 补丁
- 触摸下屏呼出游戏内菜单
- L / R：倒带 / 快进
- X / A：Y / B 连发

## 与原版的差异

- 菜单和文件列表支持中文字形（16x16 点阵字库，GB2312 一级汉字 3755 字）
- 修复 ROM 列表选中行镜像问题
- 游戏内下屏触摸菜单中文化

## 版权

原版 nesDS 为 **PUBLIC DOMAIN（公有领域）**，原作者声明：

> nesDS is released into the PUBLIC DOMAIN. You may do anything you want with it.
> -- nesds@olimar.fea.st

原始作者（Credits）：
- Coding: loopy, FluBBa
- More code: Dwedit, tepples, kuwanger, chishm
- Sound: Mamiya

本项目为修改版，同样以公有领域方式发布。
