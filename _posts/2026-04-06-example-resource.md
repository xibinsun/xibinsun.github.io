---
layout:     post
title:      示例资源：如何使用资源页面
subtitle:   这是一个示例，可以删除
date:       2026-04-06
author:     孙喜斌
header-img: img/2019.jpeg
catalog:    true
category:   resource
tags:
    - 使用说明
---

## 如何添加新资源

在 `_posts` 文件夹中新建一个 `.md` 文件，命名格式为 `YYYY-MM-DD-标题.md`，和博客文章一样。

唯一的区别是在头部加上 `category: resource`，这样它会出现在资源页面而不是博客页面。

```yaml
---
layout:     post
title:      资源标题
subtitle:   资源副标题（可选）
date:       2026-04-06
author:     孙喜斌
header-img: img/2019.jpeg
category:   resource
tags:
    - 标签1
    - 标签2
---
```

然后在下方写正文内容即可，和博客文章的写法完全一样。
