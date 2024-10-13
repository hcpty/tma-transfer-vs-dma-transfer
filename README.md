# Readme
A comparison between Traditional Memory Access and Direct Memory Access.

```
场景：在外设缓冲和内核外设缓冲之间拷贝数据。
```

```
方式1：Traditional Memory Access

过程如下：
1. CPU控制传输
```

```
方式2：Direct Memory Access

过程如下：
1. CPU发起
2. DMA Controller控制传输
3. DMA Controller中断CPU
```
