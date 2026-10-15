> **Educational code and security — updated 15 October 2026**
>
> These examples teach selected concepts and may omit controls required for production. Dependencies and runtimes become outdated over time. Before running or reusing an example, read [SECURITY.md](SECURITY.md), check current advisories, keep dependencies on supported patched versions, and test upgrades. Do not expose development servers or use real customer data or production credentials in a tutorial environment.
>
> Except as separately agreed or required by applicable law, the examples are provided as-is, without warranties. To the maximum extent permitted by applicable law, ByteGrad Sp. z o.o. and the authors disclaim liability for losses arising from use of these examples. Nothing limits mandatory consumer rights or liability that cannot lawfully be excluded. This notice does not change your course purchase agreement or grant rights to third-party assets.

# Lovable AI Video Editor Tutorial

Follow-along resources for ByteGrad's tutorial on building a short-video editor in Lovable and connecting an AI assistant through MCP.

## Downloads

- [Tutorial prompts](prompts.txt) — cleaned-up reusable prompts, organized by step.
- [Download the original demo video](https://github.com/ByteGrad/lovable-ai-video-editor-tutorial/raw/refs/heads/main/morning-routine.mp4) — a 13-second recording with a false start and pauses (about 3.3 MB).
- [Download everything as a ZIP](https://github.com/ByteGrad/lovable-ai-video-editor-tutorial/raw/refs/heads/main/clean-take-follow-along.zip) — prompts, the demo clip and instructions.

## Follow along

1. Create your own project in Lovable.
2. Open `prompts.txt`, use the initial prompt in **Plan mode**, review the plan and build.
3. Connect your own restricted ElevenLabs Speech to Text key through the secure connector or server-only secret field. Genuine word timestamps are needed for precise cuts.
4. Download and upload `morning-routine.mp4`, transcribe it and request AI cut suggestions.
5. Review the suggestions, preview the edited result and export a new MP4. Keep the original file.
6. For the MCP step, publish your own app, use its **Agent Integrations** connection details, and approve access in your chosen assistant. Client settings and labels can differ.

The assistant demo applies cut suggestions already generated in the app. It does not imply that every assistant can transcribe, analyze or export footage through MCP.

## What is included

This repository contains **tutorial resources, not the generated app's source code**. The prompts are cleaned-up versions of the recorded workflow, not a verbatim export of the project conversation. Generated layouts, app names and results may differ between builds.

The ZIP contains `prompts.txt`, `morning-routine.mp4` and a short `README.txt`.

## Safety and costs

- Never paste API keys into public prompts or source files. Restrict your transcription key to Speech to Text, set a small usage cap and use a short expiration for a tutorial.
- Lovable build credits, runtime Cloud/AI usage and ElevenLabs transcription are separate potential costs. This repository does not promise a fixed free allowance or build cost.
- Check suggested cuts and exported playback; AI suggestions still need review.
- Browser-based export creates a new file and requires the tab to remain open.
- Use your own app URL, project IDs and credentials. Do not share private recordings.
- Before allowing other users to consume paid services, add server-side ownership checks, upload limits and usage quotas. Publishing an app is not a complete production security review.

This focused tutorial app is for short clips, not a replacement for a professional editing suite.


## Keeping your generated app maintained

These materials do not include a dependency lockfile or the generated app source. A security review of this repository does not establish that an app generated from the prompts is secure. Review the actual generated source, dependencies, backend access rules and deployed configuration before using real recordings or accepting other users.

Keep your own app on supported, patched dependencies and runtimes, run its dependency/security checks regularly, and test updates. Changes here do not automatically update an existing Lovable project, fork or downloaded ZIP. See [SECURITY.md](SECURITY.md) for practical checks and private reporting. The 15 October 2026 review strengthened the prompts and synchronized the downloadable ZIP; it did not audit or deploy a generated app.
