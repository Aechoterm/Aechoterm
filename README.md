# 简介
Aechoterm（中文名：闪令）是一款免费的、跨平台的，以SSH、SFTP协议访问远程服务器的终端、文件管理工具。可以将本地与远程主机文件进行互传，并可在多个远程服务器上同时执行命令。
# 基本特点
完全免费，风格简约，支持中文，自带sftp，安全稳定，Windows/macOS/Linux多平台可用。
# 官网
https://ec.nantian.com.cn
# 功能概览
1. ssh
  - 本地会话
  - 远程会话
2. sftp
  - 自动创建sftp
  - 上传下载文件
  - 图形化操作
3. 会话管理
  - 保存会话信息
  - 分组管理会话
  - 导入/导出会话
  - 快捷命令
  - 分屏操作
  - 批量输入
  - 多标签显示
  - 实时监控服务器资源信息
  - 快捷复制粘贴
3. 云同步
  - 同步会话信息
  - 同步设置信息
  - 同步快捷命令
4. 其它
  - 自定义主题
  - 自定义会话设置
  - 多语言输出
  - 高亮显示
# 功能图解
1. 远程SSH连接
 - 登录方式：用户名密码或用户名密钥登录。
 - 会话分组：可自定义组名或选择已有分组。
 - 自动创建sftp：连接成功后，同步创建sftp。
 - 测试连接：输入会话信息，测试内容是否正确。
 - 保存会话：将当前会话保存到本地数据库中，连接成功后，将展示在左侧会话列表中。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148321067-b018bf75-56e8-494c-8141-7d5fe84dd6fd.png">

2. 会话列表
 - 会话列表可显示或隐藏。
 - 会话分组展示：以组为单位，展示或隐藏。
 - 会话搜索：关键字智能匹配，快速搜索。
 - 会话排序：单个会话和分组会话可上下拖拽排序。
 - 单会话管理：右键某个会话，可重新编辑、重命名、删除会话、导出会话到本地。
 - 多会话管理：右键列表空白处，快速新建、刷新会话、批量导出全部会话到本地。
 - 分组会话管理：右键某个会话组，可导出该组会话到本地。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148321392-69100c46-8ed7-4009-965d-cb6333b85fce.png">
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148321775-7e80e224-4253-4534-9b18-b70968678eae.png">

  - 文件导入：创建中选择导入本地文件。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148321943-ae7f7a68-393a-47cd-9c00-15dff08196b5.png">
  
3. 会话窗口
 - 内容搜索：搜索会话终端内容，支持正则方式。
 - 清屏：一键清除所有内容。
 - 分屏：支持横向、纵向多屏显示。
 <img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322095-9b30fc70-9f4b-4170-86e4-dd2077d85c0f.png">
 <img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322109-483cc4a3-3865-4d75-a5f4-1301903c6eca.png">
 
  - 新窗口打开当前会话：右键tab标题，可将当前会话以新的窗口打开；在新窗口中，点击右上角的图标按钮，可还原回主窗口。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322159-31f97f2f-f7ec-4d02-84fb-a1b770ba7505.png">

4. 快捷命令
- 管理命令：在导航栏选择快捷命令，在弹窗左侧输入常用命令后，点击保存，将命令保存到右侧的命令列表；在右侧的命令列表中可以搜索已保存的命令，右键点击某个命令可置顶、编辑或者删除命令。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322451-ded28134-daa3-4e8d-9179-a1724eb7f6cf.png">

- 使用命令：打开某个SSH连接后，在会话界面右下角可以使用快捷命令。输入内容可进行模糊搜索，单击命令即可输入到终端。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322477-72fd484c-6daa-413e-af8b-98ec64c094b7.png">

5. 批量输入
- 在会话终端界面的下方，输入命令，并批量执行到所有开启的会话终端上。包含使用独立窗口打开的会话。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322521-2c7e0947-5a3f-4753-b9cd-eb0614a6a53c.png">

6. 实时的CPU、内存以及磁盘使用状况监控
- 在会话终端的右下角，实时展示CPU以及内存的使用率。
- 点击可展示出详细的监控界面，再次点击可以关闭监控界面。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322625-66efcfd2-f14b-4eee-9c9d-8898f6d9492b.png">

7. 云同步
- Aechoterm支持微信或手机验证码登录。
- 登录后可将会话信息、设置信息、快捷命令分别上传至云服务器。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322659-fffe3dfd-3d52-4b18-9bf6-49b4c19b59f8.png">
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322666-4cb17218-08ca-45f2-a9d4-4149aa783736.png">
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322672-4ef675f0-d143-450a-be9c-39c1509e5ba6.png">

注: 上传至云服务器的数据，会经过用户自定义的密码加密后上传，Aechoterm不会保存用户输入的安全密码，服务器只会保存上传信息的密文，请大家放心使用此便捷功能。

8. SFTP文件管理
- 新建SSH连接后，点击会话终端上的SFTP切换到文件管理工具的tab页，查看和管理文件。
- 同步显示：左侧为本地文件列表，右侧为远程服务器的文件列表。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322756-fe6ab78c-6822-429f-a3f0-5ce82d0cb5c6.png">

- 拖拽传输：通过鼠标左键按住文件名称不放并拖拽的方式进行文件传输；支持多选后一次性拖拽；支持本地和远程文件双向上传或下载。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322786-db32be72-4c32-43ff-a3bf-fe6dc20a284a.png">

在本地系统中，可直接拖拽文件或文件夹到远程服务器文件窗口中，上传文件或文件夹。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322822-3bc33b8e-d2b2-4a73-b6c0-bb1252fa45ae.png">

 注: 触发拖拽的有效范围是文件名称那一列。如果想将文件直接上传到服务器的当前列表中的某个文件夹下，需要将文件拖拽到文件夹的名称上，否则将只会上传文件到服务器的当前文件列表下。

- 快速定位：文件夹地址栏中，将鼠标移动到左侧的图标上，可选择某个盘符直接进入；可点击文件夹名称直接进入；可复制地址，直接输入到地址栏，回车进入。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322885-a13abc1c-e8e6-4fc2-befb-d46c74f02bcb.png">


9. 内置文本编辑器
- 远程服务器上的文本文件，可直接双击打开，并编辑。
- 支持大部分编程文件格式，以及配置文件格式的语法高亮。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322911-2962a5a5-1952-4c2a-9144-369a8bcf94f4.png">

 注:若有其他需要支持的格式，以及在使用中遇到的任何问题、建议都可通过软件标题栏帮助菜单中的反馈功能，反馈给我们。

 10. 设置
- 根据个人喜好选择软件主题色，Mac上可设置为跟随系统。
- 多种终端类型可选、自定义字体大小行数等。
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94167606/148322958-88cd2890-ddee-4f73-9385-090e86ccd302.png">

11. 快捷键
- Ctrl + M -- 回车
- Ctrl + R -- 显示上一条命令
- Ctrl + H -- 删除光标前的1个字符
- Ctrl + L -- 清屏
- Ctrl + A -- 选中所有文件或文件夹
- Ctrl + C -- 复制文件或文件夹
- Ctrl + V -- 粘贴文件或文件夹
- F5 -- 刷新文件列表
- F2 -- 重命名
- Delete -- 删除选中文件或文件夹
