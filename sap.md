# Sap 学习笔记

[TOC]



## sap basis

### 用户权限 

[参考链接](https://blog.csdn.net/morning_snow/article/details/46986319)

   1. SU20: 维护authorization field
      2. SU21: 维护authorization object
      3. PFCG: 维护角色
      4. SU02: 维护authorization profile
      5. SU01: 维护用户
      6. SUIM: 权限检查
### 角色管理
   1. 功能：角色创建、编辑、删除、显示、角色权限配置
   2. 事务码：PFCG

## 基础知识

### 事务分析
#### 常见管理事务

1. 用户列表：SM04（实例） AL08（系统）
2. 显示系统实例：SM51
3. 后台作业预览：SM37
4. 工作进程管理：SM50（实例） SM66（系统）
5. 锁管理：SM12
6. 更新记录管理：SM13
7. 分析系统日志：SM21
8. 发送系统消息：SM02
9. 跨系统监测：RZ20
10. 传输：
    1. 传输组织器：SE01
    2. 传输管理系统：STMS

11. ABAP 字典：SE11
12. 程序开发器：SE38
13. 对象浏览器：SE84
14. 维护事务: SE93
15. 函数模块：se37
16. 

## 系统启停

### 系统启动过程

1. user：<sid>adm
2. start database -> start central instance -> start other instances
3. 



