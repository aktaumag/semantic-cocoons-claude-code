# Semantic Cocoons for Claude Code

Claude Code plugin for designing, auditing, and expanding semantic cocoons: entity-first information architecture, matriarchal internal linking, content briefs, and the "maximum useful coverage" mode.

## Install

In Claude Code, run:

```text
/plugin marketplace add aktaumag/semantic-cocoons-claude-code
/plugin install semantic-cocoons@michael-seo-skills
```

Choose **User scope** to make the plugin available in all Claude Code projects. If Claude Code asks you to reload plugins, run `/reload-plugins`.

## Use

Invoke the plugin explicitly:

```text
/semantic-cocoons:semantic-cocoons Спроектируй максимально полезное покрытие для: ремонт холодильников.
```

The plugin itself applies the rules for topic boundaries, independent cocoons, Target → Mixed → Support, intent separation, internal linking, cannibalization, and stop conditions. You do not need a site, URL, JSON, or a manually prepared keyword list to start.

## Cross-tool compatibility

The skill content follows the Agent Skills format and is also usable in Codex. In Codex, use the same request after invoking `$semantic-cocoons`.
