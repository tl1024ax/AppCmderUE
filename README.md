
支持通过命令行启动 UE Android App 并传递参数。参考资料：https://imzlp.com/posts/29169/

详见文章：[高效调试：命令行参数启动 UE Android App](https://imzlp.com/posts/29169/)

This is an Unreal Engine plugin that can easily specify command-line parameters for Android through adb.

Usage: choose engine version bat script(\*_ue4.bat/\*ue5.bat).

```bash
append_cmd_ue4.bat com.imzlp.gworld "-test123" "-test456" "-test789"
```

Log:

```txt
Final commandline: ../../../Blank426/Blank426.uproject -test123 -test456 -test789
```

