## Landed contributions

### Google ADK

- [#7513](https://github.com/google/adk-python/pull/7513): Prevent deleted SQLite session events from reappearing when a session ID is reused.
- [#7426](https://github.com/google/adk-python/pull/7426): Preserve floating-point precision in SQLite session state.
- [#7327](https://github.com/google/adk-python/pull/7327): Fix async database dependencies and improve missing-dependency errors.
- [#6830](https://github.com/google/adk-python/pull/6830): Honor the live audio transcription opt-out.

### OpenMausBot

- [#354](https://github.com/milind-soni/OpenMausBot/pull/354): Preserve assistant-text ordering around tool events in ACP, Pi, and Box drivers. Landed via [#382](https://github.com/milind-soni/OpenMausBot/pull/382).
- [#356](https://github.com/milind-soni/OpenMausBot/pull/356): Keep queued messages out of the active transcript until the current turn finishes. Landed via [#387](https://github.com/milind-soni/OpenMausBot/pull/387).

### RHWP

- [#2386](https://github.com/edwardkim/rhwp/pull/2386): Preserve section-start markers when inserting the first paragraph, preventing an extra blank page.
- [#2388](https://github.com/edwardkim/rhwp/pull/2388): Generate preview text for template-created HWP documents while preserving existing previews.

### MCP ecosystem

- [awesome-mcp-servers #8725](https://github.com/punkpeye/awesome-mcp-servers/pull/8725): Add Keymem, an associative key-graph memory MCP server, to the Knowledge & Memory directory.

## Open PRs and technical discussions

- **Google ADK · open PR:** [#7367](https://github.com/google/adk-python/pull/7367) proposes a fix to prevent LiteLLM from executing tool calls quoted in answer text.
- **LangGraph · open bug reports:** Diagnose [falsy runtime context values](https://github.com/langchain-ai/langgraph/issues/8406), [async subscription shutdown](https://github.com/langchain-ai/langgraph/issues/8429), and [async tool concurrency](https://github.com/langchain-ai/langgraph/issues/8517) with minimal reproductions and proposed fixes.
- **Pydantic AI · design discussion:** Contribute [durable replay design feedback](https://github.com/pydantic/pydantic-ai/issues/7971#issuecomment-5524973741) on queued-message deduplication, event identity, and persist-before-delivery ordering.
