# 准备工作  
  全局安装angular/cli:
    cnpm i -g @angular/cli
  安装IDE插件
  安装chrome扩展
    chrome://extensions/
    替代方案：http://chrome-extension-downloader.com/,输入id：elgalmkoelokbchhkhacckokjkejnhcd，但是失效了，尝试下面的方法
    https://augury.rangle.io/，也失败了先跳过。
  npm i -g json-server 用于mock数据
  测试数据获取：
    postman
    使用vscode的REST Client插件

#新建项目
  ```
     ng new taskmgr --skip-install(-si) --style=scss
     cnpm install
  ```
  创建核心模块
  ```
    ng g m core
    ng g m shared
  ```

