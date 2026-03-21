# claude-plugins

Claude Code plugin marketplace for video editing, photogrammetry, and media processing MCP servers.

## Plugins

| Plugin | Description |
|--------|-------------|
| [metashape-mcp](https://github.com/jenkinsm13/metashape-mcp) | Agisoft Metashape 2.3+ — 9 photogrammetry skills + MCP tools |
| [resolve-mcp](https://github.com/jenkinsm13/resolve-mcp) | DaVinci Resolve — 15 editing skills + 295 MCP tools + 3 agents |
| [resolve-assistant](https://github.com/jenkinsm13/resolve-assistant) | AI video editing assistant (Gemini + Resolve) |
| [ollama-mcp](https://github.com/jenkinsm13/ollama-mcp) | Local Ollama LLM inference |
| [exiftool-mcp](https://github.com/jenkinsm13/exiftool-mcp) | Image/video metadata via ExifTool |
| [ffmpeg-mcp](https://github.com/jenkinsm13/ffmpeg-mcp) | Video/audio processing via FFmpeg |
| [imagemagick-mcp](https://github.com/jenkinsm13/imagemagick-mcp) | Image processing via ImageMagick |

## Installation

```bash
# Add marketplace
claude plugin marketplace add jenkinsm13/claude-plugins

# Install individual plugins
claude plugin install metashape-mcp@jenkinsm13-plugins
claude plugin install resolve-mcp@jenkinsm13-plugins
claude plugin install resolve-assistant@jenkinsm13-plugins
claude plugin install ollama-mcp@jenkinsm13-plugins
claude plugin install exiftool-mcp@jenkinsm13-plugins
claude plugin install ffmpeg-mcp@jenkinsm13-plugins
claude plugin install imagemagick-mcp@jenkinsm13-plugins
```

Each plugin bundles both the MCP server (tools) and skills. No separate `claude mcp add` needed.
