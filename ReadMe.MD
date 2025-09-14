# Jump to SQL


用于在iBatis.NET项目中从C#接口方法名快速跳转到对应的XML SQL定义。反之, 可以跳转到接口定义。快捷键需要安装完毕后, 自己映射一下,工具 -> 选项 -> 环境 -> 键盘 搜索jump, 选中分别设置快捷键才能生效。

## 安装

1. 从Visual Studio Marketplace安装插件: https://marketplace.visualstudio.com/items?itemName=xiaochuanling.xcl123&ssr=false#overview
2. 或者去github下载插件, 手动安装插件;
3. 重启Visual Studio;

## 使用

1. 打开iBatis.NET项目
2. 定位到C#接口方法的所在行, 右键选择菜单选择 '转到SQL', 或者使用快捷键 'Ctrl + Alt + Shift +S'(快捷键需要自己绑定后才生效)
3. 定位到XML SQL定义的所在行, 右键选择菜单选择 '转到接口', 或者使用快捷键 'Ctrl + Alt + Shift +I'(快捷键需要自己绑定后才生效)
4. 即可跳转到对应的XML SQL定义

## 注意

1. 插件仅支持iBatis.NET项目
2. 插件仅支持C#接口方法
3. 插件仅支持XML SQL定义

如果觉的本项目对你有用,请打赏
![打赏码](images/reward_code.png)
