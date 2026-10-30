# vectoreyes-prompts

Prompt settings for my Vector eyes in Discord. Edit `vectoreyes-ai.json` to change how he reacts; changes are picked up within about 10 minutes.

| Field | What it does |
|---|---|
| `personality` | Who Vector is. Text, or a list of lines. |
| `rules` | Extra instructions, e.g. `"Get excited whenever someone mentions pizza"`. Text, or a list of lines. |
| `template` | Replaces the whole prompt. Use `{personality}`, `{rules}` and `{moods}` where those should go. |
| `moodDescriptions` | Changes when a mood is used, e.g. `{ "music": "anything about Spotify or concerts" }`. |
| `disabledMoods` | Moods Vector should never use, e.g. `["chaos", "annoyed"]`. |

Moods: happy, laugh, love, excited, proud, sad, hurt, angry, annoyed, scared, surprised, confused, curious, thinking, sleepy, hello, goodbye, sorry, chaos, music, agree, disagree. Fields starting with `_` are notes and are ignored.

Never put API keys in this repo, it's public.
