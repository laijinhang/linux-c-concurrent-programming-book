# 内存映射：
**建立内存映射：**
1. mmap：`void *mmap(void *addr, size_t length, int prot, int flags, int fd, off_t offset);`
2. mmap64

**解除内存映射：**
1. munmap：`int munmap(void *addr, size_t length);`
