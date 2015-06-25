# langdifeng
#这是一个webapp项目
## Install
This project is a `gulp-webapp`, it depends `bower` and `gulp`. So we should first install them in **global**.
这是一个‘gulp-webapp’项目，它依赖bower和gulp,所以我们先要全局装好gulp和bower

```shell
$ sudo npm i -d -g bower
$ sudo npm i -d -g gulp
```

And then in `langdifeng` directory, install package from `package.json` and `bower.json`,so just run below command:
然后在langdifeng这个项目目录中，安装package.json和bower.json依赖:

```shell
$ npm i
$ bower i
```

如果上面npm i 运行失败，有可能是因为网被墙了，可以在本地机器上装一个淘宝镜像npm：

```shell
$ npm install -g cnpm --registry=https://registry.npm.taobao.org
```
从 registry.npm.taobao.org 安装所有模块. 当安装的时候发现安装的模块还没有同步过来, 淘宝 NPM 会自动在后台进行同步, 并且会让你从官方 NPM registry.npmjs.org 进行安装. 下次你再安装这个模块的时候, 就会直接从 淘宝 NPM 安装了

```shell
$ cnpm install [name]
```
##Set up

**devlopment:** just run `gulp` command

```shell
$ gulp serve
```

**build for production:** just run `gulp build` command

```shell
$ gulp build
```
