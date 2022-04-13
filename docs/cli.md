# 脚手架

贴心的提供了几个命令工具用于创建项目和插件

## 创建项目 init

```shell
botoy init
```

## 创建插件 add

```shell
botoy add
```

## 启动机器人 run

```shell
botoy run
```

## 启动机器人并开启自动重载 hot

```shell
botoy hot
```

要求机器人主文件命名为 bot.py

## 测试连接

```shell
botoy test
```

## 插件管理

```shell
botoy plugin
```

## 快速启动

```shell
botoy sweet
```

和 run 不同的是，该命令会自己创建机器人对象，只会读取插件

## 帮助

```shell
botoy
botoy --help
botoy init --help
botoy add --help
botoy test --help
botoy sweet --help
botoy plugin --help
botoy plugin install --help
botoy plugin remove --help
botoy plugin list --help
```

!!!tip

    如果 botoy 运行不了，请尝试使用`python -m botoy`替代`botoy`
