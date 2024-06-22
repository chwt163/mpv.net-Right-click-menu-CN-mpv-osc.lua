# modernx-fork.lua osc 主题：

Forked from [ModernX](https://github.com/zydezu/ModernX)

![mpv](https://github.com/chwt163/Mpv.netRrightClickMenuCN/assets/70951194/e752e6a3-d2ea-43b7-8dac-ea6d477e5b00)


# Mpv.net 右键菜单：


![1](https://github.com/chwt163/Mpv.netRrightClickMenuCN/assets/70951194/26be7888-003a-4222-ad11-85594cef6b41)



# 设定 osc 主题：

# mpv：

1、在 mpv 程序文件夹里面新建 `scripts` 和 `fonts` 两个文件夹。

mpv 本身是绿色免安装软件，把上面两个文件夹放在 mpv 的程序文件夹里面，或者放在用户配置文件夹 `\%APPDATA%\mpv\` ，都是可以的，如果是 Linux/MacOS 系统，则放在 `~/.config/mpv/` 里面

2、下载 `modernx-fork.lua` 放在 `scripts` 文件夹

3、下载字体文件放在 `fonts` 文件夹：

[Material-Design-Iconic-Round.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Round.ttf)

[Material-Design-Iconic-Font.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Font.ttf)

4、编辑 `mpv.conf` ：
```
osc = no
```




# mpv.net：

mpvnet 和 mpv 的 osc 主题是通用的，mpvnet 只是多了一个 `portable_config` 文件夹

1、在 mpv.net 的程序文件夹里面新建 `portable_config` 文件夹

2、在 `portable_config` 里面新建 `scripts` 和  `fonts` 两个文件夹

3、下载 `modernx-fork.lua` 放在 `scripts` 文件夹

4、下载字体放在 `fonts` 文件夹：

[Material-Design-Iconic-Round.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Round.ttf)

[Material-Design-Iconic-Font.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Font.ttf)

5、编辑 `mpv.conf` ：
```
osc = no
```



# 设定 mpv.net 中文右键菜单（新版 mpvnet 已经原生支持中文菜单）：

先安装 mpv.net，替换 `input.conf` 即可。

input.conf 一般放在以下路径，选其一：

1、程序文件夹： `portable_config`

2、用户配置目录 `\%APPDATA%\mpv.net\`

也可以直接从 mpv.net 的右键菜单中打开配置文件夹： Settings > Open Config Folder





