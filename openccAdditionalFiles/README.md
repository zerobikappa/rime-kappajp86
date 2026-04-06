此文件夹中的文件，是日文平假名与片假名转换的配置文件。
opencc是一个简繁文字转换的组件，利用其原理，配置一个 平假名==>片假名 的映射词库，可做到平假名转换成片假名。
在安装完rime输入法后，必须要安装opencc才能使用这个配置。
hiragana2katakana.json 是opencc平片假名配置文件

安装完opencc后，将此文件夹中的 hiragana2katakana.ini 和 hiragana_to_katakana_characters.ocd 两个文件复制到/usr/share/opencc/ 中（此文件夹中应该也有其他的.ini 和 .ocd 文件）。需要注销才能应用此配置。
hiragana_to_katakana_characters.ocd 是平假名==>片假名映射码表

如果使用:
(1) 安装opencc
```bash
#for ubuntu
apt install opencc

#for archlinux
pacman -S opencc

```

(2) 生成ocd2格式的二进制映射文件
```bash
opencc_dict -i hiragana_to_katakana_characters.txt -f text -t ocd2 -o hiragana_to_katakana_characters.ocd2

```

(3) 将`hiragana_to_katakana_characters.ocd2`和`hiragana2katakana.json`移动到opencc存放映射文件和配置文件的目录，例如`/usr/share/opencc/`

(4) 注销然后重新登入桌面环境
