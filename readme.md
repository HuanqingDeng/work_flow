### 前端工作流

- babel js预编译器 将js的未来，现在使用
es6以前，es6以后，使用最新的js语法来编写，运行的代码可以根据需求编译成相应的版本

babel 编译js
source_code .babel-cli targets(运行平台)
presets(预处理集)
babel的预处理只是语法糖，class没有，把es5里没有的es6的语法，实现一遍，最基本的const等等，在babel-core里面
还有一些没有的Object.assign(),Promise,async
plugins


- npm node包管理器
 npm run dev /npm install
 项目构建的基本流程 
- postcss
 解决前缀问题，使用css变量
- stylus/scss/less