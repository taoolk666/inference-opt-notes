# CUDA学习笔记 Day1

## 今天学了什么
- 线程层次：Grid → Block → Thread
- 内存层次：Global → Shared → Register

## 代码片段
```cuda
__global__ void hello() {
    printf("Hello from thread %d\n", threadIdx.x);
}
