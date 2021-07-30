# wine-loader
Auto select `wine` and launch windows `.exe` file.

To use this program, you should install `pefile` python package as below.
```sh
/usr/bin/pip3 install pefile
```

Rename `wine-loader` to `<name>`. Double click it or type `./<name>`, then it will find the correct architecture of `wine` and launch `<name>.exe`.
Make sure that file `<name>.exe` exists!

To customize `wine` path, you should add the path [here](https://github.com/yaoxi-std/wine-loader/blob/main/wine-loader#L31-32).

Example:
```sh
bash-3.2$ ls
windows-app.exe	wine-loader
bash-3.2$ mv wine-loader windows-app
bash-3.2$ ls
windows-app	windows-app.exe
bash-3.2$ ./windows-app
...
```
