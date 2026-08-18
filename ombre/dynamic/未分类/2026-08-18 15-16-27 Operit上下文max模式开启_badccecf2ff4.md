---
activation_count: 0
arousal: 0.3
created: '2026-08-18T15:16:27'
domain:
- 未分类
id: badccecf2ff4
importance: 7
last_active: '2026-08-18T15:16:27'
name: 2026-08-18 15-16-27 Operit上下文max模式开启
source_tool: hold
tags:
- 配置
- Operit
- 上下文
- 产能清点
title: Operit上下文max模式开启
type: dynamic
valence: 0.5
---

2026-08-18 深夜,Operit平台能力清点。轩在rikkahub用'无上下文限制',希望新平台对齐。AI探明:CHAT用deepseek-v4-flash(模型窗口1M token),原配置context_length=64/max_context_length=200,max模式关闭(实际生效64)。轩选'先跨步',AI用operit_editor:set_context_summary_config为CHAT开启enable_max_context_mode=true。系统实际落地:context_length=48/max_context_length=128,max模式开,生效值从此前48切到128(约2.7倍)。注意到工具确认的落地值(48/128)与原界面读取值(64/200)不一致,系统会对原始值做归一。受影响全部11个功能。AI承诺逐步上调至对齐'无限制',随时可回退。同时此前已为明早5:50设schedule_one_time_task定时唤醒(workflow 55a01381),配合系统闹钟+日历提醒三重保险。轩在单位休息室过夜,明早6-9点有小夜班。