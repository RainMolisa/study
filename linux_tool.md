# 记录用过的linux小工具
## 1 sed
版本：sed (GNU sed) 4.8
```
sed -n '5350636,5351160p' ./compile_commands.json  打印文件下5350636行到5351160行
sed -i 's#{字符串1}#{字符串2}#g' {文件} 在文件里替换字符串
```
