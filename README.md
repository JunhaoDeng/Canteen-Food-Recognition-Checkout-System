# 食堂图片拍照结账系统
## 先决条件
1. Python 3.6及以上
2. import所需要的各种模块
3. Jupyter Notebook
## 文件说明
1. Food_Reg_GUI_multi.ipynb：这是一张图片可以检测多个食物的智能检测系统，会根据所拍的所有图片食物的总数进行结算
3. Food_Reg_GUI_Single.ipynb：这是一张图片只可以检测一个食物的智能检测系统，会根据所拍的所有图片食物的总数进行结算
4. sqlite_database.ipynb：这是创建卖家sqlite数据库的程序，可以让卖家在数据库中创建新的食物种类和价格
5. Database文件夹：这里有两个数据库，一个叫name_value，一个叫buy_value。name_value是卖家数据库，用于添加食物种类和价格。
buy_value是客户的账单，包含检测出来的食物和价格，每次结算完账单这个buy_value数据库就会被删除。
5. Food_picture：会存储食物拍照的图片，结算后所有图片会被清空
6. Food_Reg_GUI_multi-revise1.ipynb： 这个是拍一张图片或者去浏览文件加的一张png图片，程序会根据所拍的图片，
左半边显示食物并且每个识别出来的食物会有方框，右边会有扫面出来的结账清单。checkout_picture.png是最终的扫描食物识别结果图片
7. Merchant_database_OS.ipynb：这个是商家食品价格清单系统，可以往buy_value数据库中添加食品类和价格。

注意：
1. 所有"C:\\Users\\Junhao's Alienware\\food_recognition\\Database/buy_value.db"这个为buy_value.db在我的电脑中的路径，
因此您应该修改"C:\\Users\\Junhao's Alienware\\"这一部分为你存储food_recognition文件夹的绝对路径。
2. 所有"C:\\Users\\Junhao's Alienware\\food_recognition\\Database/name_value.db"这个为name_value.db在我的电脑中的路径，
因此您应该修改"C:\\Users\\Junhao's Alienware\\"这一部分为你存储food_recognition文件夹的绝对路径。
3. 所有"C:\\Users\\Junhao's Alienware\\food_recognition\\Food_picture"这个为Food_picture文件夹在我的电脑中的路径，
因此您应该修改"C:\\Users\\Junhao's Alienware\\"这一部分为你存储food_recognition文件夹的绝对路径。
4. 所有"C:\\Users\\Junhao's Alienware\\food_recognition\\Food_picture\\checkout_picture.png"这个为checkout_picture.png图片在我的电脑中的路径，
因此您应该修改"C:\\Users\\Junhao's Alienware\\"这一部分为你存储food_recognition文件夹的绝对路径。
5. Food_Reg_GUI_multi-revise1.ipynb和Merchant_database_OS.ipynb是最主要的两个文件，前者是结账系统，后者是卖家数据库录入系统。
这两个文件就忽略"注意"的1~4条，因为已经做了符合所有电脑的修改
6.作为演示的测试图片就在food_recognition的目录下，所以只用浏览到food_recognition这个文件夹就可以进行demo的演示
