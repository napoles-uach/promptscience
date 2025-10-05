
# 🎙️ Prompt Science — A Community-Audited AI & Science Podcast

**Prompt Science** is an open project exploring how large language models (LLMs) and humans can co-create trustworthy, verifiable scientific communication.  
Each episode covers **recent advances in AI applied to science**, generated with language models, human-edited, and published openly with transcripts, audio, and version history.

> _“A transparent dialogue between humans and machines — for science.”_

---

## 🌍 Website

📡 **Live site:** [https://your-username.github.io/prompt-science/](https://your-username.github.io/prompt-science/)  
🎧 **RSS Feed:** [https://your-username.github.io/prompt-science/feeds/podcast.rss](https://your-username.github.io/prompt-science/feeds/podcast.rss)

---

## 🧩 Repository Structure

```
prompt-science/
├── index.html                # Main website for podcast and info
├── episodes/
│   ├── promptscienceE1.mp3   # Audio file (episode 1)
│   ├── promptscienceE1.md    # Transcript in Markdown
│   └── episodes.json         # List of available episodes (loaded dynamically)
└── feeds/
    └── podcast.rss           # RSS feed for podcast directories
```

---

## 🪶 How It Works

1. **Sourcing** — We track trending research (Nature, Science, arXiv, institutional blogs).  
2. **Generation** — LLMs draft a narrative under human supervision.  
3. **Verification** — Contributors review facts, add references, and flag potential hallucinations.  
4. **Publication** — The verified script is converted to speech and released via GitHub Pages and RSS.  

Each episode includes:
- 🎧 MP3 audio  
- 📝 Markdown transcript  
- 🔗 Verified references  
- 📅 Metadata in `episodes.json`

---

## 🤝 Contributing

We welcome contributions from researchers, students, and enthusiasts who want to help make science podcasts more accurate, open, and traceable.

### 🧠 Ways to contribute
- **Fact-check or add sources**: Edit transcripts (`.md` files) and submit pull requests.  
- **Improve writing or clarity**: Fix grammar or structure while keeping the scientific meaning intact.  
- **Add new episodes**: Propose new topics or upload your own AI+Science scripts.  
- **Enhance the website**: Improve layout, accessibility, or episode rendering.

### 🧾 Steps

1. **Fork** the repository.  
2. **Create a branch**:
   ```bash
   git checkout -b add-episode2
   ```
3. **Edit or add files** under `/episodes`:
   - MP3 audio  
   - `.md` transcript  
   - Add entry in `episodes/episodes.json`
4. **Commit and push**:
   ```bash
   git commit -am "Add Episode 2 on AI in Climate Modeling"
   git push origin add-episode2
   ```
5. **Open a Pull Request** describing your change.

---

## 🧰 Episode JSON Format

Each episode entry in `episodes/episodes.json` looks like this:

```json
{
  "id": "2025-10-05-navier-stokes",
  "title": "Special: DeepMind, Navier–Stokes, and the Millennium Problem",
  "date": "2025-10-05",
  "duration": "11:45",
  "audio": "episodes/promptscienceE1.mp3",
  "transcript": "episodes/promptscienceE1.md",
  "description": "How AI-assisted mathematics is exploring one of the hardest open problems in fluid dynamics."
}
```

---

## 🧮 Fact-Checking Guidelines

Before submitting, please ensure:
- 🧾 **Citations**: Include reliable references (DOI, Nature/Science/arXiv links).  
- 📆 **Dates & authors**: Confirm accuracy of publication data.  
- 🔢 **Numbers & results**: Avoid quoting unverified values from model output.  
- 🤖 **AI transparency**: Mention which model was used to draft the text.

---

## 💡 License

- Text and audio are licensed under **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)**.  
- You may remix or reuse content with attribution.  
- Please keep all AI contributions and human edits transparent in your commits or PR descriptions.

---

## 🌟 Credits

Created and maintained by the **Prompt Science** community.  
Contributions are reviewed collaboratively to ensure transparency, accuracy, and open scientific dialogue.

---

_“Prompt Science — where AI meets scientific curiosity.”_
