# 说明

该仓库用于在 build.deepin.com 构建 linyaps

## 项目

latest 每日构建

https://build.deepin.com/project/show/linglong:CI:latest

最新 release 构建

https://build.deepin.com/project/show/linglong:CI:release

## 仓库

仓库的具体使用见 https://github.com/OpenAtom-Linyaps/linyaps/issues/1070

## 分支说明

分为 latest 和 release，latest 会每天自动更新，release 需要在 linyaps 发版时手动触发，触发时手动输入上游的 release 分支

### obs_latest

用于构建非deepin/uos发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps master 分支，删除 patchs 目录并关闭单元测试

### obs_latest_uos20

用于构建适用于uos20发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps master 分支，关闭单元测试

### obs_latest_deepin

用于构建适用于deepin发行版的linyaps

代码来自 https://github.com/OpenAtom-Linyaps/linyaps master 分支

rpm和debian 目录来自 https://github.com/deepin-community/linyaps master 分支

### obs_release

代码来自 https://github.com/deepin-community/linyaps 最新的 release/xx 分支，删除 patchs 目录并关闭单元测试

### obs_release_uos20

代码来自 https://github.com/deepin-community/linyaps 最新的 release/xx 分支，关闭单元测试

### obs_release_deepin

代码来自 https://github.com/deepin-community/linyaps 最新的 release/xx 分支
