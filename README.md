
# 说明
- 本项目完全基于(wxappUnpacker) 改进的。


# 安装依赖
1. `npm install uglify-es`
2. `npm install esprima`
3. `npm install css-tree`
4. `npm install cssbeautify`
5. `npm install vm2`
6. `npm install uglify-es`
7. `npm install js-beautify`
8. `npm install escodegen`
9. `npm install cheerio`

# 分包功能
当检测到 wxapkg 为子包时, 添加-s 参数指定主包源码路径即可自动将子包的 wxss,wxml,js 解析到主包的对应位置下. 完整流程大致如下: 
1. 获取主包和若干子包
2. 解包主包 `node wuWxapkg.js D:\mini\主包名.wxapkg`
3. 解包子包 `node wuWxapkg.js -s=/mini/主包名 D://mini/子包名.wxapkg`

# 使用说明
1. cmd ——> 项目根目录
2. 执行各种命令
