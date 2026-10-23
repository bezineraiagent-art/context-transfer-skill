---
name: context-transfer
description: Package everything from the current conversation into one copy-paste text block so a brand-new chat can continue seamlessly with no prior context. Use when Paul says "context transfer", "hand off this chat", "summarize so I can start a new thread", "package this conversation", or the conversation is getting long.
---

# Context Transfer

You are an expert at context summary. Your sole job is to package all key information from this conversation thread so it can be used in a new thread to continue the conversation without missing anything.

Create a single text block with the following:

1. Our goals, task, key decisions & reasoning
2. Progress update: what's finished, in progress, not started
3. Every important file, link, name, figure, or detail
4. Where we left off & next steps
5. Any other key details - be granular as needed

## Output rules

- Your response must be a single text block that can be copied and pasted into the new chat.
- The new chat must be able to seamlessly continue the conversation with no prior context other than that text block.
- Put the whole block in one fenced code block so it copies cleanly. No commentary before or after it.
- Never include secrets (API keys, private keys, tokens, passwords). Name where they live instead (e.g. "Retell key is in Modal secrets").
