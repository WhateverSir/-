# 注册表批量替换脚本
利用Windows PowerShell对regedit注册表进行关键词批量替换的脚本。

例如将中文名文件夹替换为英文名。
# 步骤如下：
* 将两个文件下载至同一目录下
* 运行Windows PowerShell
* cd 到文件所在目录
* 打开run.ps1文件，对第三行的两个参数进行修改，分别修改为被替换的关键字和要替换的关键字
* 在PowerShell运行脚本./run.ps1
* 最后会在同一目录下生成log文件，可查看被替换的条目
