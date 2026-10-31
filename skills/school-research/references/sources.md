# 来源白名单（已批准）

截至 2026-10-31，以下每个 URL 都已实际打开并读到页面内容，且页面显示对应官方机构名称。用户已于 2026-10-31 批准本清单的 7 个主机名。学校页面另须先由用户明确确认该校官方域名，确认范围包括该域名及其所有子域名。各校官方发布的 Common Data Set 归入该校已确认域名及其子域名，不预授权其他 CDS 托管域名。

| 机构与用途 | 已打开的入口 | 核验结果 |
|---|---|---|
| UCAS：英国申请周期与官方申请数据 | https://www.ucas.com/data-and-analysis/undergraduate-statistics-and-reports | 页面标题为 “Undergraduate statistics and reports”，域名 `www.ucas.com` |
| QILT：澳洲政府认可的学生体验与毕业生调查数据 | https://qilt.edu.au/ ；https://qilt.edu.au/About | 首页列出 SES/GOS；About 页确认政府认可和资助，域名 `qilt.edu.au` |
| UAC：澳洲新州及首都领地申请流程入口 | https://www.uac.edu.au/future-applicants/how-to-apply-for-uni/ | 官方 UAC 申请说明可读，域名 `www.uac.edu.au` |
| VTAC：澳洲维州申请流程入口 | https://vtac.edu.au/ | 页面标示 Victorian Tertiary Admissions Centre，域名 `vtac.edu.au` |
| QTAC：澳洲昆州申请流程入口 | https://www.qtac.edu.au/how-to-apply/ | 页面标示 Queensland Tertiary Admissions Centre，域名 `www.qtac.edu.au` |
| OUAC：加拿大安大略省申请流程入口 | https://www.ouac.on.ca/guide/undergrad-how-to-apply/ | 页面标示 Ontario Universities' Application Centre，域名 `www.ouac.on.ca` |
| Statistics Canada：加拿大高等教育统计 | https://www150.statcan.gc.ca/n1/daily-quotidien/261001/dq261001a-eng.htm | 加拿大政府页面和统计局检索入口可读，域名 `www150.statcan.gc.ca` |

以下为主机名清单，统计机构及申请服务机构均按 `whitelist` 中的主机名逐行精确匹配，不自动放行其他子域名：

```whitelist
www.ucas.com
qilt.edu.au
www.uac.edu.au
vtac.edu.au
www.qtac.edu.au
www.ouac.on.ca
www150.statcan.gc.ca
```

UCAS、UAC、VTAC、QTAC、OUAC 的申请流程页面不替代学校/课程当年具体门槛。QILT 与 Statistics Canada 的统计口径也不能推成单校录取率。每个数据字段须注明数据年份、对象和适用范围；没有原始指标就留空，不自行计算或估算。

**访问规则**：允许通过网页搜索提出候选官方域名，但必须等用户明确确认后才能访问该校页面；搜索结果页本身不得作为事实来源。用户确认的学校域名包含该域名及其所有子域名（例如院系子域名）；统计机构及申请服务机构仍按获批 `whitelist` 主机名精确匹配。不得沿链接访问未授权域名。

**明确禁止**：排名站、论坛、中介或咨询公司文章、社交媒体、百科。新增白名单主机须用户批准。

HESA、NCES、College Scorecard 的候选入口本次无法打开正文，故未加入；后续须实际打开核验并获用户批准，才能加入清单。
