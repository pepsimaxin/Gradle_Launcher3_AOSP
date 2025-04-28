[![7tXg2H.png](https://v1.ax1x.com/2025/04/25/7tXg2H.png)](https://zimgs.com/i/7tXg2H)

## 📜 Description

![Static Badge](https://img.shields.io/badge/aosp-launcher3-red) &nbsp;&nbsp;![Static Badge](https://img.shields.io/badge/android_15-branch-green) &nbsp;&nbsp;![Static Badge](https://img.shields.io/badge/android_14-branch-blue) &nbsp;&nbsp;![Static Badge](https://img.shields.io/badge/android_13-branch-yellow) &nbsp;&nbsp;![Static Badge](https://img.shields.io/badge/android_11-branch-pink)

1. 基于 AOSP release 分支代码
2. Gradle 构建，完美运行
3. 纯净代码，无任何自定义改动

## 📜 Branch

| Branch | Gradle | Updated |
|:- |:- |:- |
| android_15_release | ❎ 暂未适配 | - |
| android-14.0.0_r28 | ❎ 已适配（Android 14 的小伙伴直接用这个分支就可以开发了） | 2025.04.28 |
| android_14 | ✅ 已适配 | - |
| android_13 | ❎ 暂未适配 | - |
| android_11 | ✅ 已适配 | - |

## 📜 android.jar

替换本地 SDK 中 platform 文件夹下 Android 34 的同名文件（新 jar 包融合了编译 Android14 源码后生成的 framework.jar 文件的内容）。

Jar 包我放在 Release 里面了：SDK-34-android.jar -> 下载 android.jar_for_launcher，改成 android.jar 替换即可 build Success!

## 📜 Codes

[https://cs.android.com/android/platform/superproject/+/master:packages/apps/Launcher3/](https://cs.android.com/android/platform/superproject/+/master:packages/apps/Launcher3/)

## 📜 Gradle Guide

[Launcher 背后的魔法:Gradle 构建与编译全攻略(超详细 + Android 14.0)](https://blog.csdn.net/pepsimaxin/article/details/142209682)
