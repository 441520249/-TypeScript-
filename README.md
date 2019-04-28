# -TypeScript-

## 安装TypeScript出现报错
输入以下代码查看当前版本
```
node -v
```
输入命令 安装npm，g代表全局安装
```
npm install npm -g
```
等他跑完，输入以下，输入当前版本，5.6.0 则说明安装成功
```
npm -v
```
问题来了，现在安装typescript，官网的意思很简单
```
npm -g install typescript 
```
输入以上代码即可。
## 如果报错，就按照一下步骤安装
```
npm config set registry https://registry.npm.taobao.org
npm config set disturl https://npm.taobao.org/dist
npm -g install typescript
```
依次输入以上代码即可，输入，这次不报错了。
然后
```
tsc -v
```
出现当前版本，安装完成
