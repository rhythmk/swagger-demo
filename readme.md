## 安装 swagger
go get -u github.com/swaggo/swag/cmd/swag

## 添加 main.go 文件
```go
package main

import "fmt"

// @title Gin swagger
// @version 1.0
// @description Gin swagger 示例项目

// @contact.name wangk
// @contact.url https://wangk.top
// @contact.email wangkyx@qq.com

// @license.name Apache 2.0
// @license.url http://www.apache.org/licenses/LICENSE-2.0.html

// @host localhost:8080
func main() {
	// 省略其他代码
	fmt.Println("aa")
}

```
## 初始 swag 
swag init
