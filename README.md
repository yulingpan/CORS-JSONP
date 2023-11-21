# CORS-JSONP 使用方法

1. 下载代码 
    `git clone ...`
2. 进入 qq-com 运行 server.js
    `cd CORS-JSONP/qq-com; node server.js 8888`
3. 进入 frank-com 运行 server.js
    `cd CORS-JSONP/frank-com; node server.js 9999`
4. 设置 hosts
    ```
    127.0.0.1 qq.com
    127.0.0.1 frank.com
    ```
5. 打开两个页面 qq.com:8888/index.html 和 frank.com:9999/index.html
6. 记得做完之后，删掉 hosts 里的两行，否则 qq.com 无法正常访问！
