字节对齐这个概念有两处需要强调：

1. CPU 只从对齐的地址开始加载数据
2. CPU 读取块的大小是固定的，通常为 B 的 2 的整数幂次