# URTC-demo（纯 JS 版本）

## 运行步骤

1. 添加配置

js 目录下的 创建 config.js 文件，并配置 AppId 和 AppKey，示例代码：

```
window.config = {
  AppId: 'urtc-xxxxxxxx',
  AppKey: 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
}
```

> 注：
> 
> 1. AppId 和 AppKey 可从 URTC 产品中获取
> 2. AppKey 不可暴露于公网，建议生产环境时，由后端进行保存并由前端调 API 获取

2. 安装 npm 依赖包   

在本地demo目录下，执行以下操作：    

```
npm install
```

3. 执行运行命令

```
npm start
```

4. 打开页面

浏览器打开 http://localhost:3001
