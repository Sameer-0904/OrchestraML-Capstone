# OrchestraML Architecture

```text
                        ┌────────────────────┐
                        │       User         │
                        │ Natural Language   │
                        │ Goal / Prompt      │
                        └─────────┬──────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │       Launchpad          │
                    │ Input + Execution UI     │
                    └─────────┬───────────────┘
                              │
                              ▼
                 ┌─────────────────────────────┐
                 │     Orchestrator Agent       │
                 │ Pipeline Planning & Routing  │
                 └─────────┬───────────────────┘
                           │
        ┌─────────┬────────┼────────┬─────────┐
        ▼         ▼        ▼        ▼         ▼

┌──────────┐ ┌────────┐ ┌────────┐ ┌────────┐ ┌──────────┐
│ Dataset  │ │  EDA   │ │Cleaning│ │Feature │ │Modeling  │
│ Agent    │ │ Agent  │ │ Agent  │ │ Agent  │ │ Agent    │
└────┬─────┘ └────┬───┘ └────┬───┘ └────┬───┘ └────┬─────┘
     └────────────┴──────────┴──────────┴──────────┘
                           │
                           ▼

               ┌──────────────────────┐
               │ Evaluation Agent     │
               └──────────┬───────────┘
                          │
                          ▼

               ┌──────────────────────┐
               │ Deployment Agent     │
               └──────────┬───────────┘
                          │
                          ▼

              ┌────────────────────────┐
              │ Human-in-the-Loop × 6  │
              │ Validation Checkpoints │
              └──────────┬─────────────┘
                         │
                         ▼

              ┌────────────────────────┐
              │ Final Report Generator │
              └────────────────────────┘


Powered by:
Frontend → Next.js
Backend → Python
LLM → Google Gemini
Storage → Supabase
Cache → Redis
```
