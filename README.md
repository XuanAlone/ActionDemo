# ActionDemo

一个基于 Unity URP 的 3D 动作游戏 Demo，用于练习角色 3C（移动/镜头/控制）、战斗系统与性能优化。

> 项目目标：作为求职作品集使用，重点展示工程结构、系统设计与性能优化能力。

## 技术栈

- 引擎：Unity 6000.6.7f1
- 渲染管线：URP（Universal Render Pipeline）
- 语言：C#
- 版本控制：Git + GitHub（含 Git LFS）
- IDE：Visual Studio 2026

## 当前进度

- [x] 工程初始化与目录结构
- [ ] 角色 3C：移动、跳跃、相机跟随
- [ ] 战斗系统：攻击、连击、受击
- [ ] 敌人 AI
- [ ] UI 与关卡流程
- [ ] 性能优化与数据记录

## 目录结构

```
Assets/
└── _Project/
    ├── Scripts/          # C# 代码
    │   ├── Player/       # 角色控制、3C
    │   ├── Combat/       # 战斗、伤害
    │   ├── AI/           # 敌人行为
    │   ├── UI/           # 界面逻辑
    │   └── Core/         # 状态机、事件总线、工具类
    ├── Scenes/           # 场景文件
    ├── Prefabs/          # 预制体
    ├── Art/              # 模型、材质、贴图
    ├── Audio/            # 音效与 BGM
    ├── Config/           # ScriptableObject 配置表
    ├── UI/               # UI 预制体与图片
    └── ThirdParty/       # 第三方资源
```

## 运行方式

1. 使用 Unity 6000.6.7f1 打开本项目
2. 打开 `Assets/_Project/Scenes/` 下的场景
3. 点击 Play

## 开发日志

- 2026-10-31 工程初始化，建立目录结构，配置 Git 与 GitHub
