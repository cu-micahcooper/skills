# Sounds Like a Skill Issue

A self-contained, interactive slide presentation for a non-technical, in-person audience.

The 16-slide deck introduces plugins, skills, and apps with a backpack, guide, and radio analogy. It covers Custom GPT comparisons, skill portability, stacking, and supported usage environments, with a live-demo placeholder for creation and sharing. Product guidance was checked on October 9, 2026.

## Presenting

Present directly from **https://cu-micahcooper.github.io/skills/**, or open `presentation/chatgpt-plugins-skills.html` in a browser. No installation is required. The University’s Minion Pro and Myriad Pro fonts load from Adobe Fonts; slides and activities also work offline with fallback fonts. Official documentation links are in the presenter notes and require internet access.

- Use Next or the right arrow to reveal the next idea, then advance. Previous or the left arrow reverses the builds.
- Use the slide menu to jump to a topic.
- Select **Presenter view** to open separate notes and navigation on your own screen.
- Select **Full screen** or press **F** for projection.
- Press **N** to toggle notes in the slide window.
- Use **Print** for a static copy, including the official guides on the last page.

The presenter controls the activities while the audience responds aloud or discusses prompts. Activities run locally and make no AI calls.

## Files

- `presentation/chatgpt-plugins-skills.html`: slides, embedded illustrations, interactions, speaker notes, and source links.

The slides use concepts and illustrations adapted from the supplied `chatgpt-extensibility.html` field guide.

The closing activity offers four starting points, followed by audience questions and a closing QR slide. The cover and final slide carry custom QR codes to the live deck. Navigation controls are hidden on the final slide; the left arrow and presenter window remain available. Press **N** on the final slide to read the official guides. Full screen hides the header tools. Revealed content stays at full contrast for projection.

GitHub Pages publishes the self-contained deck from `main` using `.github/workflows/pages.yml`.

The halftone backpack QR uses the image-dithering and protected module-center technique from [QRFrame’s Halftone preset](https://github.com/zhengkyl/qrframe/blob/main/presets/Halftone.js).

The capabilities and scripts slides use practical examples, including processing exam results with a packaged script.

The retirement timeline uses the current English [OpenAI retirement FAQ](https://help.openai.com/en/articles/20001519-custom-gpt-retirement-and-migration-faq), checked October 12, 2026. Migration target dates, the planned creation cutoff, and standard retirement are labeled separately. Seven starting points appear immediately before the demo: an existing chat, a task description and materials, a recording, a Custom GPT, Codex with Superpowers, an existing skill, or manually written files.
