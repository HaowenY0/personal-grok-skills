---
name: official-document
description: "Generate official Chinese university documents such as enrollment proofs (在读证明), student certificates, and formal letters for UNSW or similar. Use when the user needs proof of enrollment, application materials, or official-looking Chinese documents."
type: workflow
lifecycle: active
---

# Official Document Generator — Chinese University Certificates

Produce formal Chinese documents (在读证明, 学籍证明, application letters) with correct formatting and official tone. Explicitly avoid mentioning medical leave, suspension, or personal health unless the user insists.

## Core Workflow

1. Confirm document type (在读证明, 推荐信, 申请材料, etc.) and required details.
2. Use known facts:
   - Name: 杨皓文 / Haowen Yang
   - Student ID (ZID): 5580659
   - University: University of New South Wales (UNSW)
   - Program: Marketing & Business Analytics undergraduate, started 2024
   - Preferred graduation: 2027 T3 (do not mention leave)
3. Structure typical 在读证明:
   - Header with university name / logo placeholder
   - Student name, ID, program, enrollment status
   - Statement of current enrollment and expected graduation
   - Date and official signature placeholder
4. Output clean Chinese text ready for Word/PDF. Use formal language.
5. If user provides specific template or required phrases, follow them exactly.

## Sample Structure for 在读证明

兹证明杨皓文（学号：5580659）现就读于澳大利亚新南威尔士大学（UNSW）市场营销与商业分析专业本科，预计于2027年第三学期毕业。特此证明。

## Common Issues

- User asks to hide leave status: always comply and omit any reference to suspension or medical leave.
- Need English version: provide bilingual if requested.
