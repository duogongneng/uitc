### Github AccessToken获取方式

1. 登录 [Github](https://github.com/) ，并打开设置页面。

![image](https://user-images.githubusercontent.com/71535361/215311139-baf78b72-dd85-4870-9cb2-0eb87b20b222.png)

2. 单击“Developer settings”。

![image](https://user-images.githubusercontent.com/71535361/215311166-cd01ea81-9151-448b-9680-4e489d3515f8.png)

3. 单击“Personal access tokens > Generate new token”。

![image](https://user-images.githubusercontent.com/71535361/215311173-587a3049-7f3f-43d6-b9f8-4f4a38fcb9a3.png)

4. 验证登录帐号。

![image](https://user-images.githubusercontent.com/71535361/215311183-536e4d52-1341-476e-b1af-bbc1032d3a65.png)

5. 填写Token描述并选择权限，选择私有仓库访问权限，单击“Generate token”生成Token。

![image](https://user-images.githubusercontent.com/71535361/215311318-d2f3f921-b375-4c23-87e7-43c43cb87d15.png)

6. 复制生成的Token到编译构建服务即可。

![image](https://user-images.githubusercontent.com/71535361/215311189-1200b858-3c99-47c5-8b8f-2847c65ed76e.png)

#### 说明：
Token生成后，请及时保存，下次刷新页面将无法读取，需要重新生成新Token。
注意填写有效的Token描述信息，避免误删除导致构建失败。
无需使用时及时删除Token，避免信息泄露。
