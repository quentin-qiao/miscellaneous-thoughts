# Typora图床配置

1. 配置github

2. 安装node.js

3. cmd安装配置picgo core

   **用npm命令安装picgo**

   ```
   npm install picgo -g
   ```

   **输入命令查看版本，如果有输出则添加成功。**

   ```
   picgo -v
   ```

   **github原上传插件不好用，再安装一个上传插件**

   ```
   picgo install github-plus
   ```

   **配置picgo uploader**

   ```
   picgo set uploader
   repo: quentin-qiao/images
   branch: main
   token: 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
   path: img/
   customUrl:
   success
   ```

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20221015195659952.png" alt="image-20221015195659952" style="zoom: 50%;" />

4. 配置typora

   **修改插入图片时选项**

   **上传服务选择自定义命令**

   **命令为picgo upload**

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20221015194513018.png" alt="image-20221015194513018" style="zoom:33%;" />

   