# Stickers Library

A curated collection of expressive WebP stickers for messaging, social media, and content creation.

##  Stickers

| # | Title | Category | File |
|---|-------|----------|------|
| 1 | Angry GF Beating | Reaction | `1.angrygf_Beating-Girl.webp` |
| 2 | Bro Slap | Funny | `2._broslap-Boy.webp` |
| 3 | Scary Psycho | Reaction | `3.knifeout-scary-psycho-Girl.webp` |
| 4 | Pew Pew Gun | Funny | `4.gunout-hehegun-pewpew-Girl.webp` |

##  JSON Data

All sticker metadata is stored in `stickers.json` with the following structure:

```json
{
  "id": "1",
  "title": "Angry GF Beating",
  "image": "WEBP-Assets/1.angrygf_Beating-Girl.webp",
  "category": "Reaction",
  "subcategories": ["Reaction", "Couple", "Funny"],
  "keywords": ["angry", "girlfriend", "beating", "fight", "reaction", "cute"]
}
```

### Fields

| Field | Description |
|-------|-------------|
| `id` | Unique identifier |
| `title` | Display name |
| `image` | Path to the WebP file |
| `category` | Primary category |
| `subcategories` | Additional groupings |
| `keywords` | Searchable tags |

##  Folder Structure

```
StickersLibrary/
├── README.md
├── stickers.json
└── WEBP-Assets/
    ├── 1.angrygf_Beating-Girl.webp
    ├── 2._broslap-Boy.webp
    ├── 3.knifeout-scary-psycho-Girl.webp
    └── 4.gunout-hehegun-pewpew-Girl.webp
```

##  Format

All sticker images are in **WebP** format for optimal compression and quality.
