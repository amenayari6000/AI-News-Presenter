# AI News Presenter

AI pipeline to recreate a television news broadcast using artificial intelligence.

The project replaces the original presenter with an AI-generated presenter using:

- Voice cloning
- AI presenter animation
- Lip synchronization
- Video editing

---

# Demo Video

Watch the final AI news broadcast:

https://youtube.com/4kXmf8omRt8

---

# Project Pipeline

Original News Broadcast  ![pipeline_diagram](https://github.com/user-attachments/assets/f85e0843-b56b-4ab7-95d9-c671bc2fb497)

↓  
Extract Script  
↓  
Extract Presenter Voice  
↓  
Clean Audio  
↓  
Clone Voice (ElevenLabs)  
↓  
Generate Narration  
↓  
Prepare Presenter Image  
↓  
Animate Presenter (HeyGen)  
↓  
Lip Sync  
↓  
Import into Lightworks  
↓  
Replace Original Presenter  
↓  
Insert News Elements  
↓  
Export Final Broadcast

---

# Tools Used

| Tool | Purpose |
|-----|------|
| YouTube Downloader | Download news broadcast |
| UVR | Extract presenter voice |
| Audacity | Clean audio |
| ElevenLabs | Voice cloning |
| Leonardo AI | Image enhancement |
| HeyGen | Presenter animation |
| Lightworks | Video editing |

More details in:

- pipeline.md

- tools.md


