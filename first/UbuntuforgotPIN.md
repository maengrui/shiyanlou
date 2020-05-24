# 乌班图忘记密码

1. 进入系统时选择ubuntu 高级选项

   ![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml2924\wps1.jpg)

   2.进入后选择recovery mode 2个任选1。注意：**选择完后按E，进行编辑**

   ![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml2924\wps2.jpg)

   3.删除字符recovery nomodeset,在文本末尾后面加入文本

   ```text
   quiet splash rw init=/bin/bash
   ```

   ![image-20200523225931873](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200523225931873.png)

   4.按F10(或Fn+F10)或者Ctrl+x

   ![image-20200523230220899](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200523230220899.png)

   5.输入passwd 用户名,系统提示再次输入修改密码，最后提示修改成功。

   ![image-20200523230500427](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200523230500427.png)

   6.如果不清楚用户名，#后输入指令，查看用户名。

   ```text
   cat/etc/shadow
   ```

   