```bash
git checkout feature-newblog

cd theme

## 下载 maupassant-hexo 主题内容
git clone https://github.com/7ye/maupassant-hexo.git
npm install hexo-renderer-jade --save


## hexo 相关
## https://hexo.io/zh-cn/docs/commands

hexo g -f  ## 强制删除生成的静态文章，重新再生成

hexo d ## 发布
```