title: This is my first article
date: 2015-09-23 12:30:03
tags: tech - web
comments: true
categories: tech
---
{% blockquote @zicongxie http://zicongxie.github.io %}
NEW:Mr.xi has a visite for American.http://zicongxie.github.io
{% endblockquote %}
最近写的文章收到许多朋友的反馈，感谢大家的支持和建议，让我对坚持写博客充满热情，一个月一篇文章确实有点少，所以以后尽力多做分享，做好的分享，希望能对朋友们有用。

{% codeblock lang:javascript %}
var bookStoreApp = angular.module('bookStoreApp', [
    'ngRoute', 'ngAnimate', 'bookStoreCtrls', 'bookStoreFilters',
    'bookStoreServices', 'bookStoreDirectives'
]);

bookStoreApp.config(function($routeProvider) {
    $routeProvider.when('/hello', {
        templateUrl: 'tpls/hello.html',
        controller: 'HelloCtrl'
    }).when('/list',{
    	templateUrl:'tpls/bookList.html',
    	controller:'BookListCtrl'
    }).otherwise({
        redirectTo: '/hello'
    })
});

{% endcodeblock %}

　　到新公司的这段时间学到了很多新东西，有好多东西需要去总结去探索，不过事情得一件一件来，今天咱们先从Node开始。注：以后出现的Node即node.js。

{% img [blog-img] /images/123.jpg [200px] [200px] [title text [alt text]] %}

先搞点前戏热热场 - 为什么写这篇文章：
{% link link http://zicongxie.github.io [external] [title] %}

　　1.前段时间单位有新项目启动，服务端要做的工作不多也不算麻烦，就是处理一些中间层的服务，而且我们团队里面个个都会JavaScript，领导就决定试试服务器端的JavaScript，结果本人有幸被派去研究了几天Node，怀着鸡冻的心情开始了node.js的篇章，这篇文章也就是为这几天研究的总结。

　　2.一个JavaScript工程师如果没听过node.js那么我想你是不是错过了什么，每个优秀的前端工程师都有必要去了解后台处理流程，那么如果又能从JavaScript出发，岂不是一件很美妙的事么。

　　3.互联网的火热使得JavaScrip

