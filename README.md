# cloudflare-workers

Cloudflare Worker scripts


## deploy

首页：[https://workers.cloudflare.com](https://workers.cloudflare.com)

注册，登陆，Start building，取一个子域名，Create a Worker。

复制 js 到左侧代码框，Save and deploy。


## example

- [https://github.com/cloudflare/worker-examples](https://github.com/cloudflare/worker-examples)

## limit

- [https://developers.cloudflare.com/workers/platform/limits](https://developers.cloudflare.com/workers/platform/limits)

## how-workers-works

- [https://developers.cloudflare.com/workers/learning/how-workers-works](https://developers.cloudflare.com/workers/learning/how-workers-works)

## cdn

虽然 Cloudflare Worker 使用 Cloudflare CDN，但分配给中国访客的 IP 并不友好（高延迟/高丢包/速度慢等）。

虽然 Cloudflare 公开了所有 IP 段 ，但想要在这么多 IP 中找到适合自己的，怕是要累死，可以通过 [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) 来获取速度最快的地址。

将获取到的地址与 Cloudflare Worker 域名绑定即可。

```
104.16.161.131 k8sgcr.lework.workers.dev
```
