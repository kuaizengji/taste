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

## Impeccable

- 名称：Impeccable
- 链接：https://github.com/pbakaus/impeccable
- 是什么：装进编码代理的设计技能，外加一个不调用模型的检查器。
- 什么时候用：已有网页要跑 npx impeccable detect 量对比度、字号、行长。
- 什么时候不用：不要把它的眉题、12px、ease-out 当成 taste 的新法律。
- 怎么用：让 Agent 读上游仓库，对已有网页跑 `npx impeccable detect`。不要把规则抄进 taste。

## Hallmark

- 名称：Hallmark
- 链接：https://github.com/Nutlope/hallmark
- 是什么：装进编程代理的网页设计技能。先过 Floor，再做一整页。
- 什么时候用：新的一整页。说出 custom 才是从零；不说就发一套主题。
- 什么时候不用：已有设计要改，必须点名 redesign 或 audit。主题、脚本和站点不在 taste 里。
- 怎么用：读 ui/hallmark。Codex 能跑，但不是更完整的检查环。

## Landing page

- 名称：Landing page
- 链接：https://github.com/elayadesign/ai-design-skills
- 是什么：落地页怎么说、首屏放什么、什么不许编。
- 什么时候用：落地页，不是全部界面。
- 什么时候不用：不要把它的字体表、680px、500ms、三十档字号，或「仪表盘也照做」收成 taste 的规则。
- 怎么用：读 ui/landing-page。

## Design Spells

- 名称：Design Spells
- 链接：https://designspells.com/
- 是什么：找界面灵感的网站。
- 什么时候用：要看别人怎么做某一处交互或视觉时，去那里翻例子。
- 什么时候不用：要的是 taste 里已经写下的判断时，不要用灵感站代替规则。
- 怎么用：打开链接。不把页面抄进 taste。

## Lobe UI

- 名称：Lobe UI
- 链接：https://ui.lobehub.com/
- 仓库：https://github.com/lobehub/lobe-ui
- 是什么：npm 包 @lobehub/ui，LobeHub 的 React 组件库，建在 Base UI 上。
- 使用范畴：C 端 AI 网页。对话（流式消息、输入区）和他们那套落地页。整套安装，不把零件拆去配另一套设计系统。不管桌面 Agent、B 端后台、图标选型。
- 什么时候不用：要的是 taste 已有的门禁或另一套组件时。
- 怎么用：按上游文档 pnpm add @lobehub/ui。不把代码抄进 taste。

界面图标选用见 [vi/icons.md](../vi/icons.md)。一个产品只用一套。

## 存 25 个 Vibe Coding 的参考网站

- 名称：存 25 个 Vibe Coding 的参考网站
- 链接：https://mp.weixin.qq.com/s/sL2pLGaGCn52KZNMT3IpNg
- 作者：EverettFish
- 是什么：前端案例和组件库的收藏清单。
- 使用范畴：说不清想要的效果时，拿具体站点给 AI 看。不代替 taste 已有的判断。
- 清单：[ui/prompt-sources/everettfish-vibe-sites.md](../ui/prompt-sources/everettfish-vibe-sites.md)

## 给 Vibe Coding 小白的前端效果词典

- 名称：给 Vibe Coding 小白的前端效果词典
- 链接：https://mp.weixin.qq.com/s/ojAQxVHYIsANwh61zyOOgw
- 作者：EverettFish
- 用途：查 UI 元素的专有名词。
- 清单：[ui/prompt-sources/everettfish-effect-glossary.md](../ui/prompt-sources/everettfish-effect-glossary.md)
- 什么时候不用：要执行已有门禁时，以那些文件为准。

## 人人都是 UI 设计师（Refactoring UI 20 条）

- 名称：人人都是 UI 设计师（Refactoring UI 20 条）
- 链接：https://x.com/longhaiqwe123/status/2106216781174251724
- 作者：龙海
- 清单：[ui/prompt-sources/longhai-refactoring-ui/](../ui/prompt-sources/longhai-refactoring-ui/)

## 用 AI，把照片秒变 LOGO

- 名称：用 AI，把照片秒变 LOGO
- 链接：https://mp.weixin.qq.com/s/Bo6adIxMnRResGHkQKIeEw
- 作者：告白天
- 是什么：把一张主体照片收成品牌标志的提示词，外加四条不能直接用的照片。
- 什么时候用：要从人物、动物、植物或建筑的照片做出品牌标志时。
- 什么时候不用：选界面图标时看 [vi/icons.md](../vi/icons.md)。不把原文案例图，或星巴克、肯德基、阿童木当成本仓库的参考资产。
- 怎么用：读 [vi/gaobaitian-photo-to-logo.md](../vi/gaobaitian-photo-to-logo.md)。

## AI 做设计总像模板？因为你少写了这 5 样

- 名称：AI 做设计总像模板？因为你少写了这 5 样
- 链接：https://mp.weixin.qq.com/s/J7MhBhzAMIF_WPEWFoIEEw
- 作者：PennW
- 是什么：让 AI 出界面初稿时，第一句话要写清的五要素，以及生成后改细节还是重来。
- 什么时候用：开口要一版界面初稿，或生成完要决定修还是重来时。
- 什么时候不用：界面已经有门禁时，以那些文件为准。不覆盖落地页、Hallmark、B 端、桌面 Agent、图标选型、龙海。文中工具对照和 263 个站不抄进来。
- 清单：[ui/prompt-sources/pennw-five-elements.md](../ui/prompt-sources/pennw-five-elements.md)

## Lemo-Opuscar

- 名称：Lemo-Opuscar
- 链接：https://github.com/lemomo-ai/lemo-opuscar
- 图鉴：https://lemomo-ai.github.io/lemo-opuscar/
- 是什么：Claude Code 技能，外加 66 种用代码做的短片风格。画面逐帧渲染，不用视频模型。
- 什么时候用：点名一种画风，要用它的管线做代码短片时。
- 什么时候不用：要的是已经写下的节奏和镜头时，读 [video/lemo-opuscar.md](../video/lemo-opuscar.md)。不要把风格提示词或渲染代码抄进 taste，也不要把画风清单当成所有视频的法律。普通剪辑、转码不用。风格按 Claude Opus 5.5 调校。
- 怎么用：装上游 skill 或读那个仓库。不把代码抄进 taste。

## beat-promo-director

- 名称：beat-promo-director
- 链接：https://github.com/kuaizengji/beat-promo-director
- 是什么：把分镜做成 10–40 秒、音乐卡点、大字排版的宣传片。渲染、配乐和抽帧在上游 kit 里。
- 什么时候用：做这种卡点大字宣传片，并要用它的 kit 出片时。
- 什么时候不用：有故事、点名画风的代码短片看 [video/lemo-opuscar.md](../video/lemo-opuscar.md)。不要自己搭截帧管线，也不要把 kit 抄进 taste。
- 怎么用：读上游 SKILL.md，跑 kit。判断在 [video/beat-promo-director.md](../video/beat-promo-director.md)。



