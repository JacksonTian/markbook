# Markbook
写作《深入浅出Node.js》的过程中用到的一些脚本，用于将文章切分成小章节。这里封装成模块工具，使得可以更便利地生成电子书。

## Feature

- 自动根据标题生成索引，无需在写作时拆分，令你写作更流畅

## Installation

```bash
$ npm install markbook -g
```

## 约定
源码目录：

```
sources
├── 01_Introduction.md // 第1章，按{dd}_{章节名}.md
├── 02_Module.md // 第2章，按{dd}_{章节名}.md
├── figures // 如果有图片，请放在此目录下
└── README.md // 用来做说明页
```

## Usage

```bash
$ # build it
$ markbook sourcesDir outputDir --book "Your book name"
$ # serve it
$ npm install anywhere -g # optional
$ cd outputDir
$ anywhere
```

## License
The MIT License
