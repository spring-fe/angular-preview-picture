# angular-preview-picture
图片预览组件

# 使用说明

```js
angular.module('App').directive('replyDetailDirective',['PreviewPictureFactory', function(PreviewPictureFactory){
    PreviewPictureFactory.open(attachments, index, options);
}]
```
## PreviewPictureFactory.open(images, index, options)参数说明

1.images:图片地址数组

2.从第index张图片开始(从0开始）

3.options:

对象属性:

(1)preload{Number}：预先加载图片的张数，默认1。

(2)downloadBtn{Boolean}：是否显示下载原图按钮，默认true。

(3)contextMenu{Boolean}:右键单击是否显示弹框，默认true。

(4)loop{Boolean}:是否循环显示图片，默认false。

## demo
https://spring-fe.github.io/angular-preview-picture/


