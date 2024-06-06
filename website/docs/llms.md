---
title: Connecting to LLMs
nav_order: 40
has_children: true
---

# Aider can connect to most LLMs
{: .no_toc }

[![connecting to many LLMs](/assets/llms.jpg)](https://aider.chat/assets/llms.jpg)

## Best models
{: .no_toc }

**Aider works best with [GPT-4o](/docs/llms/openai.html) and
[Claude 3 Opus](/docs/llms/anthropic.html),**
as they are the very best models for editing code.

## Free models
{: .no_toc }

Aider works with a number of **free** API providers:

- Google's [Gemini 1.5 Pro](/docs/llms/gemini.html) is the most capable free model to use with aider, with
code editing capabilities similar to GPT-3.5.
- You can use [Llama 3 70B on Groq](/docs/llms/groq.html) which is comparable to GPT-3.5 in code editing performance.
- The [Deepseek Chat v2](/docs/llms/deepseek.html) model work well with aider, better than GPT-3.5. Deepseek currently offers 5M free tokens of API usage.
- Cohere also offers free API access to their [Command-R+ model](/docs/llms/cohere.html), which works with aider as a *very basic* coding assistant.

## Local models
{: .no_toc }

Aider can work also with local models, for example using [Ollama](/docs/llms/ollama.html).
It can also access
local models that provide an
[Open AI compatible API](/docs/llms/openai-compat.html).

## Use a capable model
{: .no_toc }

Check
[Aider's LLM leaderboards](/docs/llms/https://aider.chat/docs/leaderboards/)
to see which models work best with aider.

Be aware that aider may not work well with less capable models.
If you see the model returning code, but aider isn't able to edit your files
and commit the changes...
this is usually because the model isn't capable of properly
returning "code edits".
Models weaker than GPT 3.5 may have problems working well with aider.
