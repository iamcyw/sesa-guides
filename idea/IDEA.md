# IDEA安装使用

## 1. 下载地址

 > FTP地址：

## 2. 运行程序

 > 运行ideaIU-2019.2.win\bin\idea64.exe

   ![文件目录](assert/exeMain.jpg)

## 3. 导入设置

 > **参考其他文章[IDEA设置项导入](idea/importSetting 'IDEA设置项导入')**

## 3. 设置新项目JDK

 ![菜单选择设置JDK](assert/2019-08-19-16-32-42.png)
 ![设置SDK](assert/2019-08-19-16-41-17.png)
 > 点击新建，选择本地的J8K8的安装目录，完成后点击OK回到启动器

## 4. 修改用户名

 > 1. 打开IDEA的bin目录，找到**idea64.exe.vmoptions**
 ![找到vmoptions](assert/2019-08-20-12-26-55.png)
 > 2. 编辑文件，修改**Duser.name=自己的svn名称**
 ![修改用户名](assert/2019-08-20-12-30-23.png)

## 5. 导入项目

 > 点击导入按钮，选择项目目录

 ![导入项目按钮](assert/2019-08-19-20-26-46.png)
 > 如图选择按Gradle项目导入

 ![选择gradle](assert/2019-08-19-20-30-37.png)
 > 等待项目导入成功

## 6. 运行项目

 ![运行项目](assert/2019-08-19-21-31-23.png)
 > 1： 选择右侧面板的Gradle  
 > 2： 运行Server模块的Gradle Task：bootRun  
 > 3： 运行Webapp模块的Gradle Task: bootRun
