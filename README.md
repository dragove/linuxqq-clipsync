# Linuxqq-Clipsync

通过同步 X11 和 Wayland 剪贴板的方式修复 Linuxqq 以 Wayland 运行时的剪贴板异常。

## 依赖

`xclip` `wl-clipboard` `clipnotify`

## 安装

- Arch Linux

    ```
    yay -S linuxqq-clipsync-git
    ```

- 其他发行版

    ```
    You'll figure it out.
    ```

## 使用方法

运行`linuxqq-clipsync`命令即可，也可以使用systemd服务。 

```
systemctl enable --user linuxqq-clipsync
```

