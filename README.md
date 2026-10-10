# GameMasterKyle short link

Compatibility entry that forwards existing links to the GameMasterKyle links page.

[Open the public experience](https://jonathankhobson.github.io/gm/links.html).

## Maintenance

index.html owns the JavaScript, meta-refresh, canonical and fallback destinations. This repository is an active compatibility route. Keep all four targets consistent. The current redirect uses a fixed destination; it does not preserve incoming query strings or fragments. Review incoming-link requirements before changing that behavior.

See [AGENTS.md](AGENTS.md) for change and verification boundaries. Report reproducible problems through this repository’s Issues, including the affected public URL. Do not include private records or credentials.

## Site publication

This repository remains the short-link source. Its public route forwards to the native GameMasterKyle links page while `_legacy=1` keeps this original GitHub Pages shortcut available.

[Open the current public experience](https://gamemaster-kyle.jkylehobson.chatgpt.site/links.html).
