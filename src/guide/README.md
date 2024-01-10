---
title: 介绍
--- 

> 一直想做一个适用于尽可能多的需求场景的快速开发脚手架，参考[若依](https://doc.ruoyi.vip/)项目，实现了一套适合自己开发习惯的系统。

Fast Alden，中文名为“快安”，可理解为“快速安装”，主要目的让开发者注重专注业务，降低技术难度，从而节省人力成本，缩短项目周期，提高软件安全质量。

Fast Alden是一个前后端分离的完整系统，包含后台管理系统和前台业务系统。

- 后台管理系统后端使用Java 21 + SpringBoot 3 + Spring Security + Spring Data JPA技术组合，前端使用Vue3 + Vite + Element Plus + Tailwind CSS技术组合。

- 前台业务系统后端与后台系统使用了相同的技术栈，但前端针对不同的运行环境（如PC端网页、移动端网页、微信小程序、安卓等）提供了多个脚手架工程，每个前端工程都使用了不同的技术栈，大体包括Vue3、原生微信小程序、uni-app以及相关的工具库、UI库。

> 问：为什么没有上TypeScript？
>
> &nbsp;
>
> 答：在本系统的原型版本中使用了TypeScript进行前端开发，但作为个人开发者，如果每一个前端工程都使用ts，为保证每个工程的独立性，需要在每一个前端工程里都要声明一遍相同的实体类型，会导致工作量成倍增加，因此暂时抛弃了它。

#### 在线体验

- 快安官网：[http://falden.com](http://falden.com)
- 项目地址：[https://gitee.com/breezefaith/fast-alden-dev](https://gitee.com/breezefaith/fast-alden-dev)
- 演示地址：
    - 前台系统：
        - PC端：[http://demo.falden.conm](http://demo.falden.conm)
        - H5端：[http://h5.demo.falden.conm](http://h5.demo.falden.conm)
        - 微信小程序端：请使用微信扫描以下小程序进行体验

            ![](https://foruda.gitee.com/images/1688698896981315161/070caf77_1915710.jpeg)
        - uni-app版本：在PC端、H5端、微信小程序中均可体验，以下是PC端、H5端访问地址[http://uni.demo.falden.conm](http://uni.demo.falden.conm)
    - 后台系统：[http://admin.demo.falden.conm](http://admin.demo.falden.conm)

#### 系统需求

- JDK >= 21
- MySQL >= 5.7
- Maven >= 3.0
- Node >= 18
- Redis >= 3

#### 技术交流群

- 社区群需要邀请入群，关注公众号后点击`联系方式`加我，我可以拉你入群

![程序员偏安](https://open.weixin.qq.com/qr/code?username=zzcoder_life)