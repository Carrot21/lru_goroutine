多Goroutine共享LRU缓存。
---
> ####Cap容量
> ####RandMax 取值范围。
> ####命中率约为：Cap/RandMax

命中率比想象中低。在生产环境中谨慎使用缓存。
> 缓存缺点：
>---
>    1.调试困难
>    2.晚上容易接到老板电话。
>    3.容易加班。

>> go run example.go