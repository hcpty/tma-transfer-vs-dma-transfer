# Readme
A comparison between Traditional Memory Access and Direct Memory Access.

```
问题：在外设缓冲和内核外设缓冲之间拷贝数据。
```

```
解法1：Traditional Memory Access：

会浪费CPU周期：
1. CPU控制传输
```

```
解法2：Direct Memory Access：

不会浪费CPU周期：
1. CPU向DMA Controller发送传输指令
2. DMA Controller控制传输
3. DMA Controller中断CPU
```
