# 高校科研管理系统项目文档

[返回首页](https://yourusername.github.io)

---

## 目录导航
- [可行性分析报告](#可行性分析报告)
- [界面设计](#界面设计)
- [设计文档](#设计文档)
- [需求分析文档](#需求分析文档)
- [附件](#附件)

---

## 可行性分析报告
> *此部分内容待补充*

---

## 界面设计
> *此部分内容待补充*


---

## 设计文档
> *此部分内容待补充*


---

## 需求分析文档

### 1.1 业务需求分析

#### 当前痛点
- 学术成果分散存储（Excel/纸质文档），缺乏统一管理
- 权限分配不合理，权限管理落后
- 科研数据孤立，存在数据孤岛问题

#### 核心业务需求
1. **系统登录需求**
   - 四种身份用户登录（科研人员/学院管理员/学校管理员/系统管理员）
   - 需选择身份类型并输入验证信息

2. **科研成果管理需求**
   - 科研人员：填写成果信息并上传材料
   - 学院管理员：审核提交的科研信息
   - 学校管理员：查看管理全校科研成果
   - 科研数据可视化呈现

3. **统计分析需求**
   - 多维度可视化统计（年度趋势/学科对比/个人贡献）
   - 生成教育部评估标准报表（待开发）

![需求分析流程图](requirements-flow-placeholder.jpg)

### 1.2 功能需求分析

#### 1.2.1 系统登录管理
- **身份验证与权限控制**
  - 多角色登录支持（身份类型选择）
  - 账号：工号/邮箱/系统分配ID
  - 密码：加密传输与存储

- **登录流程**
   - 选择身份类型

   - 输入账号密码

   - 身份验证成功 → 跳转角色主界面

   - 身份验证失败 → 显示具体错误类型

#### 1.2.2 学术成果管理
- **成果类型**
- 论文（SCI/EI/核心等）
- 专利（发明/实用新型/外观）
- 竞赛（学科竞赛/创新创业）
- 著作与科研项目

- **核心功能**

   - 增：单条录入 
   - 删：删除项目
   - 改：修改项目名称，类型等信息
   - 查：查看项目列表

- **人员权限**
- 科研人员：填写/查询成果
- 学院管理员：查询/删除成果，增添科研项目
- 学校管理员：管理全校成果

#### 1.2.3 统计分析管理
- **多维度统计**
- 年度趋势分析（成果数量/类型分布）
- 学科对比分析

- **可视化展示**
- 图表类型：柱状图/折线图/饼图
- 交互式查询：动态生成图表

© 2025 高校科研管理系统项目组 | [更新日志] | [反馈问题]
