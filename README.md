extend_fileuploader
===================

 extend fileuploader js 

扩展<a href='https://github.com/Valums-File-Uploader/file-uploader'>file-uploader</a> 可以设置手动上传

引用:
```js
	<javascript type='text/javascript' src='extend_fileuploader.js '></javascript>
```

使用exemple : 
 ```js
    file_upload = new qq.FileUploader{
        ...
        autoUpload : false  // 禁止自动上传,默认true自动上传
    }
      
    //调用上传
    $("#button_id").click(function(){
        file_upload.submitUpload()
    })
   ```