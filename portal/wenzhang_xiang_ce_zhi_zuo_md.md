# 文章相册制作

```html
<php>$smeta=json_decode($vo['smeta'], true);</php>
<div id="imgs" class="imgs">
    <foreach name="smeta['photo']" item="vo"> <
        <img src="{:sp_get_asset_upload_path($vo['url'])}" /> 
    </foreach>
</div>


```