
为了处理从 B站 下载的视频去掉开头又臭又长的前缀名字弄的，没啥技术难度，搞着玩的。

## Mac 使用方法
- 解压文件
- 进入到文件夹执行运行命令
```shell
# rename-mac
./run

# 配置 config.yml
```

- 配置参数
```text
DIRPATH            // 文件夹路径 这里需要填写绝对地址
SRCPART            // 文件名称开头相同的部分
REPLACE            // 需要替换的部分 默认为空 就是删除相同部分
```

- 再次执行修改文件名称
```shell
./run
```

## Windows 使用方法

- 解压文件
- 进入到文件夹双击执行
- 配置参数