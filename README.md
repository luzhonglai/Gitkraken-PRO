# crack-gitkraken

#### 介绍

破解版 gitkraken 版本：7.5.5

安装包下载：链接：https://pan.baidu.com/s/1lXPEH3F34Qy_FL9pmTyoRQ?pwd=xhhf 
提取码：xhhf

破解教程

## 环境要求

- `Node.js` v12 LTS 及以上
- `yarn`
- `GitKraken v6.5.2 to v7.5.5`

## 开始破解

- `git clone https://gitee.com/pan13640612207/GitKraken.git`
- `cd GitCracken/`
- `yarn install`
- `yarn build`
- `node dist/bin/gitcracken.js patcher --asar C:/Users/{用户名}/AppData/Local/gitkraken/app-7.5.5/resources/app.asar`

## 屏蔽更新（重要！）

Add this content to your `hosts` file:
在你的 host 文件添加以下：
推荐下载 switchhost 这个软件修改

```text
127.0.0.1 release.gitkraken.com
```
