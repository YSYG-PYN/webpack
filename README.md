### 1. webpack打包
1.	index.js: webpack入口起点文件
2.	运行指令
   	- 开发环境：webpack ./src/index.js -o ./build/built.js --mode=development
     	-  webpack会以 ./src/index.js 为入口文件开始打包，打包后输入到 ./build/built.js
     	-  整体打包环境，是开发环境
   	- 生产环境：webpack ./src/index.js -o ./build/built.js --mode=production
     	-  webpack会以 ./src/index.js 为入口文件开始打包，打包后输入到 ./build/built.js
     	-  整体打包环境，是生产环境  
3.	结论
   	- webpack能处理js/json资源. 不能处理css/img等其他资源
   	- 生产环境和开发环境将ES6模块化编译成浏览器能识别的模块化
   	- 生产环境比开发环境多一个将js代码压缩步骤		
