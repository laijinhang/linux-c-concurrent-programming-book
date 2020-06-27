# listen函数
**原型**
```c
#include <sys/socket.h>
int listen(int sockfd, int backlog)
```

**返回值**
* 成功：0
* 失败：-1

可通过errno获取失败原因

**错误信息：**
* EADDRINUSE：另一个socket也在监听同一个端口
* EBADF：参数sockfd为非法的文件描述符
* ENOTSOCK：参数sockfd不是文件描述符
* EOPNOTSUPP：套接字类型不支持listen操作
