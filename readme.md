# 
```sh
git clone --depth=1 --branch=wrangler2 https://github.com/cloudflare/worker-sites-template my-site
wrangler dev
#发布到pnpx
pnpx wrangler deploy
# 初始化github项目 增加github action发布
i ngh .
## 设置secrets ，可选
cf2 sghs CF_API_TOKEN $CF_API_TOKEN
# 初始化github项目 增加github action发布

```