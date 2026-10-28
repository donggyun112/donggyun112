## Research notes

[AI Research Knowledge Base](https://donggyun112.github.io/knowledge-base/) — Notes on agents, retrieval, inference, and memory experiments.

[Threads @dong_kseo](https://www.threads.com/@dong_kseo) — Writing about AI agents and development.

## Landed contributions

### [Google ADK](https://github.com/google/adk-python)

- [#7558](https://github.com/google/adk-python/pull/7558): Prevent truncated Claude tool calls from executing when token or context-window limits are reached, in streaming and non-streaming responses. Landed via Copybara: [b9d2bc3](https://github.com/google/adk-python/commit/b9d2bc3d95487ecc4a437b813f9b8fa634e1be54).
- [#7367](https://github.com/google/adk-python/pull/7367): Prevent LiteLlm from executing tool calls quoted in answer text. Landed via Copybara: [6b00a38](https://github.com/google/adk-python/commit/6b00a38901e7181801f645e5890da54aa322b6dc).
- [#7513](https://github.com/google/adk-python/pull/7513): Prevent deleted SQLite session events from reappearing when a session ID is reused. Landed via Copybara: [3b2b949](https://github.com/google/adk-python/commit/3b2b949c4b0b2a063b01e838d0fdde4aa93336d7).
- [#7426](https://github.com/google/adk-python/pull/7426): Preserve floating-point precision in SQLite session state. Landed via Copybara: [13787a5](https://github.com/google/adk-python/commit/13787a5bd43fcc7306f5b14dc87ff633bd6e7ea2).
- [#7327](https://github.com/google/adk-python/pull/7327): Fix async database dependencies and improve missing-dependency errors. Landed via Copybara: [ffc2494](https://github.com/google/adk-python/commit/ffc2494a656d4fdaaec1c930d1124bba339a3cfd).
- [#6830](https://github.com/google/adk-python/pull/6830): Honor the live audio transcription opt-out. Landed via Copybara: [c0f92f8](https://github.com/google/adk-python/commit/c0f92f8964eff431eca46234fe3d83bd2a67bde1).

### [OpenMausBot](https://github.com/milind-soni/OpenMausBot)

- [#354](https://github.com/milind-soni/OpenMausBot/pull/354): Preserve assistant-text ordering around tool events in ACP, Pi, and Box drivers. Landed via [#382](https://github.com/milind-soni/OpenMausBot/pull/382) · commit [8717716](https://github.com/milind-soni/OpenMausBot/commit/871771651e5fa9e585a8ec5da8d36cf57759c1b8).
- [#356](https://github.com/milind-soni/OpenMausBot/pull/356): Keep queued messages out of the active transcript until the current turn finishes. Landed via [#387](https://github.com/milind-soni/OpenMausBot/pull/387) · commit [0353c0e](https://github.com/milind-soni/OpenMausBot/commit/0353c0e0b0e04353cc4e49680e33b16ad3b20034).

### [RHWP](https://github.com/edwardkim/rhwp)

- [#2386](https://github.com/edwardkim/rhwp/pull/2386): Preserve section-start markers when inserting the first paragraph, preventing an extra blank page. Merge commit: [0f8c617](https://github.com/edwardkim/rhwp/commit/0f8c6173c421323fe98371fb646fc2f6bdce78b5).
- [#2388](https://github.com/edwardkim/rhwp/pull/2388): Generate preview text for template-created HWP documents while preserving existing previews. Merge commit: [010705e](https://github.com/edwardkim/rhwp/commit/010705e016104a5b4184d51266bb75e50db6eb8c).
- [#7978](https://github.com/edwardkim/rhwp/pull/7978): Fix cursor positions and undo/redo for supplementary Unicode characters in headers, footers, and footnotes. Landed via [#7997](https://github.com/edwardkim/rhwp/pull/7997) · commit [8766fb4](https://github.com/edwardkim/rhwp/commit/8766fb47d8ec11547f0d2ae941c53cc3c9780ab2).
- [#7985](https://github.com/edwardkim/rhwp/pull/7985): Reject unsupported cross-section selection edits before mutation, preserving document content and undo/redo history. Landed via [#7997](https://github.com/edwardkim/rhwp/pull/7997) · commit [8766fb4](https://github.com/edwardkim/rhwp/commit/8766fb47d8ec11547f0d2ae941c53cc3c9780ab2).
- [#7988](https://github.com/edwardkim/rhwp/pull/7988): Use original-text match lengths in case-insensitive replacement to preserve surrounding Unicode text. Landed via [#7997](https://github.com/edwardkim/rhwp/pull/7997) · commit [8766fb4](https://github.com/edwardkim/rhwp/commit/8766fb47d8ec11547f0d2ae941c53cc3c9780ab2).
- [#8000](https://github.com/edwardkim/rhwp/pull/8000): Prevent overlapping search matches from deleting trailing text during replacement. Landed via [#8004](https://github.com/edwardkim/rhwp/pull/8004) · commit [6ed1682](https://github.com/edwardkim/rhwp/commit/6ed1682c3267ea786734eb2e75252916a861d1fd).
- [#8002](https://github.com/edwardkim/rhwp/pull/8002): Normalize CRLF/CR editing input to prevent text loss when saving HWP documents. Landed via [#8004](https://github.com/edwardkim/rhwp/pull/8004) · commit [6ed1682](https://github.com/edwardkim/rhwp/commit/6ed1682c3267ea786734eb2e75252916a861d1fd).

### [MCP ecosystem](https://github.com/punkpeye/awesome-mcp-servers)

- [awesome-mcp-servers #8725](https://github.com/punkpeye/awesome-mcp-servers/pull/8725): Add Keymem, an associative key-graph memory MCP server, to the Knowledge & Memory directory. Merge commit: [6a34971](https://github.com/punkpeye/awesome-mcp-servers/commit/6a349711eb16dd66b2bb420e59bee1bc0110e5fc).
