
# 🌐 FOFA-X 查询工具 🛠️

## 简介
**FOFA-X 查询工具**是一个基于Python开发的图形化应用程序，专为网络安全研究人员设计。该工具通过FOFA API进行查询，提供了便捷的界面、批量导出、标签管理等功能。**
### 作者0xShe
### 下载地址：https://github.com/0xShe/FOFA-X/releases/tag/Fofa-X
---

## 📋 功能概览
1. **查询功能**：输入FOFA的API Key和查询语句，快速获取结果。
2. **标签管理**：支持多标签页查询，方便用户同时查看多个查询结果。
3. **数据导出**：可将查询结果导出为Excel格式，便于后续分析。
4. **右键菜单操作**：支持复制URL、IP、域名等数据，并提供快捷查询功能。
5. **快捷查询**：可一键查询C段 标题 IP。
6. **Key的记忆** 若需要软件记住你的key请手动修改key.ini。

---

## 🛠️ 使用指南
### 1. 启动程序
运行 `Fofa-X` 程序后，将看到如下界面：
![image](https://github.com/user-attachments/assets/1d5db17d-d78c-43e8-a160-d2adb21342eb)

- **Key输入框**：输入FOFA API的Key。
- **条数输入框**：设置查询返回的结果条数。
- **查询语句输入框**：输入FOFA支持的查询语句。
- ![image](https://github.com/user-attachments/assets/489d3e58-8f6d-4947-8c18-76619cef08be)


### 2. 执行查询
- 点击“**查询**”按钮即可发送请求，并显示结果于新标签页中。
- 支持多标签查询，用户可同时查看多个查询结果。
  

### 3. 导出数据
- 在任意标签页中点击“**导出所有数据**”按钮，即可将当前数据导出为Excel。

### 4. 使用右键菜单
- 在查询结果中右键点击某一行，可选择：
  - **复制网站URL**
  - **复制IP地址**
  - **复制主域名**
  - 快捷查询 **IP C段** 或 **标题** 等。


![image](https://github.com/user-attachments/assets/0d9313a1-3ac3-4dba-864e-75e430a2a8c6)

---

## 🖥️ 致谢
- 本软件由衷向FOFAviewer致谢。
- 本人使用FOFAviewer多年 最近发现随着不同的Java版本 会导致无法导出Excel。
- 所以诞生了FOFA-X 【打包成exe 打开即用】。

---

## 🔧 开发与配置
- **配置文件**：首次运行时，程序会加载 `key.ini` 配置文件，自动填充API Key。
- **API接口**：调用FOFA API时，将查询语句转为Base64格式。
![x2](https://github.com/user-attachments/assets/ce4c5f9b-11f0-49f5-9d4e-c488b7c7e1d6)

---

## 🔴 注意事项
> 本软件仅供合法合规使用，禁止用于任何违法活动，否则后果自负！
> 禁止某些割韭菜的星球圈子等反编译换个署名就往韭菜堆里发！尊重原创！

---

## 📢 关于作者
- **作者**：0xShe
- **项目地址**：[GitHub](https://github.com/0xShe/FOFA-X)
- **微信公众号**：安全社

---

## 🚀 联系与支持
如果在使用过程中遇到问题，欢迎通过GitHub提交Issue，或访问[0xShe网络安全导航](http://sbbbb.cn)获取更多资源。
