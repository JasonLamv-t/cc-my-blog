---
title: A preliminary study on website Automation Test
date: 2021-11-05 11:58:36
tags:
---

# Web 自动化测试

## Before All

### 为什么需要自动化测试

快速迭代过程中经常有代码的重构修改，需要不断回归测试，没有成建制的测试团队和测试环节，手工测试无法QA，同时需要耗费大量时间和精力。

### 用什么

- Selenium：时间最长、用的人最多，多语言、平台、浏览器支持
- Puppeteer：免费开源、JS，headless
- Cypress：部分收费、JS，Chromium / firefox support

倾向于后两个

## 实践

### Cypress

#### Refers：

- [Why Cypress? | Cypress Documentation](https://docs.cypress.io/)

#### Install

Install the cypress as a dev dependence via npm or yarn to the front end project.
Then add the script to `package.json`: `test: $(npm bin)/cypress open`.
Actually it is up to you, because my config is `test: yarn cypress open`. Please check the documentation for more details.

#### 1. Try some simple api

Apis record and their functions:

```

```

