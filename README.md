# Bili-Blocked

>   眼不见心不烦，根据关键信息屏蔽哔哩哔哩上某些视频的信息

-   原仓库，[ZanwingMak/bilibili-out-of-sight-out-of-mind](https://github.com/ZanwingMak/bilibili-out-of-sight-out-of-mind.git)

## 需求

-   修复原仓库实现的视频屏蔽功能，修改屏蔽的方式为 **追加到浏览器右键**
    
    -   移动到某个视频，右键屏蔽用户（包含该视频和该用户所有视频）、屏蔽视频（仅该视频，不屏蔽用户）
    -   移动到某个名字
        -   屏蔽这个 up
        -   （评论区）屏蔽这个评论发起人
    
    -   指定屏蔽理由，或者 default
    -   遇到被屏蔽的内容，当鼠标移过去时，显示用户、屏蔽理由
-   官方的黑名单有上限，这边手动添加用户黑名单
    -   弹幕：直接删除；
    -   视频：按原仓库形式替换封面和文本；
    -   评论区：替换文本；
-   关于关键词相关存储
    -   需要 server 服务端登录？
    -   插件用户数据区自己存储？
-   相关页面（适配新版？）
    -   主页
    -   搜索页
    -   单个视频的播放页，包括视频播放完成后的推荐视频

## 预期参考

![](https://tuchuang.laji.blog/imgs/2020/08/211821308a0cafd6.png)

---

![](https://tuchuang.laji.blog/imgs/2020/08/1d13c6ae5c040461.png)

## 预计效果

![](https://tuchuang.laji.blog/imgs/2020/08/c88071e4382d0388.png)

---

![](https://tuchuang.laji.blog/imgs/2020/08/a0303b7c587d8c82.png)

---

![](https://tuchuang.laji.blog/imgs/2020/08/456e2e5533b0414d.png)

---

![](https://tuchuang.laji.blog/imgs/2020/08/fa4f7cb8416914a0.png)
