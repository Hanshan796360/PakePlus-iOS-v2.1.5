# 小鹿出行 Android 应用

这是一个基于WebView的小鹿出行Android应用，使用HTML、CSS和JavaScript开发。

## 项目结构

```
deer-app/
├── app/src/main/
│   ├── assets/
│   │   ├── index.html      # 主页面
│   │   └── edit.html       # 编辑页面
│   ├── java/com/deer/taxi/
│   │   └── MainActivity.java  # 主活动
│   ├── res/layout/
│   │   └── activity_main.xml  # 布局文件
│   └── AndroidManifest.xml     # 应用清单
└── build.gradle            # 构建配置
```

## 功能

- 显示行程信息
- 编辑行程数据
- 紧急求助功能
- 联系乘客功能

## 如何使用

1. 将项目导入Android Studio
2. 构建并运行应用
3. 点击编辑按钮修改行程信息
4. 返回主页面查看更新后的信息

## 注意事项

- 这是一个模拟应用，不连接真实的服务器
- 所有数据存储在本地
- 仅用于演示目的