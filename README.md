# 最简单的一个npm包，大小不到1k

### 使用
```javascript
    let Mytag= require('mytag')
	// 或es6引用 import Mytag from 'mytag'

    Mytag()  // 输出 hello , myTag package !
```

### 说明
    可以做探针使用，查看是否成功安装npm等工具，或是工具是否能够正常使用
	新手发布包的参考，(源码见github) 发布命令
		npm 镜像源切换到最原始地址 https://registry.npmjs.org 
		npm login
		npm version <update_type>  （patch   minor   major三个参数）
		npm publish
		
		
	