# 数据政策 | Data Policy

本文档说明 OPCBoundary 仓库中数据的管理方式。
This document describes how data is managed in the OPCBoundary repository.

## 适用范围 | Scope

本政策适用于 `data/` 目录下的所有内容以及本仓库中引用的所有数据。
This policy applies to all content under the `data/` directory and any data referenced throughout the repository.

## 收录标准 | Inclusion Criteria

数据仅在满足以下条件时方可收录：
Data is included only when it:

- 与项目的合规研究范围相关
  Relates to the project's compliance research scope
- 来源于公开且合法获取的渠道
  Is derived from publicly available, legally accessible sources
- 可提供可追溯的来源引用
  Can be documented with a traceable source reference
- 已经过敏感性和隐私审查
  Has been reviewed for sensitivity and privacy concerns

## 脱敏与敏感性 | De-identification and Sensitivity

所有数据在收录前必须经过审查：
All data must be reviewed before inclusion:

- 个人身份信息（PII）必须删除或匿名化处理
  Personal identifying information (PII) must be removed or anonymized
- 数据应尽可能聚合或抽象化
  Data should be aggregated or abstracted where possible
- 数据中不应可识别出具体个人
  Specific individuals should not be identifiable from the data
- 如检测到重新识别风险，该数据不得收录
  If re-identification risk is detected, the data must not be included

## 删除与下架 | Deletion and Takedown

在以下情况下，数据将被删除或修订：
Data will be removed or redacted when:

- 发现重新识别风险
  A re-identification risk is discovered
- 原始来源撤回或限制该信息
  The original source retracts or restricts the information
- 权利人提出合法的下架请求
  A rights holder submits a legitimate takedown request
- 新信息表明数据不准确或具有误导性
  New information suggests the data is inaccurate or misleading

## 更新与更正 | Updates and Corrections

- 数据随新的可靠信息出现而更新
  Data is updated as new reliable information becomes available
- 更正通过提交记录追踪
  Corrections are tracked via commit history
- 案例数据的实质性变更在提交信息中注明
  Substantive changes to case data are noted in commit messages

## 争议处理 | Dispute Resolution

如对收录数据产生争议：
If a dispute arises regarding included data:

1. 在 GitHub 提交 Issue 说明问题
   Open a GitHub issue describing the concern
2. 维护者将在合理时间内审查
   The maintainers will review within a reasonable timeframe
3. 审查期间，争议数据可暂时隐藏
   Pending review, the contested data may be temporarily hidden
4. 决定将在 Issue 中公布
   A decision will be communicated in the issue thread

## 禁止用途 | Prohibited Uses

数据使用者不得：
Users of the data must NOT:

- 尝试重新识别个人或特定实体
  Attempt to re-identify individuals or specific entities
- 将数据用于骚扰、歧视或定向曝光
  Use the data for harassment, discrimination, or targeted exposure
- 将数据用于商业画像或监控
  Use the data for commercial profiling or surveillance
- 在未包含本政策和适用 `DATA_LICENSE.md` 的情况下重新分发数据
  Redistribute the data without including this policy and the applicable `DATA_LICENSE.md`

## 风险确认 | Risk Acknowledgment

使用者确认：
Users acknowledge that:

- 数据可能包含错误或遗漏
  Data may contain errors or omissions
- 维护者不对基于此数据做出的决策承担责任
  The maintainers are not liable for decisions made based on this data
- 数据使用风险由使用者自行承担
  Use of the data is at the user's own risk
