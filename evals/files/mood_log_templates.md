# Mood Log Templates

## Daily Check-in Template

```
## 情绪日志 - {date}

### 当前情绪状态
- 总体感受: (1-10)
- 主要情绪: [高兴/平静/焦虑/悲伤/愤怒/恐惧/其他]
- 强度: (1-10)

### 触发因素
今天有什么让你感到[情绪]的事情吗？

### 影响评估
这个情绪对以下方面的影响程度:
- 睡眠: (0-3)
- 食欲: (0-3)
- 日常活动: (0-3)
- 社交: (0-3)
- 治疗依从性: (0-3)

### 备注
自由记录...
```

## PHQ-4 Screening Template

```
## PHQ-4 筛查问卷
在过去两周里，以下问题困扰你的频率是多少？

### 问题
1. 做事提不起劲或有兴趣
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

2. 心情低落、沮丧、或绝望
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

3. 睡不好、难以入睡或睡太多
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

4. 紧张、焦虑或烦躁
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

总分: ___/12

### 解读
- 0-2: 无明显抑郁症状
- 3-5: 轻度抑郁，需关注
- 6-8: 中度抑郁，建议寻求专业帮助
- 9-12: 重度抑郁，建议寻求专业帮助
```

## GAD-4 Screening Template

```
## GAD-4 筛查问卷
在过去两周里，以下问题困扰你的频率是多少？

### 问题
1. 难以控制担忧
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

2. 担心过多
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

3. 容易紧张或着急
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

4. 难以放松
   - 完全不会(0) / 几天(1) / 一半以上日子(2) / 几乎每天(3)

总分: ___/12

### 解读
- 0-2: 无明显焦虑症状
- 3-5: 轻度焦虑，需关注
- 6-8: 中度焦虑，建议寻求专业帮助
- 9-12: 重度焦虑，建议寻求专业帮助
```

## Conversation Summary Template

```json
{
  "conversation_id": "uuid",
  "date": "ISO 8601",
  "user_id": "anonymous",
  "session_type": "emotional_support | screening | crisis",
  "initial_sentiment": "positive | neutral | negative",
  "final_sentiment": "positive | neutral | negative",
  "themes_discussed": [
    "diagnosis_anxiety",
    "treatment_fear",
    "uncertainty_about_future",
    "caregiver_burnout",
    "family_pressure",
    "financial_concerns",
    "body_image",
    "relationship_issues",
    "survivor_guilt",
    "other"
  ],
  "crisis_detected": false,
  "phq4_score": null,
  "gad4_score": null,
  "dad_joke_told": false,
  "professional_referral_made": false,
  "notes": "自由记录"
}
```