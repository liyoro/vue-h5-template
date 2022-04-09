# vue-h5-template

基于 [vue-h5-template](https://github.com/sunniejs/vue-h5-template)，此框架变种于 [vue-element-admin](https://github.com/PanJiaChen/vue-element-admin/) 这个框架基本可以直接使用了，为适合自己的习惯，稍微做了修改。

## 环境

```
node v14.18.3 (npm v6.14.15)
```

## 代码总览

``` 
|-- public
	|-- data	// mock接口数据
|-- src
	|-- api	// 接口
	|-- assets	// 图片、字体、iconfont
    |-- components 	// 组件
    |-- config		// 全局配置文件
    |-- directive		// 指令
    |-- filters		// vue全局过滤器
    |-- layout		// 项目总体布局文件
    |-- plugins	// 主要是vant配置
    |-- router		// 项目路由配置
    |-- store		// 项目vuex配置
    |-- styles 	// css配置
    |-- utils 		// 工具类、请求
    |-- views		//
|-- main.js    // 全局配置
```

## iconfont

### 引入

下载的文件，放`assets`-`iconfont`目录下面

### 配置

在`main.js`里面配置

```
import "@/assets/iconfont/iconfont.css"
```

### 使用

xxx是图标名称

```
<i class='iconfont xxx' />
```


## 使用

[vant](https://youzan.github.io/vant-weapp/#/home)