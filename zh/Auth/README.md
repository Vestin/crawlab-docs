## 权限管理

Crawlab 从 v0.4.9 版本开始，加强了对权限管理的支持，让权限管理变得更加复杂和实用，为企业用户提供了权限管理的支持。

### 用户角色

Crawlab 的权限管理是简易版的 RBAC。简单来说，Crawlab 分为两个角色：`管理用户` 和 `普通用户`。

- **管理用户**：可以查看并操作所有用户的数据，包括爬虫、项目、任务等，可以看到用户管理页面；
- **普通用户**：只能查看并操作自己的数据，不能看到用户管理页面。

### 公共爬虫

您可以在爬虫详情-概览页面看到 `是否公共` 对选项。如果勾选并保存，表示该爬虫为公共爬虫，也就是说所有用户都可以查看到，但除了管理员以外，其他用户无法对该爬虫进行修改，只能复制该爬虫当自己的工作空间。