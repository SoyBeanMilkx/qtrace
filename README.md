# qtrace



## 速度

2GB+/min

 ![](upload/tmp/947037_YZS68P6XXE9XPSC.webp)

## 格式

```bash
libName!{symbolInfo}!{traceType}
```

其中：

1. **symbolInfo**可以是符号名(并不保证百分百能解析出偏移)、偏移地址、IDA反汇编风格函数名(sub_xxxx)
2. **traceType**定义
   1. *func_code*：常规汇编流
   2. *func_call*：函数调用关系
   3. *mem_rw*：内存读写情况



## 日志格式

### func_code

 ![](upload/tmp/947037_SC34KAPHX9VK4DG.webp)


### func_call
 ![](upload/tmp/947037_XYNCGS7BAPJA6PM.webp)
 ![](upload/tmp/947037_NX763JTDGRRB85B.webp)


## == END ==

不开源。因为部分代码参考了**追佬的vm-trace** 欢迎大家使用vm-trace

