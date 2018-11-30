golang在国内安装依赖包时会各种被墙, glide包管理的mirrors.yaml文件支持映射到对应的github上省了不少事情, 这里记录了一些常用的
# 使用方式
替换或新建掉 `~/.glide/mirrors.yaml` 文件即可

更多参考 https://glide.readthedocs.io/en/latest/commands/#glide-mirror

## 觉得更好的方案 使用二级代理
参考 https://github.com/cyfdecyf/cow
