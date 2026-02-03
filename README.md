# 说明

该仓库用于在 build.deepin.org 构建linyaps

## 项目

每日构建

https://build.deepin.com/project/show/linglong:CI:latest

最新release构建

https://build.deepin.com/project/show/linglong:CI:release

## 仓库

仓库的具体使用见

https://github.com/OpenAtom-Linyaps/linyaps/issues/1070

## 分支说明

### obs_latest

用于构建适用于deepin发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps master 分支

### obs_latest_uos

用于构建适用于uos发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps develop/uos 分支

### obs_latest_nopatch

用于构建适用于其它发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps master 分支，删除 patchs 目录并关闭单元测试

### obs_release

代码来自 https://github.com/deepin-community/linyaps 最新的 release/xx 分支

### obs_release_uos

代码来自 https://github.com/deepin-community/linyaps 最新的 release/uos/xx 分支

### obs_release_nopatch

代码来自 https://github.com/deepin-community/linyaps 最新的 release/xx 分支，删除 patchs 目录并关闭单元测试
