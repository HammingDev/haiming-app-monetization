# haiming-app-monetization

海明Dev（HammingDev）· App 商业化 Skill

# 用法
在 App 项目目录调用，读取实际实现，研究同类产品，给出可以继续交给开发 Agent 执行的 onboarding、付费墙和套餐方案。

## 安装

```bash
npx skills add HammingDev/haiming-app-monetization
```

安装到当前项目的 Codex：

```bash
npx skills add HammingDev/haiming-app-monetization --agent codex --yes
```

全局安装到 Codex：

```bash
npx skills add HammingDev/haiming-app-monetization --agent codex --global --yes
```

也可在交互安装时选择其他受支持的 Agent。

## 使用

在 App 项目对应的任务中输入：

```text
使用 $haiming-app-monetization 评估当前项目，研究相关竞品，
给出套餐定价、个性化 onboarding 和付费墙方案，先不修改代码。
```

也可以只处理一个环节：

```text
使用 $haiming-app-monetization 检查当前付费墙的会员权益、试用说明和购买路径。
```

希望落实方案时，明确要求“评估并实现”。没有源码也可以提供产品说明、截图或录屏进行辅导。

## 输出与边界

- 真实路径与优先问题：定位到页面和代码，区分静态推导与运行观察。
- 竞品与候选定价：注明地区、币种、周期、来源和未知项。
- 分支 onboarding：让用户的选择对应不同演示、亮点和文案。
- 付费墙：明确权益、主推套餐、试用和购买后的下一步。
- 实施与验证：复用位置、必要改动和首轮实验。

默认评估，不修改产品代码；明确要求实现后才执行相应修改。联网研究与项目读取依赖运行 Agent 的工具能力。不能联网时会标注价格未核实。不会承诺转化率或收入提升。

## 版本与验证

当前为 v0.1.0。已通过 Skill 格式校验；方法在 Life Widget 项目完成过静态评估和竞品研究。尚未证明实际转化提升。仓库不包含项目源码或私人合作 brief。

入口为 [SKILL.md](SKILL.md)，行为验收参考 [acceptance.md](references/acceptance.md)。

## 作者与共创

作者：**海明Dev / HammingDev**，Skill 前缀：`haiming`。

本 Skill 为 Meoo「AI Builder Growth Kit｜从 Vibe Coding 作品到真实收益」共创成果，以 **海明Dev（HammingDev）× 秒悟 Meoo** 联合署名。

[Meoo 官网](https://meoo.com)；本 Skill 包的 Meoo 官方入口待项目方提供，当前不表示已在 Meoo 上架。

本仓库采用 [MIT 许可证](LICENSE)，允许使用、修改、再分发与商业使用；分发时须保留版权声明和许可证。
