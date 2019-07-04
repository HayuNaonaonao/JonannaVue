node下载
https://www.cnblogs.com/liangsongbai/p/5506073.html
安装node.js
https://www.liaoxuefeng.com/wiki/1022910821149312/1023025597810528
建project
https://www.jianshu.com/p/769a46d16b0c


步骤
1.前往nodejs官网下载安装软件，地址：https://nodejs.org/en/
安装完成验证run cmd 输入
node -v
npm -v
npm
{可以参考这个链接：https://www.liaoxuefeng.com/wiki/1022910821149312/1023025597810528}

2.run cmd 安装淘宝镜像
前往淘宝镜像官网 http://npm.taobao.org/，可查看安装cnpm包的命令
npm install -g cnpm --registry=https://registry.npm.taobao.org

3.安装vue
run cmd 输入：
cnpm install vue
cnpm install --global vue-cli

安装完成验证run cmd 输入 
vue -V

4.新建项目vue init webpack vue-project
vue build standalone  choose
vue-router			  Yes
ESLint    			  no
unit tests			  no
e2e					  no
NPM       			  choose


完成后run cmd验证
// 进入项目
$ cd vue-project
// 安装依赖
$ cnpm install
// 测试环境是否搭建成功
$ cnpm run dev

(可以参考这个链接进行安装新建项目：https://www.jianshu.com/p/769a46d16b0c)
#################################################################################
	这里需要进行一些配置，默认回车即可											#
This will install Vue 2.x version of the template.								#
																				#			
For Vue 1.x use: vue init webpack#1.0 vue-projec								#
																				#
? Project name joannahuvue                      								#
? Project description Joannahu's Vue	          								#
? Author Joannahu@outlook.com        											#
																				#
? Vue build standalone                          								#
? Use ESLint to lint your code? No             									#
? Pick an ESLint preset Standard												#
? Setup unit tests with Karma + Mocha? no	      								#
? Setup e2e tests with Nightwatch? no	          								#
																				#
   vue-cli · Generated "my-project".            								#
																				#
   To get started:																#
																				#
     cd vue-project                             								#
     npm install																#
     npm run dev                                								#
																				#
   Documentation can be found at https://vuejs-templates.github.io/webpack		#
################################################################################