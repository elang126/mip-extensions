# mip-share

提供页面内分享按钮功能，默认分享当前网址：

标题|内容
----|----
类型|通用
支持布局|responsive,fixed-height,fill,container,fixed
所需脚本|https://mipcache.bdstatic.com/static/v1.1/mip-share.js


## 示例

```html
<!-- 通用分享 -->
<div class="mip-share-container">
    <mip-share 
        layout="fixed-height"
        height="158">
    </mip-share>
</div>

<!-- 通用分享 -->
<div class="mip-share-container">
    <mip-share 
        layout="fixed"
        width="200"
        height="158">
    </mip-share>
</div>

<!-- 通用分享 -->
<div class="mip-share-container">
    <mip-share 
        layout="responsive"
        width="414"
        height="158">
    </mip-share>
</div>
```

## 属性

### url

说明：分享出去的网址  
必选项：是  
类型：字符串  
取值范围：URL

### title

说明：分享出去的标题  
必选项：否  
类型：字符串

### content

说明：分享出去的内容  
必选项：否  
类型：字符串

### icon

说明：分享出去的图标  
必选项：否  
类型：字符串  
取值范围：URL
