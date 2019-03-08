# 扩展X虚拟机外壳

# 此仓库提供叫全面的操作系统X编译器与X虚拟机外壳下载

xcross@xxx 的文件下载后需更名为xcross, 扩展名不变
如xcross@win_x64.exe下载后需更名为 xcross.exe

# xcross 与bin目录需保持不变


bin/darwin/ 为Mac OSX虚拟机外壳 

bin/linux/arm/ 仅支持测试树莓派3B+ 官方jessie操作系统

bin/linux/x86/ 支持linux X86架构的操作系统

bin/linux/x64/ 支持linux X64架构的操作系统

bin/windows/x86 为 Windows x86 平台虚拟机外壳 (注意：不支持XP)

bin/windows/x64 为 Windows x64 平台虚拟机外壳 (注意：不支持XP)


### 下载后将此目录与 XStudio 下的 bin 目录重叠覆盖即可直接使用 XStudio 将项目编译对应平台的项目,  在菜单[项目属性]中更改目标平台与操作系统即可。

### 手动编译请参考 xcross 命令行.
