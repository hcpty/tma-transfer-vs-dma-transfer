# Readme
A comparison between TMA (Traditional Memory Access) Transfer and DMA (Direct Memory Access) Transfer.

### TMA Transfer vs DMA Transfer

问题：在外设缓冲和内核外设缓冲之间拷贝一份数据。

解法1：使用TMA Transfer，会浪费CPU周期：
```
1. CPU控制传输。
```

解法2：使用DMA Transfer，需要使用DMA Controller，不会浪费CPU周期：
```
1. CPU向DMA Controller发出传输指令。
2. DMA Controller控制传输。
3. DMA Controller中断CPU。
```

### Credits
- [Direct memory access - Wikipedia](https://en.wikipedia.org/wiki/Direct_memory_access)
