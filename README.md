# 医院门诊管理系统 java553

## 项目概述

医院门诊管理系统是基于Python语言和Django框架，前端使用Vue.js构建的Web应用。该系统旨在提高医疗机构的门诊工作效率，实现预约、挂号、诊断、开药等流程的数字化管理。

## 技术栈

- 后端：Python 3.x, Django 3.x
- 前端：Vue.js, Element UI
- 数据库：PostgreSQL

## 功能模块

### 前台功能

- 患者预约挂号
- 查看医生排班
- 个人信息管理
- 查看历史就诊记录

### 后台功能

- 医生排班管理
- 挂号管理
- 病历管理
- 药品管理
- 统计报表

## 系统角色

- 系统管理员
- 医生
- 患者

## 运行环境

- Python 3.8 或以上版本
- Django 3.x
- Node.js
- Vue.js
- PostgreSQL 12.x 或以上版本

## 部署步骤

1. 安装依赖项
   ```bash
   pip install -r requirements.txt
   ```
2. 配置数据库
   编辑 `settings.py` 文件中的数据库配置项。
3. 迁移数据库
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
4. 收集静态文件
   ```bash
   python manage.py collectstatic
   ```
5. 启动开发服务器
   ```bash
   python manage.py runserver
   ```

## 目录结构

```
hospital_management_system/
│
├── hospital_backend/          # 后端目录
│   ├── apps/                   # 应用模块
│   ├── migrations/             # 数据库迁移文件
│   ├── settings.py             # 配置文件
│   └── urls.py                 # URL配置
│
└── hospital_frontend/         # 前端目录
    ├── assets/                 # 资源文件
    ├── components/             # 组件
    ├── views/                  # 视图
    ├── App.vue                 # 主Vue应用实例
    └── main.js                 # 入口脚本
```

## 核心亮点

- 前后端分离，便于维护和扩展
- 灵活的角色权限管理
- 集成化的预约与挂号流程，提高工作效率
- 数据驱动决策支持，便于管理优化

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img10.360buyimg.com/ddimg/jfs/t1/326145/27/23843/75681/68d4f406F2feb0ff8/a8d21682d17dd263.jpg)

