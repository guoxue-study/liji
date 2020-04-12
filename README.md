# 《礼记》胶片版

[![Netlify Status](https://api.netlify.com/api/v1/badges/d04c0d0f-965e-4bc6-95cd-bf78bca2fba7/deploy-status)](https://app.netlify.com/sites/shi-ji/deploys)

TLDR: [https://liji.qiaopang.com](https://liji.qiaopang.com)

制作《礼记》胶片版的原因见：[《资治通鉴》胶片版](https://github.com/tyrchen/tongjian)。

制作出来的 slides 截图如下：

![](assets/snapshots/snapshot1.jpg)

![](assets/snapshots/snapshot2.jpg)

![](assets/snapshots/snapshot3.jpg)


## 运行

本地需要有 nodejs 运行时，然后安装依赖：

```bash
make init
make dep
```

之后可以 `make run` 运行 http 服务器。服务器运行完毕后，可以在浏览器中打开 `http://localhost:8080/` 查阅。

如果要批量生成 html / pdf 版本，可以 `make build` 或者 `make build-pdf`。

## 语音素材的生成

《资治通鉴》胶片版内的所有语音素材均使用 __科大讯飞开放平台__ 的在线语音合成技术提供。目前使用的发音人为 __讯飞小媛__。感谢科大讯飞的开放平台，我得以自动化生成所有语音素材。由于目前我使用的免费版有日 API 访问上限，所以所有内容生成语音素材尚需时日。

如果你想生成自己的语音素材，可参考：[语音素材的生成](https://github.com/tyrchen/tongjian#%E8%AF%AD%E9%9F%B3%E7%B4%A0%E6%9D%90%E7%9A%84%E7%94%9F%E6%88%90)

## 如何编辑及添加素材

所有的素材都放在 `slides/assets` 下，按卷命名。见：[如何编辑及添加素材](https://github.com/tyrchen/tongjian#%E5%A6%82%E4%BD%95%E7%BC%96%E8%BE%91%E5%8F%8A%E6%B7%BB%E5%8A%A0%E7%B4%A0%E6%9D%90)


## 贡献

目前的版本是自动生成的，还很粗糙，我自己也在边读边整理。如果你遇到任何问题，欢迎提 issue，当然跟欢迎发 pull request。


## 鸣谢

### 科大讯飞开放平台

tts 的质量相当上乘，在此感谢！
