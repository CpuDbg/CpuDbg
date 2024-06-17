## CpuDbg is currently a closed-source project, and this repository is solely for bug reporting.

#### CpuDbg is a debugger that supports all platforms, including but not limited to Windows Android Iphone as well as WEB and hardware platforms.
#### The interface and functions of CpuDbg are referenced to OllyDbg. Special thanks to Mr. Oleh Yuschuk, the author of OllyDbg, for writing such an excellent debugger for us. If there is no OllyDbg debugger, there will be no CpuDbg debugger.

#### CpuDbg currently only supports running on the Windows platform. It may consider supporting other platforms in the future. The project of CpuDbg is very, very large, and currently only supports debugging Windows 32-bit and 64-bit programs. (16-bit is not supported temporarily).

### Some notes about debuggers.

If you want to switch languages, you can do so through the menu settings below. (Currently, only Chinese and English are supported)

如果您想要切换语言, 可以通过下面菜单设置. (目前只支持中文和英文)

![switch_lan](https://github.com/CpuDbg/CpuDbg/assets/134661959/4bb6bad3-6f2e-40e8-a807-4a679a351600)


If you are a Windows x64 system, you are debugging a 32-bit program. When you drag the target program into the debugger window, or press F3 to open the target program, the program will break at the place as shown below:

![image](https://github.com/CpuDbg/CpuDbg/assets/134661959/a6413601-a444-4743-84e8-7814ae63b104)

As shown in the figure above, you will find that the debugger breaks in 64-bit ntdll. This is because when a 64-bit debugger is debugging a 32-bit program, it will by default pass through the WOW64 interrupt information. You can set it in the (Alt+O) debug option, as shown below:

![image](https://github.com/CpuDbg/CpuDbg/assets/134661959/60a4c19b-61e3-4ba5-8f85-ccf1bd9fb255)


After this setting, the program will not be interrupted in 64-bit ntdll, but interrupted in 32-bit oep. As shown below:

![image](https://github.com/CpuDbg/CpuDbg/assets/134661959/cdc4d578-c84d-40be-b221-be21efbcf305)



------------------download------------------

https://github.com/CpuDbg/CpuDbg/releases

如果你不会魔法, 可以从下列地址下载:

链接:https://pan.baidu.com/s/1CLMAceVhgClZrfA6GR8hrw?pwd=cpuu 提取码:cpuu 复制这段内容后打开百度网盘手机App，操作更方便哦

------------------download------------------


------------------------------------------------------------------------------------------------------------------
Currently CpuDbg is not perfect, she still has a lot of bugs. Please give her some time, let her grow slowly... 😉

to be continued...

