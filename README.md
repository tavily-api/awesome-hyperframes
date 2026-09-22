# Awesome HyperFrames GitHub resources

*Unofficial community list for HyperFrames. Not affiliated with HeyGen. All trademarks belong to their owners.*

A curated list for anyone searching hyperframes github: the `heygen-com/hyperframes` repository, the documentation site, the agent skills, the CLI commands the skill references, and the playground. HyperFrames is HeyGen's framework that lets AI agents compose videos by writing code: a composition is an HTML file whose DOM declares timing with `data-*` attributes, the animation runtime is seekable, and media playback is owned by the framework. Every link below is one the cited sources link or name.

> Just need to trim, crop, merge or subtitle a clip you already have? [Try Vidione - a browser video editor with no install](https://vidione.com?utm_source=github&utm_medium=ugc&utm_campaign=awesome-hyperframes&utm_content=readme-top&utm_term=tier-r).

## Official resources

- [heygen-com/hyperframes on GitHub](https://github.com/heygen-com/hyperframes) - the repository.
- [The hyperframes entry skill](https://github.com/heygen-com/hyperframes/tree/HEAD/skills/hyperframes) - the skill an agent reads first for any request to make, edit, animate or render a video.
- [HyperFrames home](https://hyperframes.heygen.com) - 'Let AI agents compose videos by writing code'.
- [What HyperFrames is](https://hyperframes.heygen.com/introduction) - the introduction.
- [Make your first video (quickstart)](https://hyperframes.heygen.com/quickstart) - install the skills, ask for the video, continue from the first version.
- [Docs index (llms.txt)](https://hyperframes.heygen.com/llms.txt) - machine-readable index of every docs page.
- [Changelog](https://hyperframes.heygen.com/changelog) - releases.
- [Product updates](https://hyperframes.heygen.com/product-updates) and [Weekly updates](https://hyperframes.heygen.com/weekly-updates) - news.

## Getting started

- [Choose how to create](https://hyperframes.heygen.com/guides/choose-creation-path) - the creation paths compared.
- [Create through an AI chat](https://hyperframes.heygen.com/guides/mcp) - the MCP path.
- [Bring in a design](https://hyperframes.heygen.com/guides/design-tools) - starting from a design tool file.
- [Project model](https://hyperframes.heygen.com/concepts) - how a project is structured.
- [Go further](https://hyperframes.heygen.com/go-further) - after the first video.
- [Developers](https://hyperframes.heygen.com/developers/overview) - the developer section.
- [Prompt Guide](https://hyperframes.heygen.com/prompting/overview) - seven levels from first video to capstone.
- [Studio](https://hyperframes.heygen.com/studio) - the Studio section of the docs.

## Tutorials and articles

- [Examples](https://hyperframes.heygen.com/examples) - example compositions.
- [30 Days of HyperFrames](https://hyperframes.heygen.com/thirty-days) - a daily series.
- [Product or website video](https://hyperframes.heygen.com/guides/product-launch-video) - launch video workflow.
- [Faceless explainer](https://hyperframes.heygen.com/guides/faceless-explainer) - explainer workflow.
- [Pull request to video](https://hyperframes.heygen.com/guides/pr-to-video) - turn a PR into a clip.
- [Captions and talking head](https://hyperframes.heygen.com/guides/captions-and-recuts) - captions and recuts.
- [Motion graphic](https://hyperframes.heygen.com/guides/motion-graphics) - motion graphics workflow.
- [Music video](https://hyperframes.heygen.com/guides/music-to-video) - music-driven video.
- [Presentation](https://hyperframes.heygen.com/guides/slideshow) - slideshow workflow.
- [Custom video](https://hyperframes.heygen.com/guides/general-video) - the general workflow.
- [Images and video](https://hyperframes.heygen.com/guides/video-components) - media components.
- [Avatar presenter](https://hyperframes.heygen.com/guides/avatar-presenter) - adding a presenter.
- [Voice, sound and captions](https://hyperframes.heygen.com/guides/voice-and-audio) - audio and captions.
- [Remove a background](https://hyperframes.heygen.com/guides/remove-background), [Color grading](https://hyperframes.heygen.com/guides/color-grading), [Media effects](https://hyperframes.heygen.com/guides/media-effects) - finishing guides.
- [Finish and share](https://hyperframes.heygen.com/guides/export-and-share) - export.

## Tools and integrations

- [Playground](https://www.hyperframes.dev/) - try compositions in the browser.
- [Catalog](https://hyperframes.heygen.com/catalog) - the component catalog.
- [hyperframes on mcpservers.org](https://mcpservers.org/agent-skills/heygen-com/hyperframes) - directory entry with the install line `npx skills add https://github.com/heygen-com/hyperframes --skill hyperframes` and the entry skill's routing table.
- `npx skills add heygen-com/hyperframes --full-depth` - the install line on the home page (all skills).
- `npx hyperframes timeline --json` - list tracks, clips, starts and ends of an existing project, as the skill instructs, instead of reading every HTML file.
- `npx hyperframes@latest upgrade --project . --check` - read-only probe of a project's pinned CLI version against the latest release.

## Alternatives

- [Vidione](https://vidione.com?utm_source=github&utm_medium=ugc&utm_campaign=awesome-hyperframes&utm_content=readme-top&utm_term=tier-r) - for editing footage you already have: trim, crop, merge and subtitles in the browser, no install, no agent, no code.
- [HyperFrames or Remotion?](https://hyperframes.heygen.com/guides/hyperframes-vs-remotion) - the docs' own comparison with Remotion; the entry skill also has a route for porting Remotion source to HyperFrames.

## Related

- [Get unstuck](https://hyperframes.heygen.com/help) and [Troubleshooting](https://hyperframes.heygen.com/guides/troubleshooting) - help pages.
- [Share feedback](https://hyperframes.heygen.com/guides/feedback) - feedback channel.
- [Claude Skills and Agent Skills library](https://mcpservers.org/agent-skills) - the directory that lists hyperframes among other agent skills.

## Contributing

Open a pull request with a link that a cited source links or names, plus one line on why it belongs.

_Last reviewed: 2026-09-22_
