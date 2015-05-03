1.INETNT几种有关Activit的启动方式
FLAG_ACTIVITY_BROUGHT_TO_FRONT 将ACTIVITY带到最前面
FLAG_ACTIVITY_CLEAR_TOP 清除顶部
FLAG_ACTIVITY_CLAER_WHEN_TASK_RESET 重置任务时清除
FLAG_ACTIVITY_EXCLUDE_FROM_RECENTS  排除最近的
FLAG_ACTIVITY_MULTIPLE_TASK 多任务启动
FLAG_ACTIVITY_NEW_TASK 新任务启动
2.ACTIVITY和Task的启动模式有哪些？各种的含义
standard、singleTop、singleTask和singleInstance
3.通过Intent传递一些二进制数据的方法有哪些？
1》使用Serializable接口实现序列化
2》实现Parcelable接口，Bitmap就实现了
4. 能说下Android应用的入口点吗?
真正的Android入口点是application的main
5. Android都有哪些XML解析器，都熟练掌握吗?
XMLPull、Sax、DOM
6.SQLite支持事务吗？添加删除如何提高性能？
SQLite是轻量级的数据库，比MySQL还小，支持SQL语句查询，
提高性能可以考虑通过原始经过优化的SQL查询语句方式处理
1.activity的生命周期
onCreate、onStart、OnResume、onPause、onEnd、onDestroy
2.android的布局管理器
LinearLayout、TableLayout、FrameLayout、RelativeLayout、AbsLayout
3.android的数据存储
SharedPreference、文件、SQLite数据库、Content Provider、网络存储
4.Android 动画有哪几种？描述一下
两种。 Tween动画和Frame动画。 Tween动画主要是透明度、尺寸伸缩、旋转、位移等效果。

5.Handler的运行机制
先进先出
将线程放进去的队列
postDelayed（线程，多少毫秒家务 ）将信息添加到消息队列中
handler.post（线程） 马上加入到消息队列
removeCallbacks结束handler线程
消息队列
在线程中handler的obtainMessage得到消息对象
Message 
i=i+10;
msg=handler.obtainMessage();
msg.arg1=i;

6.Android如何实现刷新
通过View的invalidate()方法
7.android中的动画有几种？
两种。Tween和frame
8.HashMap可以保存重复的数据 、HashSet不可以存放重复的数据、HashTable存放的数据键值都不能为空

