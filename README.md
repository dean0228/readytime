# 时刻 ReadyTime

一款以任务为核心的 macOS 本地优先效率工具，把任务、提醒、日程、专注和日常 Mac 工具组织在同一个原生工作台中。

> ReadyTime 是当前公开展示名称。产品仍处于内部验证阶段，完整源代码与安装包暂未公开。

## Overview

ReadyTime is a local-first macOS task companion that brings planning, reminders, focus and lightweight utilities into one native workspace.

## 为什么做它

很多效率工具擅长记录，却没有帮助用户真正进入行动。ReadyTime 以任务为主线，把创建、提醒、执行、复盘和轻量工具串成一套连贯的 Mac 工作流。

## 核心能力

- 常规任务、循环任务、优先级、标签和子任务
- macOS 原生提醒与前后台互斥通知
- 每日、每周和每月日程视图
- 自然语言和语音辅助创建任务
- 任务方案预览、编辑与确认后执行
- 专注计时、远眺休息和键盘清洁工具
- 活动统计、热力图与本地成就系统
- 本地备份、完整性校验与安全恢复
- 简体中文、English 和多种外观模式

## 产品原则

- **本地优先**：任务、活动、统计和偏好默认保存在当前 Mac
- **先预览再执行**：AI 只生成受约束的任务方案，不直接控制数据库、Shell 或文件系统
- **最小权限**：日历、通知、麦克风等能力均按需申请
- **可靠提醒**：应用前台与系统通知只保留一个明确出口

## 技术概览

- Swift + SwiftUI + AppKit
- SQLite
- Swift Package Manager
- macOS 14+
- 219 项自动化测试，覆盖 32 个测试套件

## 当前状态

- 当前内部版本：`v1.5.0 · Build 61`
- 已完成本机 DMG 构建与安装验证
- 当前构建采用 Ad Hoc 签名，仅用于内部测试
- Developer ID 签名、Apple 公证和正式公开分发尚未完成

## 隐私说明

- 不要求账号，不内置广告
- 不进行常驻录音或后台监听
- 语音创建由用户主动触发，原始录音不落盘
- API Key 保存在 macOS 钥匙串
- 远程模型默认关闭，启用后仅发送用户主动提交的当次输入

## 品牌说明

ReadyTime 是独立开发项目，与 Apple 及任何模型服务商不存在隶属、合作或背书关系。Apple、macOS 及其他第三方商标归各自权利人所有。

## 关于此仓库

该仓库用于展示产品方向、设计思路与开发进展，不包含完整应用源码、用户数据、API Key、内部构建产物或未签名安装包。

---

Built by [@dean0228](https://github.com/dean0228)

Copyright © 2026 Dean. All rights reserved.
