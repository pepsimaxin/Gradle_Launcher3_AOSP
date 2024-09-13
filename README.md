# Gradle_Launcher3_AOSP

## 说明

1. 基于 AOSP release 分支代码
2. Gradle 构建，完美运行

## 分支

├── Launcher3
│   └── android14-release


├── common                    # 公共能力层目录
├── docs                      # 开发指南
├── feature                   # 公共特性层目录
│   └── appcenter             # 应用中心
│   └── bigfolder             # 智能文件夹
│   ├── form                  # 桌面卡片管理功能
│   ├── gesturenavigation     # 手势导航
│   ├── pagedesktop           # 工作区
│   ├── recents               # 最近任务
│   ├── settings              # 桌面设置
│   ├── smartdock             # dock工具栏
├── product                   # 业务形态层目录
├── signature                 # 签名证书


## 源码参考

[https://cs.android.com/android/platform/superproject/+/master:packages/apps/Launcher3/](https://cs.android.com/android/platform/superproject/+/master:packages/apps/Launcher3/)

## Gradle 构建指导

[Launcher 背后的魔法：Gradle 构建与编译全攻略（超详细 + Android 14.0）](https://blog.csdn.net/pepsimaxin/article/details/142209682?spm=1001.2014.3001.5501)