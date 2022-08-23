# INSTALLAAB
>## 本地安装AAB包到手机

>1.工具功能描述  

&emsp;&emsp;该工具可以将aab包转化为apks，并在连接手机的情况下将该aab包安装到手机方便进行测试  

>2.材料准备  

&emsp;&emsp;需要在INSTALLAAB/根目录下放入需要安装的aab包  
&emsp;&emsp;根目录下必须仅放置一个aab包  
&emsp;&emsp;放入该aab需要的签名文件，并对config.ini进行配置，配置方法同APK2AAB工具  
&emsp;&emsp;连接手机，打开调试，选择传输文件  

>3.执行命令  

python installaab.py  

>4.常见错误及解决方法  

&emsp;&emsp;出现：error: None output:  
&emsp;&emsp;说明：已经签名成功并生成了apks文件  

&emsp;&emsp;出现：offline  
&emsp;&emsp;原因：当前连接的手机已经断开连接  
&emsp;&emsp;处理：需要断开并重新连接下手机插口  