---
title: Azure Monitor Logs reference - SPAssessmentRecommendation
description: Reference for SPAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 3/16/2020
---

# SPAssessmentRecommendation

 Recommendations generated by SP assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- SPAssessment




## Columns

|Column|Type|Description|
|---|---|---|
|SourceSystem|string||
|AssessmentId|string||
|RecommendationId|string||
|Recommendation|string||
|Description|string||
|RecommendationResult|string||
|TimeGenerated|datetime||
|FocusAreaId|string||
|FocusArea|string||
|ActionAreaId|string||
|ActionArea|string||
|RecommendationWeight|real||
|Computer|string||
|AffectedObjectType|string||
|AffectedObjectName|string||
|Farm|string||
|Server|string||
|DatabaseName|string||
|WebApplication|string||
|Technology|string||
|CustomData|string||
|Type|string||