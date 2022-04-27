# 深度定制主题修改方法
大部分内容更改可在_config.json中修改，如需要更换资源（如背景更新）可在指定路径下添加替换文件，并在_config.json中重新定位。

# 相关插件
使用插件前需要安装hexo-renderer-sass与hexo-renderer-scss
npm install hexo-renderer-sass --save
npm install hexo-renderer-scss --save
拥有此插件时hexo才能将scss文件转成目标css文件

# 更新关于部署到github之后css无法正常显示的问题
首先运行hexo g生成本地文件，并在hexo s中测试成功的情况下再将theme中的css文件全部覆盖到public的css中，再使用hexo d部署，此bug会在后期更新中修复



