<h2>修改hosts文件-方法一</h2>

用文本编辑器打开hosts文件，将以下内容复制进去，保存即可（hosts 文件没有后缀）<br/>

<br/>Windows 用户可以以管理员身份直接运行 notepad "%SystemRoot%\system32\drivers\etc\hosts" 进行 编辑

<br/>Linux 和Mac用户用文本编辑器（需要root权限）修改 /etc/hosts 即可开始编辑

<br/>关闭某个IPv6的转发请在那一行的最前面添加#号，启用请去除最前面#号，每行中间的#号是为了区分地址 和注释，不用理睬