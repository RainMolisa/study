# 记录用过的linux小工具
## 1 sed
版本：sed (GNU sed) 4.8
```
sed -n '5350636,5351160p' ./compile_commands.json  打印文件下5350636行到5351160行
sed -i 's#{字符串1}#{字符串2}#g' {文件} 在文件里替换字符串
```
## 2 wc
版本：wc (GNU coreutils) 8.32
```
wc -l {文件} 打印文件行数
```
## 3 解压rar
```
unrar x DeepSeek-R1-0528-Qwen3-8B.rar
```
## 4 查看磁盘空间大小
```
df -h
```
## 5 查看某个文件夹下文件大小
```
du -h <路径>
```
## 6 搜索文件关键词 grep (GNU grep) 3.7
```
grep -rns "你的关键词" <文件路径>
```
## 7 压缩文件夹 tar (GNU tar) 1.34
```
tar -czvf 输出文件名.tar.gz ./你要压缩的文件夹
```

