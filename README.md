# 独立开发者的最佳技术栈

> 是想通过独立开发赚钱吗？可以看看辛宝这篇文章[独立开发赚钱吗](./docs/独立开发赚钱吗.md)

独立开发，核心是产品换钱。所以投在技术上，roi并不高。quick第一，dirty与否不重要

所以，在选技术栈的时候，关注难度小，交付快。

- 简单
- 快
- 兼容性好
- 最好也能ai辅助

## 你是什么主义？

实用主义 vs 专业主义

- 专业主义：你可用Next + Nest，你可用ts，你可以关注测试覆盖率，如何做可信软件，原因很简单，1、公司给你发工资，2、自己凭兴趣。
- 实用主义：很多独立开发者自己是老板，非常关注时间ROI，能花钱外包的就外包，能用技术快速搞定的就快速搞定，更专注实现的成就感。

## 技术栈

前置条件，你多少要了解一些编程技能，无论那种。

基础5大件：node+astro+react+tailwind+mdx

后端node里已经有了。koa\express就够了，vercel上发布。
当然，vercel funcion、next也行
如果在补一个，shadcn/ui可以算一个。

至此。8大技术栈

- 1、node（基础）
- 2、astro（基础）
- 3、react（基础）补[React自学路径](https://indie.npmstudy.com/react)。
- 4、tailwind（基础）
- 5、mdx（基础）
- 6、next（进阶）
- 7、remix（进阶）
- 8、shadcn/ui（进阶）

## 使用场景

- 快速建站
- [用Starlight写文档](https://indie.npmstudy.com/scenes/docs/)
- 建博客
- 加订单、支付
- 集成服务
- 开发完整saas
- 海外支付

分析

- 门户、博客、文档，astro无敌，性能好，开发简单，如果想ssr，也可以有很多node adapter
- 简单api，express、koa、vercel funcion、next都可以
- astro可以quick，也可以dirty。我个人比较习惯react，组件生态足够。实在需要，加个shadcn/ui
- 我不喜欢next，但next有一些生态是不错的，拿过来改改用，还是很爽的
- 关于css，tailwind写响应式，真是太爽了，不是那么关注可读性，那真是太快了
- 用tailwind 和 shadcn/ui 的好处之一是可以搭配https://v0.dev 遇到想不出来的样式，可以直接问，拷贝一下，依赖一装，成了
- 以上技术和各种现有服务都非常容易集成，比如clark、paddle、supabase、stripe，这些现有集成的，都放在独立开发者的服务。集成服务是要花不少精力的一部分。

## 新手的话应该从哪里开始这个项目

你需要有

- 域名
- Github账号
- 使用Github账号关联Vercel

然后，用astro先搞快速建站、写文档、建博客。

搞定建站和发布，里面写页面就需要react、tailwind了，循序见见

熟悉基础技术

- 1、node（基础）
- 2、astro（基础）
- 3、react（基础）
- 4、tailwind（基础）
- 5、mdx（基础）

然后，根据其他使用场景，熟悉进阶技术栈。

- 6、next（进阶）
- 7、remix（进阶）
- 8、shadcn/ui（进阶）

## 还愿清单

- 写一个个人站点
- 写一个项目或教程文档
- 建一个博客
- 写一个组件
- 开发一个micro saas
- 用一次ai写10行以上代码

## 其他

- 你这个技术栈不考虑APP？答：水太深，只推荐native
- 有人说next就不需要astro。我的回复是未必，做静态站点，next远没有astro爽。别说astro兼容vue、alphine等，就是性能，collection也吊打next。
- 2gua过两天会说用go也挺好的：go只能替换node部分，都是function，无所谓的。会啥用啥。剩下那几个都依赖node，娃哈哈

独立开发者要求快，能复用就复用，将精力放到产品设计上才是正经事。

以上。欢迎讨论
