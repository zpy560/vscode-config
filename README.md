# vscode-config
配置vscode中的c++环境
# 1 先解压安装包到固定位置
D:\mingw-w64\x86_64-8.1.0-release-win32-seh-rt_v6-rev0\mingw64\bin
# 2 添加系统环境变量（任意用户都能使用），用户环境变量（只能限定用户下使用）
D:\mingw-w64\x86_64-8.1.0-release-win32-seh-rt_v6-rev0\mingw64\bin
# 3 注意配置tasks.json文件command
"command": "D:\\mingw-w64\\x86_64-8.1.0-release-win32-seh-rt_v6-rev0\\mingw64\\bin\\g++.exe",
# 4 配置launch.json文件miDebuggerPath
"miDebuggerPath": "D:\\mingw-w64\\x86_64-8.1.0-release-win32-seh-rt_v6-rev0\\mingw64\\bin\\gdb.exe",
# 5 配置c_cpp_properties.json文件compilerPath
"compilerPath": "D:/mingw-w64/x86_64-8.1.0-release-win32-seh-rt_v6-rev0/mingw64/bin/g++.exe",