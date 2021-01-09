使用 tar 命令来创建压缩文件，如：
tar czvf - <file_name> | split -b <max_size>

使用 tar 解压：
cat x* | tar xzvf -

