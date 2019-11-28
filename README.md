
shadowsocks ui
======================
在[tongsheClient.shadowsocks-go-ui](https://github.com/dawei101/tongsheClient.shadowsocks-go-ui)上修正了因为依赖库函数升级没法编译成功
和在win10下,一运行就报错的问题

具体的修改可以参看这个issue https://github.com/dawei101/tongsheClient.shadowsocks-go-ui/issues/2

因为原作者好像已经不维护这个了,所以我就没有fork然后merge,新开了个库

为了避免依赖库的升级再次出现编译失败的情况,加上了go mod
