<!-- CSS 模拟选项卡容器，实现中英文版本切换 -->
<div class="tab-container">
  <input type="radio" name="tab" id="tab1" checked>
  <label for="tab1">中文</label>
  <input type="radio" name="tab" id="tab2">
  <label for="tab2">English</label>

  <!-- 中文内容 -->
  <div class="tab-content" id="content1">
<div align="center">
<h1>RWKV 会议的公开存档</h1>

[![中文版本](https://img.shields.io/badge/文档-中文版本-red)](README.zh-CN.md) [![English](https://img.shields.io/badge/Docs-English-blue)](README.md)</p>
</div>

这个仓库记录由 RWKV 基金会或 RWKV 社区组织的各种峰会，包括会议的 PPT、现场图片或视频、会议纪要等。


下面是一些常见的问题：

## 为什么缺少了一些峰会的内容？

出于隐私保护，我们不会存档任何**非公开**的内容。此仓库的任何内容（包括大会海报、演讲嘉宾的 PPT、现场图片等）均取得版权认证和演讲嘉宾的许可。

## 我可以为此仓库贡献内容吗？

出于版权纠纷和肖像授权等不确定性，此仓库暂时只接受内容纠错的 commit 和 pr。
  </div>

  <!-- 英文内容 -->
  <div class="tab-content" id="content2">
<div align="center">
<h1>Public RWKV Summit Archive</h1> 

[![中文版本](https://img.shields.io/badge/文档-中文版本-red)](README.zh-CN.md) [![English](https://img.shields.io/badge/Docs-English-blue)](README.md) </div>

## What does this GitHub repository document?

This repository records summits organized by the RWKV Foundation or the RWKV community, including conference PPTs, Live pictures or videos, conference proceedings, and more.

## Why are some summit content missing?

For privacy reasons, we do not archive any **non-public** content. Any content in this repository (including conference posters, speaker PPTs, images, etc.) is copyrighted and licensed by the speakers.

## Can I contribute to this repository?

Due to the uncertainty of copyright disputes and portrait licenses, this repository only accepts commits and prs for content corrections for the time being.

  </div>
</div>

<style>
.tab-container { position: relative; }
.tab-container input[type="radio"] { display: none; }
.tab-container label {
  display: inline-block;
  padding: 10px 20px;
  background: #fff;
  cursor: pointer;
  border-radius: 5px 5px 0 0;
}
.tab-container input:checked + label {
  background: #eee;
  border-bottom: 3px solid #0366d6;
}
.tab-content {
  display: none;
  padding: 20px;
}
#tab1:checked ~ #content1,
#tab2:checked ~ #content2 { display: block; }
</style>