# python0401
less 分页浏览 分页浏览文件内容，类似 more 命令，基本语法 $ less file # 分页浏览 file  $ less -N file # 分页浏览 file，并展示行号  $ less -m file # 分页浏览 file，并显示百分比  sort 排序浏览 sort 命令可以用来对文本文件中的内容进行排序查看，默认为字典升序 $ sort 文件 # 字典升序查看文件内容  $ sort -r 文件 # 字典降序查看文件内容  $ sort -u 文件# 剔除文本文件中重复的内容  $ sort -n 文件# 按照数字排序  sed 流式浏览 sed -n "1,5p" 文件   显示1~5行内容 sed -n "3,5{=;p}"   显示3~5行内容,并且打印行号 sed -n "10p"  显示第10行内容
