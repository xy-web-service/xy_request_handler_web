<!--
 * @Author: 余洋 yuyangit.0515@qq.com
 * @Date: 2024-10-18 13:02:22
 * @LastEditors: 余洋 yuyangit.0515@qq.com
 * @LastEditTime: 2024-10-23 20:52:22
 * @FilePath: /xy_request_handler_web/readme/README.en.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# xy_request_handler_web

| [简体中文](../README.md)         | [繁體中文](./README.zh-hant.md)        |                      [English](./README.en.md)          |
| ----------- | -------------|---------------------------------------|

## Description

The web request base class based on xy_request_handler_base encapsulates common functions for easy and rapid development.

## Source Code Repositories

| [Github](https://github.com/xy-web-service/xy_request_handler_web.git)         | [Gitee](https://gitee.com/xy-opensource/xy_request_handler_web.git)        |                      [GitCode](https://gitcode.com/xy-opensource/xy_request_handler_web.git)          |
| ----------- | -------------|---------------------------------------|

## Installation

```bash
# bash
pip install xy_request_handler_web
```

## How to use

> For details, please see [Demoes.py](./samples/xy_web_server_demo/source/Runner/RequestHandlerDemo/Demoes.py)
```python
# Demoes.py

from xy_request_handler_web.Web import Web

class Demo(Web):

    def get(self):
        self.write("Hello, xy_request_handler_web !")

```

Run [Sample Project](../samples/xy_web_server_demo)

> For detailed usage of the sample project, please go to the following repository <b style="color: blue">xy_web_server.git</b>

| [Github](https://github.com/xy-web-service/xy_web_server.git)         | [Gitee](https://gitee.com/xy-opensource/xy_web_server.git)        |                      [GitCode](https://gitcode.com/xy-opensource/xy_web_server.git)          |
| ----------- | -------------|---------------------------------------|

```bash
# bash

# The current directory is the directory where the git local repository of xy_request_handler_web is located
# Switch to the project directory
cd ./samples/xy_web_server_demo

# Start the Tornado service of the sample project
xy_web_server -w tornado start

# The default Tornado service URL is: http://127.0.0.1:8400
# Open the browser and visit http://127.0.0.1:8400/demo for verification
```


## License
xy_request_handler_web is licensed under the <Mulan Permissive Software License，Version 2>. See the [LICENSE](../LICENSE) file for more info.

## Donate

If you think these tools are pretty good, Can you please have a cup of coffee?  

![pay-total](./pay-total.png)  


## Contact

```
WeChat: yuyangiit
Mail: yuyangit.0515@qq.com
```