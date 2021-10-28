# 剪贴板过滤器

## 关于模块  
通过正则过滤APP写入剪贴板的内容，只过滤写入，防止各种口令、奇奇怪怪的字符串强x剪贴板。目前只支持有XSharedPreferences的xposed框架，比如lsposed。

内置一些规则，可以根据需要添加其他。作用域是被勾选的app，例如浏览器。
### v1.6
Xposed在获取不到SharedPreferences时尝试使用ContentProvider。调整hook位置。
### v1.5
更新使用提示，修复未勾选模块时导致的闪退。  
目前模块只支持有XSharedPreferences的xposed框架，比如lsposed
### v1.4
刷新版本号，顺便调整了一下ui，改了点逻辑
### v1.3
不再需要存储权限，写好规则保存正常使用即可，如果实在不知道怎么写，可以上酷安问[今天内存降价了吗](http://www.coolapk.com/u/855305)

开源: [ClipboardFilter](https://github.com/Thiasap/ClipboardFilter)

## 下载
[Release](https://github.com/Xposed-Modules-Repo/com.bit747.clipboardfilter/releases)
