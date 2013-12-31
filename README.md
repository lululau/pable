# pable

An CLI utility which can make TUI tables


# 使用方法

```
 -h, --help  Print help messages.
 -d <delimeter> field delimeter, default to white characters.
 -n, --field-number <n> number of fields, default to the number of fields of the first line.
 -c, --columns <columns> Specify which fields to print, for example: `-c 1,3-4,7,9' (origin 1).

 You can specify only one option of `-n' and `-c'.

 ./pable reads data from STDIN and print result table to stdout.

```

# 示例

![示例截图](http://imglf0.ph.126.net/XHXJh6ifz3f7Mawc2QzVIw==/1829587348719497790.png)

# 安装

```
git clone https://github.com/lululau/pable
cd pable
sudo cp pable /usr/local/bin/
sudo cpan 
pable --help
```