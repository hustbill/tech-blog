### Git Operations
```
$ git remote add origin  <REMOTE_URL> 
$ git remote add origin https://github.com/hustbill/tech-blog.git

# Sets the new remote
$ git remote -v
# Verifies the new remote URL

git push --set-upstream origin master

```

## Install  themes/archer 
```code
npm i hexo-generator-json-content --save && npm i --save hexo-wordcount && git clone https://github.com/fi3ework/hexo-theme-archer.git themes/archer --depth=1
```

## Add a post into source/_posts
```markdown 
---
title: "React Hooks"
subtitle: "Hooks实践"
layout: post
author: "hua"
header-style: text
hidden: false
tags:
  - 技术笔记
  - React
---
这是一篇博文的例子。
```

## Start
```
$ hexo serve

INFO  Validating config
INFO  Start processing
INFO  Hexo is running at http://localhost:4000 . Press Ctrl+C to stop.
```

