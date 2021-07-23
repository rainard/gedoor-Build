## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.21.072310.apk](https://github.com/rainard/gedoor-Build/releases/download/legado-3.21.072310/legado-3.21.072310.apk) 上次构建时间:2021-07-23 14:27:28
<!--start-->
> **2021/07/22**
> 1. 非关键规则添加try防止报错中断解析
> 2. 添加获取封面的api
> 3. 获取正文api使用替换规则
> 4. 添加一个ronet版本,网络访问使用Chromium内核
> 5. web书架增加【最近一次更新书籍信息的时间】
> 6. 采用Flow替换LiveData,优化资源使用
> 7. 统一网络一键导入路径legado://import/{path}?src={url}
> * path: bookSource,rssSource,replaceRule,textTocRule,httpTTS,theme,readConfig
> * 添加了txt小说规则,在线朗读引擎,主题,排版 的一键导入支持,老url依然可用
> 8. 替换规则管理添加置顶所选和置底所选
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

