---
author: ["管理员"]
title: "公告"
date: "2024-07-12"
summary: "关于本站，以及如何预约/公告 Seminar。"
tags: ["公告"]
categories: ["系统信息"]
---

本站由西安交通大学人工智能学院学生自发维护，旨在为学院学生提供一个方便的学术交流平台。本站公告并维护 Seminar 信息，并计划定期开展 Seminar。在计划之外的分享同样是被鼓励的。

## 如何预约/公告 Seminar

本站使用 Hugo 框架进行搭建并且维护，同时使用 PaperMod 主题。因此，您需要具备一定的 Git 和 Markdown 知识才能发布新的公告。相关技能的初步了解可以前往 [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600) 以及 [Markdown 官方教程](https://markdown.com.cn/basic-syntax/) 进行学习。

预约/公告 Seminar 的流程与 Github 正常的 PR 流程一致，您需要 Fork 本站仓库，并在本地进行修改与 commit，最后提交 Pull Request。

有必要重点提及的是，关于 Hugo 的目录组成，以及如何在 Hugo 中创建新的文档。

作为非开发者，公布公告仅需要关注根目录下的 `content/posts` 目录，其中的内容为本站的全部内容的源文件。在该目录下创建一个新的 Markdown 文件，并在开头写入配置信息，即可
完成一篇新的公告的创建。

例如，在 `content/posts` 目录下创建 `announcement.md` 文件，并在其中写入以下内容：

```yaml
author: ["管理员"]
title: "公告"
date: "2024-07-12"
summary: "关于本站，以及如何预约/公告 Seminar。"
tags: ["公告"]
categories: ["系统信息"]
```

后续的全部内容则根据 Markdown 的语法进行编写即可。

## 格式规范

在本站进行公告以及宣传，需使用 Markdown 进行编写。任何具有创意的页面编辑均是被允许的，但是为了网站的格式化表达，我们依然给出对于文章内容的格式规范：

使用以下的默认配置：

```yaml
author: ["线下地址/腾讯会议"]
title: "XJTU AI Seminar 2024 - X"
date: "2024-07-12"
summary: "主讲人信息。"
tags: ["Seminar 所在领域"]
categories: ["Seminar"]
```

其中，`author`, `summary` 和 `tags` 部分需要根据实际情况进行修改。同时 Title 部分需要按照当前的 Seminar 序号进行命名，例如 `XJTU AI Seminar 2024 - 1`。

一般来说，公告的编写需要遵循常见的 Markdown 书写规范，这包括：

- 使用二级标题作为最高级别标题
- 在英文/代码块的两侧添加空格，在半角符号的后侧添加空格。

更多的写作规范，本站将建立公告模板以供参考。