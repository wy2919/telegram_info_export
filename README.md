# Telegram_Info_Export

- 导出群组和频道（有邀请链接和无邀请链接分开显示）
- 导出机器人
- 导出对话中的个人用户（不包含无用户名的）

### 使用说明

> 将`telegram_info_export.exe`和`config.ini`放在同一目录下

- `api_id`和`api_hash`需要到[Telegram 开发者平台](https://my.telegram.org/auth)申请
- proxy_url 格式

```
socks5://wowyijiu:wowyijiu@127.0.0.1:23333
socks5://127.0.0.1:23333
http://127.0.0.1:7890
```

手机号格式：+130727xxxxx

如果报错 406: UPDATE_APP_TO_LOGIN 就是pip依赖版本太低需要更新

```
pip install --upgrade telethon
```


### 示例图

![应用](https://cdn.jsdelivr.net/gh/WowYiJiu/image@master/git/image.5jsppfdyeq40.webp)

![导出](https://cdn.jsdelivr.net/gh/WowYiJiu/image@master/git/image.7htsb7kxl2g0.webp)

![导出信息](https://cdn.jsdelivr.net/gh/WowYiJiu/image@master/git/image.21sh6p5c05cw.webp)

### 鸣谢

[囧囧 JOJO](https://github.com/jiongjiongJOJO)
