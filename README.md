# UploadFiles

Use when you want to upload an image or file and get url

## Use in Controller
* Add use
use Satoritech44\UploadFiles\UploadFiles;

* inside method
  ```php
  $file=$request->file('img');
  if (isset($file)){
  $url=UploadFiles::storeFile($file,'id','path','projectName');
  }
  ```


