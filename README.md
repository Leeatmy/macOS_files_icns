# macOS 自制 各种文件格式 简洁图标

## 初衷

> 先吐槽 ‘苹果的产品设计真的不错，图标设计咋这么烂呢。’

>「访达」在分栏模式下，各种格式的文件显示效果 ‘一坨遭’ 。本来那么小，图标上还要加上文字，美编咋想的，根本什么看不到。

- 几年前自制一些图标
- 一开始画了一些，发现，多么精美，没用，什么一缩小就是‘一坨遭’；而是，越简单越好，线条越简单，色彩越简单，在小字体下，显示效果越好。
- 经过使用发现不错，放到github上来备份。

![更美了吧](https://raw.githubusercontent.com/Leeatmy/macOS_files_icns/master/Screenshot/1.png?raw=true)


## 设计
> 去除 导致 ‘一坨遭’ 的原因 ‘文字+复杂图形’

> 转而利用 ‘颜色’ 和 ‘图形’ 来分类

> 在「访达」中开启`后缀`这样区分档案更加清晰 主观

> 去除 各种‘机器人’ ‘昆虫’ 图标

- 文字 txt rtf pdf 等等

最终选用‘绿色系’ 因由 ‘墨是由植物而生成’ ‘君子谦谦如玉’ ‘书中自有颜如玉’

- 多媒体档案 mp3 mp4 mov 等等

图形颜色皆受YouTube影响 使用‘梅花粉色系’

- 图片档案 jpg png 等等

‘梅花图形’ ‘天空蓝色系’

- 压缩档案 rar zip 7z 等等

‘包装箱’ ‘橘黄色系’

- 各种 Apple 内置软体

## 安装

- 除苹果macOS内置的App外的，IINA Keka DevonThinkPro 等等，都不需要关闭「SIP」直接找到相关的App，覆盖原图标，即可。

> 例如 `Keka.app`

```
Macintosh HD⁩ ▸ ⁨应用程序⁩ ▸ ⁨Keka.app⁩ ▸ ⁨Contents⁩ ▸ ⁨Resources⁩
```

- 苹果macOS内置的App，每次macOS更新都要做一遍，不过反正也要从安装「TotalFinder」，执行「Monolingual」删除无用语言档案，都已经习惯了。

#### 需要 暂时 关闭「SIP」
关机 同时按住`Command+R`从起
`终端机` 输入
```
csrutil disable
```

#### 复制图标到 对应的各个 App中

例如 `文本编辑.app` 复制位置
```
Macintosh HD⁩ ▸ ⁨应用程序⁩ ▸ ⁨文本编辑.app⁩ ▸ ⁨Contents⁩ ▸ ⁨Resources⁩
```


#### 安装 「TotalFinder」

#### 用「Monolingual」去除多余的语言档案

- 使用了这么年没出过错误 包括现在的 macOS 10.14 beta
- 实际使用`1.6.7`这个版本去除的最干净。
- 每次更新系统，只保留英文、中文、中文简体、中文繁体，这四个，其它的都删除，大概清理出去800M+。


#### 从新 激活「SIP」
关机 同时按住`Command+R`从起

`终端机` 输入
```
csrutil enable
```
