# Features and boundaries

Yuiluma is a private Windows desktop application with four primary spaces: Chat, Tasks, Memory and Settings.

| Included | Boundary |
| --- | --- |
| Conversation through a local Ollama server | Model installation is separate; chat support does not establish tool capability. |
| Scoped file tools and approval dialogs | Work stays inside the chosen workspace; sensitive changes need approval. This is not an OS sandbox. |
| Inspectable action and result evidence | A completed write does not prove an entire natural-language request was fulfilled. |
| Optional First Hello | The greeting is a draft. Its file sample needs a chosen folder and explicit consent. |
| Exact checks for the bounded file sample | Folder, exact UTF-8 content and readback are checked. This is not a general-purpose goal verifier. |
| Local memories and optional conversation storage | Users choose what to retain; records are not application-encrypted. |
| Scoped scheduled tasks | The app must be open; saved scope and current permissions still apply. |
| Pause, Stop and window-close cleanup | Pause waits at a safe checkpoint. Completed changes are not automatically rolled back. |
| Reduce Motion and Gaming mode | Optional motion and scheduling remain under user control. |

The Y1 Woven Stem mark identifies the product. It is separate from Reina's character emblem. No 3D avatar, companion overlay, new character voice, microphone workflow or cloud AI service is part of this candidate.

The application is not publicly available. See the [roadmap](ROADMAP.md) for remaining release gates.
