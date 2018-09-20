# www

[![GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Build Status](https://travis-ci.org/mtdhb/www.svg?branch=master)](https://travis-ci.org/mtdhb/www)

https://mtdhb.org 网页端

关闭网站之前最后一个版本看这里 [releases](https://github.com/mtdhb/www/releases)

## 开发

环境要求 Node.js 9.x

```bash
npm i
npm run dev
```

## 发布

```bash
npm run build
```

将生成的 `build/` 目录提交到网站根目录

并参考 `public/_headers`、`public/_redirects` 在你的静态服务器上做相关配置 [FAQ](https://github.com/mtdhb/mtdhb/issues/135)
