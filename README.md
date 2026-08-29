# assets

Public static assets for makke.net projects — UI sounds, push icons.

## Files

| File | Type | Usage |
|---|---|---|
| `audio/dsh-plick.m4a` | sound | DSH notification plick (default) |
| `audio/dsh-plick-fast.m4a` | sound | fast variant |
| `audio/dsh-plick-low.m4a` | sound | low-pitch variant |
| `audio/dsh-plick-fast.caf` | sound | Core Audio format (macOS `afplay`) |
| `icons/dsh-whale-300.png` | icon | DSH whale, 300px |

## Hotlinking

GitHub raw works, but for production use prefer jsDelivr (CDN-cached):

```
https://cdn.jsdelivr.net/gh/theorangee-makke/assets@main/audio/dsh-plick.m4a
https://cdn.jsdelivr.net/gh/theorangee-makke/assets@main/icons/dsh-whale-300.png
```

Pin a tag instead of `@main` for immutable URLs.

## License

CC0 1.0 — free to use, no attribution required.
