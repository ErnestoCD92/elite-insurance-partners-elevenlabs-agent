┌─────────────┐
│   Customer  │
│   (Phone)   │
└──────┬──────┘
       │
       │ Calls
       ↓
┌─────────────────┐
│  Twilio Phone   │ ← Your phone number
│     Number      │
└────────┬────────┘
         │
         │ Webhook
         ↓
┌─────────────────────────┐
│   ElevenLabs Agent      │
│   (Sarah)               │
│                         │
│  ┌─────────────────┐    │
│  │ System Prompt   │    │ ← Your behavioral rules
│  │ (Brain)         │    │
│  └─────────────────┘    │
│                         │
│  ┌─────────────────┐    │
│  │ Knowledge Base  │    │ ← Your 4 documents
│  │ (Memory)        │    │
│  └─────────────────┘    │
│                         │
│  ┌─────────────────┐    │
│  │ Voice (Sarah)   │    │ ← Natural speech
│  └─────────────────┘    │
└─────────────────────────┘
         │
         │ If needed
         ↓
┌─────────────────┐
│  Human Agent    │ ← Escalation for
│  (Specialist)   │   complex cases
└─────────────────┘