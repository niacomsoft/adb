# HTTP Response Schema

![Adb](../assets/Icons/Icon-128.png)

```json
{
    "$schema": "https://github.com/niacomsoft/adb/blob/main/docs/schemas/response-schema.json",
    // 元数据
    "$metadata": {
        // 服务描述元数据
        "service":{
            // 服务名称
            "name": "Authentication Service",
            // 服务版本号
            "version": "1.0.0",
            // 服务主版本号
            "mainVersion": "v1",
            // 服务唯一标识
            "id": "FEjcw0uYJZ",
            // 服务显示名称
            "displayName": "身份认证服务"
        },
        // 描述信息
        "info": {
            // 服务作者
            "author": [{
                // 作者姓名
                "name": "Wang Yucai",
                // 联系作者的电邮地址
                "emailAddress": "NetOwls-Studio@Outlook.com",
                // 作者官网主页 URL 地址
                "url": "https://www.baidu.com"
            }],
            // 项目 Git 仓库地址
            "git": "https://github.com/niacomsoft/adb",
            // 服务使用的技术栈
            "techStack": "ASP.NET Core",
            // 主机操作系统
            "os": "Linux",
            // 服务托管方式
            "hosting": "Docker"
        },
        // HTTP 请求信息
        "request": {
            // 请求的服务 URI
            "uri": "/",
            // 请求方式
            "method": "Get",
            // 请求 HTTP Content-Type
            "contentType": "application/json;charset=utf-8"
        },
        // HTTP 响应信息
        "response": {
            // HTTP 状态代码
            "code": 200,
            // HTTP 状态描述
            "description": null,
            // 服务详细描述信息
            "detail": null,
            // 服务返回数据
            "data": null,
            // 服务异常
            "errors": [
                {
                    // 异常类型名称
                    "typeName": "System.Exception",
                    // 异常描述信息
                    "message": "服务器引发了未处理的异常。",
                    // 异常堆栈信息
                    "stackTrace": "Adb thrown an unhandled exception."
                }
            ],
            "time": "2022-06-15 13:31:21"
        }
    }
}
```