# YEAH·BUOY

A 3D-printed electric thruster for kayaks, inflatables, and jon boats. Paddle-assist, not a speed record. Built to be repaired in the field.

**Live site:** https://billthorpe522.github.io/yeah-buoy/

## What's in this repo

```
yeah-buoy/
├── index.html                       # the one-shot landing page
├── README.md
├── .gitignore
└── assets/
    ├── photos/                      # source photos (9, web-optimized)
    ├── brand/
    │   ├── wordmark.svg             # "YEAH · BUOY" full wordmark
    │   ├── favicon.svg              # square buoy mark
    │   └── palette.json             # color tokens
    ├── social/
    │   ├── og-card.png              # 1200×630 link preview
    │   └── hero-poster.png          # 1080×1350 IG portrait
    └── print/
        └── sticker-round.svg        # printable round sticker
```

## Specs (from v1 hardware)

| | |
|---|---|
| **Battery** | 12.8V 22Ah LiFePO4 deep cycle, 30A BMS |
| **Motor** | Any 4S drone motor (2200–2400KV class) |
| **Propeller** | 6-blade ducted, 3D-printed, conformal-coated |
| **Mount** | Velcro strap, tool-free |
| **Control** | Wireless throttle remote (Havcybin-class) |
| **Runtime** | ~3 hours cruise at 2 mph on internal battery |
| **Connectors** | XT60 + ring terminal + waterproof plug |
| **Files** | STLs release on Maker World (TBD) |

## Strategy (from the audio)

The product targets **two buyers with one design**:
1. **Makers** — print it from open-source STLs, source the motor + battery yourself
2. **Buyers** — order a finished unit from Cerealnaut, ready to plug and paddle

Both paths funnel through the same Maker World listing — that's the marketing surface.

## Branding

- **Wordmark:** retro-marine manual style, slab serif + monospace details
- **Palette:** safety orange `#E8612C`, cream `#FAF1DC`, ink `#1A1A1A`, sea `#2A4A5C`
- **Built by:** Send It Studio (Bill Thorpe) for Cerealnaut

## Stack

- Plain HTML + CSS, no build step
- Google Fonts (Roboto Slab + Roboto Mono) for the marine-manual feel
- Single-page, ~25 KB
- GH Pages serves it for free
- Open repo on `Billthorpe522/yeah-buoy` (public for free-tier Pages)

## When STLs land

Regenerate the hero, exploded view, and dimension callouts from the actual CAD. Drop them into `assets/photos/` and update the index.html gallery section. The `Build it` CTA can flip from placeholder to a real Maker World link.

## License

Not yet licensed. STLs will release under a permissive license (CERN-OHL or similar) when published. Site code is unlicensed — clone freely.