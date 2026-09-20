<!-- 标题、heading 和 field label 使用英文；正文使用中文。填写后移除提示文字。 -->
## Pre-flight Plan

- Issue linkage（每个 relation 使用独立 plain-Markdown 行；不要把 closing keyword 与 parent reference 合并在同一句）:
  - `Closes #N`
  - `Refs #N`
  - 或 `None — <reason>`
- Goal: 说明具体问题，以及完成后可观察到的变化；必要时给出一个前后对比。
- Scope / non-goals: 说明包含和排除的行为。
- Touched files or areas: 列出计划涉及的文件或职责区域。
- PR grouping decision: 说明这些改动为何构成一个可独立验收的单元。
- Risks / shared-state ownership: 说明共享状态、依赖和恢复风险及其负责人。
- Verification plan: 说明拟运行的检查及预期结果。
- Review package: 按项目约定填写；没有该约定时省略。

## Review Highlights

<!-- 按优先级列出真正需要人工判断的事项。每项给出具体位置、要确认的问题及其影响；没有额外判断时如实说明。 -->
- Focus areas: `<path:line or symbol>` — 需要确认的具体行为或边界，以及判断错误的影响。
- Key decisions: 说明选择、依据和取舍，以及哪些判断仍待确认。
- Validation focus: 指向最有说服力的验证证据，并指出尚未覆盖的风险。

## Outcome Summary

- What changed: 说明实际行为变化，使用具体触发条件和前后结果。
- Deviations from plan: 仅记录相对原计划的变化及原因；原计划保持不变。
- Files map: 简述实际文件职责，细节与关键判断引用 Review Highlights。
- Verification performed: 记录实际命令、结果及未运行的检查和原因；区分自动验证与人工验证。
