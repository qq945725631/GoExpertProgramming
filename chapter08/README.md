前面介绍了go test用于单元测试、性能测试和示例测试，但Web应用程序中往往需要与其他系统进行交互，比如通过http访问其他系统，此时就需要有一种方法用于打桩来模拟Web服务器和客户端，httptest包即Go语言针对Web应用提供的解决方案。

httptest可以方便的模拟各种Web服务器和客户端，以达到测试目的。