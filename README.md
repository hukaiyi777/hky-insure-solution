# hky-insure-solution · 养老与传承标准化解决方案

读取「风险评估报告」+「二次沟通记录」，把风险映射为可落地方案。只给工具类别与配置逻辑，不推具体产品。

## 依赖
零第三方依赖（仅 Python 标准库，直接构造 OOXML）。

## 内置生成器
`assets/solution_template.py`：把顶部 `DATA` 字典替换为本客户内容，`python solution_template.py` 即产出 `.docx`。

## 安装
把本目录整体复制到 WorkBuddy 用户技能目录（Windows）：
```
copy /Y * %USERPROFILE%\.workbuddy\skills\hky-insure-solution\
```
或在 WorkBuddy 中安装本包。

## 用法（复制给 WorkBuddy 的指令）
请用养老与传承标准化解决方案生成 Skill，读取下面的「风险评估报告」+「二次沟通记录」，产出标准版解决方案（人·权·财 主线，暖黄 1.0 版 docx）。方案只给工具类别+配置逻辑+参数化金额拆分，不推具体产品/品牌。

{粘贴风险评估报告 + 二次沟通记录}

## Demo
见 `demo/示例-养老与传承风险解决方案.docx`
