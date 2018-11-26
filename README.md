# nginx-compile

一键命令编译 nginx，

```shell
sh -c "$(curl -kfsSl https://raw.githubusercontent.com/xzhih/nginx-compile/master/install.sh)"
```

## 特性

- https 开启 TLS1.3，并支持 TLS1.3 的 23,26,28 草案，以及 Final 版标准
- 使用 cloudflare 优化的 zlib，有更强的 gzip 性能
- brotli 压缩，比 gzip 更强的压缩算法，已支持主流浏览器
- 更好的内存管理 jemalloc
- 可选择安装 ngx_lua_waf 高性能轻量化 web 应用防火墙
- nginx 服务进程
- nginx 日志规则 (自动分割)

## 其他

其他详细描述可以看我的博客

https://zhih.me/make-your-website-support-tls1-3 

https://zhih.me/ngx-lua-waf

当然你也可以直接看脚本的代码