# quick-thought-capture
- n8n 워크플로우 구조 
```txt
[Webhook Trigger]
   ↓
[Input Type 분기 (text vs voice)]
   ↓
[음성 → 텍스트 변환 (optional)]
   ↓
[AI Summarizer (OpenAI, Claude 등)]
   ↓
[Format 처리 (title, body 등)]
   ↓
[Notion Page 생성]
```