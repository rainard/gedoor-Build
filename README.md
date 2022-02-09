## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.020919.apk](https://github.com/rainard/gedoor-Build/releases/download/legado-3.22.020919/legado-3.22.020919.apk) 上次构建时间:2022-02-09 20:33:47
<!--start-->
> **2022/02/09**
> 
> * 校验失效分组具体到搜索发现目录正文 by Xwite
> * txt文件初次解析目录不选择禁用的正则
> * txt单章字数超102400均分txt，添加开关 by Xwite
> * 修复tts被回收后无法继续朗读的bug,重新初始化tts
> * webDav备份支持自定义文件夹
> * 其它一些优化
<!--end-->
  
1. fork到你自己的仓库
2. 去你自己的仓库,点一下右上角star就会自动开始构建,已经star的点unstar,再点一下star就会进行新的构建,你的[Actions](https://github.com/10bits/gedoor-Build/actions)列表会有显示的
3. 每次构建完,apk会自动打包为`legado.apk.zip
`,去你自己的[Actions](https://github.com/10bits/gedoor-Build/actions)列表里找
4. 每次构建大概十几分钟,请耐心等待

## 如果你安装apk遇到以下问题

1. `安装失败(-102)`问题,给release apk增加了签名,已解决
2. `与已安装应用签名不同`问题,请卸载重新安装,已解决
3. `与已安装程序共存`问题,通过修改`applicationIdSuffix='.releaseA'`,已解决,不用卸载重装了
> 使用app过程中遇到问题,请到这里解决[gedoor/legado](https://github.com/gedoor/legado/issues)

