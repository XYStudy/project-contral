# project-contral
项目整体把控

对于项目的把控
1.确定node版本
2.封装http库
3.封装el-empty 缺省页组件
4.环境地址env
5.确定表格通用样式，搜索框通用样式（label-width 80px 120px, 搜索框220px）
6.所有的表单提交按钮，都要加上loading ，防止重复提交


uniapp , dev-bar 设置title的fontsize大小可以到源码中设置
uniapp修改uni组件样式，如果组件在子组件中使用（h5就在子组件修改该Uni样式， 小程序在父组件修改该组件样式）
uniapp中修改input 的placeholder样式，使用placeholder-class添加类名，因为<style scoped>中的scoped不生效，在该页面重新写个<style>.placeholder-class{}</style>
修改某一页的背景样色<style>page{background: red}</style>不能要scoped

1.npm install nvm -g
2.命令行运行：nvm root 显示出nvm的安装目录
打开nvm文件夹下的settings.txt文件，在最后添加以下代码：
node_mirror: https://npm.taobao.org/mirrors/node/
npm_mirror: https://npm.taobao.org/mirrors/npm
3.nvm install 版本号
4.nvm use 版本号  使用该版本号node

nvm ls 查看已有node版本
