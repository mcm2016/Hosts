欢迎使用hosts！
1.下述使用指导均可能覆盖现有 hosts ，如现有 hosts 内容重要的话请事先备份。您也可以使用我们的 Host Tools 来自动化 备份/配置 的工作。
2.根据下述使用指导配置完成后，您将需要“重置网络”：

重启系统
拔插网线
启用禁用飞行模式
在系统设置内开关网络
如果不先重置网络的话， hosts 将无法使用。

Windows

用文本编辑器（如记事本等）打开文件：

C:\Windows\System32\drivers\etc\hosts
将下载的hosts文件中的内容全部内容复制到该文件中并保存。

注意：如果遇到无法保存，请右键文件hosts并找到“属性” -> “安全”，然后选择你登陆的用户名，最后点击编辑，勾选“写入”即可。
Mac OS

请 新建/修改 /private/etc/hosts 文件，并将我们的hosts文件中的内容全部内容复制到该文件中并保存。

也可以使用Gas Mask工具。
Android

请 新建/修改 /system/etc/hosts 文件，并将我们的hosts文件中的内容全部内容复制到该文件中并保存。

iOS

请 新建/修改 /etc/hosts 文件，并将我们的hosts文件中的内容全部内容复制到该文件中并保存。

Linux

请 新建/修改 /etc/hosts 文件，并将我们的hosts文件中的内容全部内容复制到该文件中并保存。

或是开启终端（快捷键为Ctrl + Alt + T）并直接使用下述命令：

bash -c 'wget https://raw.githubusercontent.com/racaljk/hosts/master/hosts -qO /tmp/hosts && sudo mv /tmp/hosts /etc/hosts'
License

本项目的所有代码按照 MIT License 发布。
本项目的hosts，README.MD，wiki等资源基于CC BY-NC-SA 4.0 这意味着你可以拷贝、并再发行本项目的内容，但是你将必须同样提供原作者信息以及协议声明。同时你也不能将本项目用于商业用途，按照我们狭义的理解（增加附属条款），凡是任何盈利的活动皆属于商业用途。若你无法遵守上述的责任和义务，请不要拷贝、并再发行本项目。
