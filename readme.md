**所有文章可在issue中访问，方便回复及讨论！**

## 概述
Arale是支付宝开发的一套基础类库，提供了一整套前端模块架构，基于CMD规范，所有模块均是以sea.js的标准进行开发。其开发过程借鉴了优秀的开源类库如jQuery, underscore等的经验，并融合发展，最后建立了一套自己的开发机制。

## 结构
```
Arale
  |--基础设施
  |    |-- Base
  |    |-- Class
  |    |-- Events
  |    `-- Widget
  |--工具
  |    |-- Cookie
  |    |-- Detector
  |    |-- Dnd
  |    |-- Easing
  |    |-- Iframe-Shim
  |    |-- Messenger
  |    |-- Name-Storage
  |    |-- Position
  |    |-- Qrcode
  |    |-- Sticky
  |    |-- Templatable
  |    `-- Upload
  `--UI组件
       |-- Autocomplete
       |-- Calendar
       |-- Dialog
       |-- Overlay
       |-- Popup
       |-- Switchable
       |-- Select
       |-- Tip
       `-- Validator
```

## 这是什么项目
本项目的主题即是Arale类库的源码分析。本人也是边学边记录，把自己的理解写下来，在全部写完后，将会对内容进行一次整理。为了方便与各位进行交流，除本篇外，所有的源码分析文章会采用和我的博客一样的存放方式——放在项目的issue中，便于读者即时回复和交流。为了便于查找，本系列的目录如下，可点击链接前往具体内容。

## 目录
01. [Class](https://github.com/classicemi/araledoc/issues/1)