# live2d_blog

最近打算自己搭个博客，这个live2d看板，参考了

https://github.com/galnetwen/Live2D 

https://github.com/xb2016/poster-girl-l2d-2233

的源码，先调整好了，到时候直接用进去。
1. 网上有大神用php写了切换模型、贴图的接口、插件，奈何洒家玩不转，所以自己用js写了一下切换模型，切换贴图的方法。 *缺点是每套贴图需要对应新建一个model.json* 。新加入的模型信息需写入model_master.json
2. 参考[猫与向日葵](https://imjad.cn/archives/lab/add-dynamic-poster-girl-with-live2d-to-your-blog-01)大佬提供的拆包方法，从药水制作师游戏中给pio扒了80套衣服。
3. 加了两个鼠标点击特效：点击爆炸特效，点击出现文字特效。
4. 貌似由于chrome不支持本地ajax请求，因此直接点index.html看不到模型，请将项目导入工程中运行

# 版权说明
本项目仅供学习和交流使用，禁止用于商业用途。 本插件用到的模型pio、tia版权为《药水制作师》官方所有，2233为[哔哩哔哩](https://www.bilibili.com/)所有 。 原项目使用了 GPL v2 开源协议，根据 GPL v2.0 许可证开源


