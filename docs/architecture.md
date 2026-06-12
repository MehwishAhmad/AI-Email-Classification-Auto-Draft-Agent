# System Architecture

Incoming Email
      ↓
 Gmail Trigger
      ↓
 Text Classifier
   ↙       ↘
Order    Inquiry
  ↓         ↓
AI Agent  AI Agent
  ↓         ↓
Groq LLM  Groq LLM
  ↓         ↓
 Gmail Draft Creation

## Workflow Components

### Gmail Trigger
Monitors incoming emails automatically.

### Text Classifier
Classifies emails into Order or Inquiry categories.

### AI Agent
Analyzes email content and generates responses.

### Groq LLM
Provides intelligent language processing and response generation.

### Gmail Draft
Creates ready-to-send email drafts.
