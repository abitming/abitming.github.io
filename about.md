---
layout: page
title: 简介 | Eden
class : read-me
comments: true
menu: About
---
{% assign current_year = site.time | date: '%Y' %}

## ABitMing

目前就职于 新浪 ，运维工程师/运维开发工程师。主要研究方向 Docker / Kubernetes 相关

曾就职于 58同城 , 运维工程师。主要负责存储(MFS)及大数据(ES)相关

标签： `Linux` `Golang` `Python` `Docker` `Kubernetes`

## 联系

- QQ: 1328173503
- Tel: ******
- 邮箱：edenabitming@gmail.com
- 微博: 冒了个小小泡
- 主页：http://abitming.github.io

## keywords
<div class="btn-inline">
{% for keyword in site.skill_keywords %} <button class="btn btn-outline" type="button">{{ keyword }}</button> {% endfor %}
</div>

## 爱好
<div class="btn-inline">
{% for keyword in site.hobby %} <button class="btn btn-outline" type="button">{{ keyword }}</button>{% endfor %}
</div>
