# Jump to SQL

用于在iBatis.NET项目中从C#接口方法名快速跳转到对应的XML SQL定义。反之，也可从XML SQL定义跳转到接口定义。快捷键需在安装完成后自行映射，操作路径为：**工具 -> 选项 -> 环境 -> 键盘**，搜索“jump”关键词，选中对应功能后设置快捷键即可生效。


## 安装

1. 从Visual Studio Marketplace直接安装插件：[https://marketplace.visualstudio.com/items?itemName=xiaochuanling.xcl123&ssr=false#overview](https://marketplace.visualstudio.com/items?itemName=xiaochuanling.xcl123&ssr=false#overview)
2. 或前往GitHub仓库下载插件安装包，通过本地手动方式安装；
3. 安装完成后重启Visual Studio，插件即可生效。


## 使用

1. 打开目标iBatis.NET项目；
2. **从接口跳转到SQL**：定位到C#接口方法所在行，右键菜单选择“转到SQL”，或使用已绑定的快捷键（如默认建议的 `Ctrl + Alt + Shift + S`，需自行配置）；
3. **从SQL跳转到接口**：定位到XML文件中SQL定义所在行，右键菜单选择“转到接口”，或使用已绑定的快捷键（如默认建议的 `Ctrl + Alt + Shift + I`，需自行配置）；
4. 执行操作后，将自动跳转至对应的代码/配置位置。


## 注意事项

1. 插件仅适配iBatis.NET框架的项目，其他ORM框架（如MyBatis、Dapper等）暂不支持；
2. 仅支持通过C#接口方法与XML SQL定义的关联跳转，不支持非接口类的方法映射；
3. 仅识别XML格式的SQL配置文件，其他格式（如注解式SQL、JSON配置等）暂不支持。


## 支持与反馈

如果该插件对您的开发工作有帮助，欢迎通过下方渠道支持项目发展：
- 扫码支持：![项目支持二维码](images/reward_code.png)
- 代码贡献：前往项目GitHub仓库提交Issue或Pull Request，共同完善功能；
- 问题反馈：若使用中遇到bug或需求建议，可在GitHub Issues板块留言，我们会尽快响应。