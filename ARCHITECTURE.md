# Memory Machine — Prototype Architecture

```text
                ┌──────────────────────┐
                │     HUMAN MEMORY     │
                │ photo / voice / story│
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │    INPUT LAYER       │
                │ camera / microphone  │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │ CONTEXT & SAFETY     │
                │ facts / source /     │
                │ uncertainty           │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │   AI INTERPRETATION  │
                │ text / image / audio │
                └──────────┬───────────┘
                           ↓
              ┌────────────┼────────────┐
              ↓            ↓            ↓
          VISUAL        SOUND        WRITING
              └────────────┼────────────┘
                           ↓
                ┌──────────────────────┐
                │ MEMORY ARTIFACT       │
                │ source + outputs      │
                └──────────┬───────────┘
                           ↓
                    QR / NFC ARCHIVE
```

## Core principle

Generated outputs are interpretations. They should never be presented as recovered facts about a person or historical event.
