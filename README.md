# youtube_maker

Local tooling for evidence-based health YouTube production.

## Agent skills

### ffmpeg-skill

Local FFmpeg video editor for Cursor agents (42 tools, no cloud / API keys).

Installed at [`.cursor/skills/ffmpeg-skill/`](.cursor/skills/ffmpeg-skill/) via:

```bash
npx --yes ffmpeg-skill --dir .cursor/skills
```

Verify:

```bash
npx --yes ffmpeg-skill doctor
python3 .cursor/skills/ffmpeg-skill/scripts/probe.py <file.mp4> --compact
```

Requires `ffmpeg` 6.1+ and `python3` 3.10+ on `PATH`. Upstream: [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill).
