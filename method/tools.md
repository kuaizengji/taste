# 工具

## Design Studio

- 名称：Design Studio
- 链接：https://github.com/itspatmorgan/design-studio
- 是什么：给设计师和产品经理的本地原型沙盒。人在已有编码代理里下指令，它提供浏览器预览和可替换的设计系统。不自带模型。早期 beta。
- 什么时候用：做前端界面或交互原型，需要在浏览器里看屏幕、换设计系统、把 React 屏幕和说明放在一起时。
- 什么时候不用：要的是 taste 的视觉判断（滚动、动效原则、VI、幻灯片、海报、视频）时，不要把它当成原则来源，也不要把它的品牌色和标当成 taste 的识别。
- 怎么用：让 Agent 去读那个仓库并在本地跑，不要把代码抄进 taste。

## Solid Glass

- 名称：Solid Glass
- 链接：https://github.com/deeplethe/solid-glass
- 文档：https://deeplethe.github.io/solid-glass/docs
- 是什么：盖在 shadcn/ui（Base UI）上的一层主题，外加一小套给「人看着代理干活」用的零件。不是独立组件库，不发 npm。安装：npx shadcn@latest add deeplethe/solid-glass/solid-glass
- 什么时候用：已有 shadcn/ui + Base UI 的 Agent 界面或 AI 应用，需要这层烟玻璃皮，或需要会话、工具步、diff、提问这类代理零件时。
- 什么时候不用：代码编辑器、IDE、C 端应用；也不要把它的品牌色或字标当成 taste 的识别。要的是 taste 自己的视觉判断时，不要把整份 CSS 抄进来。
- 怎么用：让 Agent 用上面的 shadcn add 装进目标项目，不要把代码抄进 taste。

## SPT · 项目交互设计总 Skill

- 名称：SPT · 项目交互设计总 Skill
- 链接：https://github.com/aixinxino/spt-ui-interaction-skills
- 是什么：交互选型 Skill，给编程 AI 按位置推荐组件名。
- 什么时候用：非专业的人要为界面某一处选组件或动效时。
- 什么时候不用：它没有高保真样子，不要把它当成组件库或原型。
- 怎么用：读 ui/interaction-skill，不要安装、不要把产品改成效果演示页。

## B端设计系统 Skill

- 名称：B端设计系统 Skill
- 链接：https://github.com/Ludi-Herry/b-end-design-system-skill
- 是什么：给编程代理用的 B 端后台决策 Skill。
- 什么时候用：B 端后台：页面骨架、抽屉/确认框/独立页、操作区门禁。
- 什么时候不用：不是组件库，不替代项目里已有的 shadcn 或 antd。
- 怎么用：读 ui/b-end-skill。

## Desktop Agent UI

- 名称：Desktop Agent UI
- 链接：https://github.com/Ludi-Herry/desktop-agent-ui
- 是什么：桌面 Agent 界面的视觉门禁。
- 什么时候用：做桌面 Agent 界面，要核对这组视觉门禁时。
- 什么时候不用：不是组件库；Open Claude UI 的设计令牌留在上游。
- 怎么用：读 ui/desktop-agent-ui。
