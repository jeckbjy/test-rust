# test-rust
学习rust

## 语法学习

- Option<T>
    - None
    - Some
    - Some类型: https://www.zhihu.com/question/389859557
    - SumType in swift and kotlin : https://adapptor.com.au/blog/sum-types-in-swift-and-kotlin
- Result<T,Error>,用于返回带有Error的数据,
    - 使用?对Result解包,如果没有成功则提前返回错误
    - unwrap:当接收到None时panic
    -
- .await 等待异步结果
- 生命周期标注: 类似这种<'a>
    - https://llever.com/rust-by-example-cn/scope/lifetime/explicit.html
    - https://www.zhihu.com/question/435470652

## 资料

- [Rust程序设计](https://kaisery.github.io/trpl-zh-cn/title-page.html)
- [tao-of-rust](https://github.com/denglitong/tao-of-rust)
- [通过例子学习Rust](https://llever.com/rust-by-example-cn/index.html)
- [tokio](https://tokio.rs/tokio/tutorial/spawning)
- [memory manager](https://www.slideshare.net/eelcovisser/compiler-construction-lecture-15-memory-management)
- [self](https://www.jianshu.com/p/aeb0650f574b)
