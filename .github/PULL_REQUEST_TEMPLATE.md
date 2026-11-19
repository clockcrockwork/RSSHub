<!-- 
If you have any difficulties in filling out this form, please refer to https://docs.rsshub.app/joinus/new-rss/submit-route
如果你在填写此表单时遇到任何困难，请参考 https://docs.rsshub.app/zh/joinus/new-rss/submit-route
-->

## Involved Issue / 该 PR 相关 Issue

Close #

## Example for the Proposed Route(s) / 路由地址示例

<!--
Please include route starts with /, with all required and optional parameters.
Fail to comply will result in your pull request being closed automatically.
请在 `routes` 区域填写以 / 开头的完整路由地址，否则你的 PR 将会被无条件关闭。
如果路由包含在文档中列出可以完全穷举的参数（例如分类），请依次全部列出。

```routes
/some/route
/some/other/route
/dont/use/this/or/modify/it
/use/the/fenced/code/block/below
```

If your changes are not related to route, please fill in `routes` section with `NOROUTE`. Fail to comply will result in your PR being closed.
如果你的 PR 与路由无关, 请在 `routes` 区域 填写 `NOROUTE`，而不是直接删除 `routes` 区域。否则你的 PR 将会被无条件关闭。
-->

```routes
```

## New RSS Route Checklist / 新 RSS 路由检查表
  
- [ ] New Route / 新的路由
  - [ ] Follows [Script Standard](https://docs.rsshub.app/joinus/advanced/script-standard) / 跟随 [路由规范](https://docs.rsshub.app/zh/joinus/advanced/script-standard)
- [ ] Anti-bot or rate limit / 反爬/频率限制
  - [ ] If yes, do your code reflect this sign? / 如果有, 是否有对应的措施?
- [ ] [Date and time](https://docs.rsshub.app/joinus/advanced/pub-date) / [日期和时间](https://docs.rsshub.app/zh/joinus/advanced/pub-date)
  - [ ] Parsed / 可以解析
  - [ ] Correct time zone / 时区正确
- [ ] New package added / 添加了新的包
- [ ] `Puppeteer`

## Note / 说明

## Acceptance criteria and next state

<!-- Decide verifiable acceptance criteria before adding work. Refer to existing criteria/evidence sections instead of maintaining duplicate records. -->
- Target: head SHA / base branch + SHA / tested merge SHA or tree (when relevant):
- Criteria and evidence: <!-- Link existing sections or use the table below. -->

| Acceptance criterion | Evidence, target SHA and environment | Result |
| --- | --- | --- |
|  |  | UNVERIFIED |

<!-- PASS / FAIL / UNVERIFIED / NOT_REQUIRED (reason required). A skipped, cancelled, NOT_REQUIRED, absent or old-head CI run is not a passing execution of the tests. -->
- Independent review: <!-- Reviewed head/base, receipt and unresolved findings. Check where existing evidence remains valid; distinguish a receipt from GitHub APPROVED. -->
- Current state and concrete remaining action: <!-- Action, owner and reason for waiting. For a human decision, identify what to inspect, what to decide and what happens next. -->
- State after acceptance: <!-- Ready for review / awaiting a named human decision / merge candidate / merge into an authorized parent / close as superseded. -->
- Integration/publication authority and impact: <!-- Target branch, applicable approval and deployment/publication effects. A merge candidate is not merge authorization. -->

<!-- Reuse valid evidence. When head/base changes, validate the changed diff and integration risks. Once implementation is complete and repository Ready requirements are met, leave Draft with the remaining review/decision stated unless an explicit owner/repository hold requires Draft. Preserve required checks, independent review, branch protections and publication authority. -->
