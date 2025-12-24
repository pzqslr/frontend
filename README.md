"# frontend" 
# 60天前端学习计划

## 学习阶段安排

| 阶段 | 天数 | 任务 | 关键产出 | 学习资源（全部免费） |
|------|------|------|----------|----------------------|
| 0. 环境&工具 | 0 | Node20+VSCode+Git+PNPM 一次装完；注册 GitHub，建 repo「60days-frontend」；把本计划粘进 README 打 todo | 第 1 个 commit | Git 小游戏 1h |
| 1. 三件套极速过 | 1–3 | HTML5 语义化标签 + 表单 + SEO 快速过；CSS3 只看 Flex/Grid + 响应式 + 变量；JS 只看 ES6+（let/const、解构、箭头、Promise、async/await、模块化） | Day3 把「TodoMVC 静态版」push | MDN「Learn HTML/CSS」速读 + B 站「小马哥 ES6」2 倍速 |
| 2. DOM+事件+手写题 | 4–6 | 事件委托、闭包、节流防抖、深拷贝、数组去重、Promise.all 手写 | Day6 把「TodoMVC 本地存储版」push，README 附 6 张手写题截图 | 尚硅谷「JS 基础到高级」第 4-7 章 |
| 3. 网络&构建 | 7–8 | HTTP1/2、CORS、Cookie/Storage、Axios 封装；Vite 初始化项目、配置路径别名、环境变量 | Day8 把 TodoMVC 用 Vite+TS 重构，开 devServer | Vite 官方文档 30 min |
| 4. React 暴力入门 | 9–15 | 只看函数组件+Hooks（useState/useEffect/useRef/useCallback/useMemo）；React-Router v6；Ant Design 套壳；Redux Toolkit 走马观花 | Day15 完成「豆瓣电影」PC 版（搜索+列表+分页），部署 GitHub Pages | React 新文档 Beta「Learn」章节 + 技术胖「React18 极速版」 |
| 5. Vue3 暴力入门 | 16–22 | Composition API、Pinia、Element-Plus；写后台管理（登录+用户列表+权限菜单） | Day22 完成「Vue 后台」并部署 Vercel | Vue3 官方文档「快速开始」+ 技术胖「Vue3 后台极速版」 |
| 6. TypeScript 补漏 | 23–24 | 基本类型、接口、泛型、工具类型；把两个项目全量改 .tsx/.vue+TS | Day24 两个仓库全 TS 化，tsconfig 严格模式 0 error | TypeScript 手册「5min 入门」+ B 站「TS 极速课」 |
| 7. 性能+工程化 | 25–26 | Lighthouse 90+、路由懒加载、图片压缩、Gzip、GitHub Actions 自动部署 | Day26 README 贴 Lighthouse 截图 | Google Web Vitals 速读 |
| 8. 算法+八股文 | 27–36 | 每天 2 h 力扣前端题库（数组→字符串→链表→栈队列→二叉树→动态规划），共 100 题；同步背「前端八股文」30 问（事件循环、跨域、Diff、闭包、虚拟 DOM、响应式） | Day36 把 100 题刷完截图+八股文整理成 Notion 速查表 | 力扣「Top 100」+ 牛客「2025 前端面经」 |
| 9. 简历+模拟面试 | 37–42 | 用「超级简历」一页模板；项目 STAR 描述；找人 mock（牛客/小红书/学长）≥3 场；根据反馈改项目 | Day42 简历定稿，GitHub 链接可秒开 | 牛客 AI 模拟面试 |
| 10. 海投+冲刺 | 43–60 | 每天 3 家日常实习+3 家春招，共 100+ 投递；同步补面经盲区（微前端、SSR、Next.js 了解即可） | Day60 拿到 ≥1 offer 或 ≥3 面试流程中 | Boss 直聘+牛客内推 |
Git 小游戏：https://learngitbranching.js.org
阶段一
MDN「Learn HTML」速读（只看 3 章）：https://developer.mozilla.org/zh-CN/docs/Learn/HTML
CSS3
Flex 交互游戏（30 min 通关）：https://flexboxfroggy.com
Grid 交互游戏（30 min 通关）：https://cssgridgarden.com
CSS-Tricks 速查表（收藏）：https://css-tricks.com/almanac/
JavaScript ES6
B 站「小马哥 ES6 极速版」2 倍速（共 6 集，每集 20 min）：https://www.bilibili.com/video/BV1uK411H7pp
阮一峰《ES6 标准入门》在线版（当字典）：https://es6.ruanyifeng.com/
阶段二
尚硅谷「JS 高级」手写题合集（直接看 PPT 源码）：https://www.bilibili.com/video/BV1NK411F7zV?p=15 起
30 道必会手写题整理（直接复制）：https://juejin.cn/post/7031032460446623758
TodoMVC 官方模板（原生 JS 版，直接 fork 改）：https://github.com/tastejs/todomvc/tree/master/examples/vanilla-es6
阶段三
尚硅谷 Ajax 2025 版（只看 P1–P25，共 2 h）：https://www.bilibili.com/video/BV1NK411F7zV
Vite 官方文档（10 min 速读）：https://vitejs.dev/guide/
Vite + TS 项目模板（官方，直接 degit）：npm create vite@latest my-app --template vanilla-ts
阶段四
React 新文档 Beta（只看「Learn」模块，代码可在线跑）：https://react.dev/learn
B 站「技术胖 React18 极速版」（共 18 集，每集 15 min）：https://www.bilibili.com/video/BV1sy4y1C7p6
Ant Design 5 官方示例（直接 fork 跑）：https://github.com/ant-design/ant-design-pro
React-Router v6 官方示例（10 min 跑通）：https://github.com/remix-run/react-router/tree/main/examples/basic
Redux Toolkit 官方模板（Vite 版）：
npm create vite@latest my-react-app --template react-ts
cd my-react-app && pnpm add @reduxjs/toolkit react-redux
阶段五
Vue3 官方文档「快速开始」（代码片段可复制）：https://cn.vuejs.org/guide/quick-start.html
B 站「技术胖 Vue3 后台极速版」（共 20 集，每集 20 min）：https://www.bilibili.com/video/BV1yS4y1m7d9
Element-Plus 官方模板（直接 clone）：git clone https://github.com/element-plus/element-plus-vite-starter
Pinia 官方示例（5 min 跑通）：https://github.com/vuejs/pinia/tree/v2/packages/playground
阶段六
TypeScript 手册「5 分钟入门」：https://www.tslang.cn/docs/handbook/typescript-in-5-minutes.html
B 站「黑马 TS 极速课」（共 8 集，每集 15 min）：https://www.bilibili.com/video/BV1yK411n7kJ
React/Vite 模板已带 TS，无需再配；Vue3 用官方模板：
npm create vite@latest my-vue-app --template vue-ts
阶段七
Lighthouse CI 官方 GitHub Action（复制 yml 即可）：https://github.com/GoogleChrome/lighthouse-ci
图片批量压缩在线工具（免注册）：https://tinypng.com
掘金「性能优化 21 条」速查（收藏）：https://juejin.cn/post/7031032460446623758
阶段八
力扣前端题库（按标签刷，免费）：https://leetcode.cn/problemset/?topicSlugs=array,string,linked-list,stack,queue,dynamic-programming
牛客「2025 前端八股文」30 问（直接背）：https://www.nowcoder.com/review/frontend
前端真实面试题库（小红书合集）：
微信小程序搜「前端面试题精选」→ 每日更新 5 题
