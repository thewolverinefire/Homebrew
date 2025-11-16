D&D Homebrew Theme
Version: 1.0.0 Created by TheWolverineFire w/help from Gemini

Welcome, Dungeon Master! This theme is designed to transform your Obsidian vault from a simple note-taking app into a fully-fledged, parchment-style D&D campaign wiki, reminiscent of the 5th Edition Player's Handbook.

It features two modes: a classic Light Mode (parchment and ink) and a high-contrast Dark Mode (dark earth tones) for late-night prep.

⚠️ Important: Font Installation
This theme will not look correct unless you download and install the following two fonts on your operating system (Windows/macOS/Linux):

Bookinsanity: Used for all headers (H1-H6) to give that classic D&D title feel.

Scaly Sans: Used for all mechanical text, stat blocks, and UI elements.

The main body font, Alegreya, is loaded automatically from Google Fonts and does not require installation.

🎨 Core Features
1. The Floating Infobox (Callout)
This is the theme's signature feature. It allows you to place a large, fading image in the right-hand margin of your note, just like an infobox on a wiki.

How to Use: You must place the following callout at the very top of your note, right after the main title.

Markdown

> [!float-right]
> !(path/to/your/image.png)
> *(An optional caption for the image)*
Responsive Behavior:

Desktop: Floats in the right margin.

Tablet/Mobile: Automatically converts to a full-width image that stacks cleanly at the top of the note.

2. Monster Stat Blocks
To create themed D&D 5e-style stat blocks, use the statblock or dnd language identifier for a fenced code block. This will apply the Scaly Sans font and the thematic borders.

Example:

Markdown

```statblock
**Goblin**
*Small humanoid (goblinoid), neutral evil*
---
**Armor Class** 15 (leather armor, shield)
**Hit Points** 7 (2d6)
**Speed** 30 ft.
---
|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|8 (-1)|14 (+2)|10 (+0)|10 (+0)|8 (-1)|8 (-1)|
---
**Skills** Stealth +6
**Senses** darkvision 60 ft.
**Languages** Common, Goblin
**Challenge** 1/4 (50 XP)
---
***Nimble Escape.*** The goblin can take the Disengage or Hide action as a bonus action on each of its turns.
### Actions
**Scimitar.** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.
```
3. Thematic Headers
Headers are styled using Bookinsanity and the D&D Red accent color.

# Header 1 (H1): Styled as a large, red, shadowed title. Use this once at the top of your note.

## Header 2 (H2): A red, small-caps section break with an underline. Perfect for major sections like "History" or "Locations."

### Header 3 (H3): A smaller, red sub-header for subsections.

4. Read-Aloud Text (Blockquotes)
Standard blockquotes are styled to look like the "read-aloud" text boxes found in official adventure modules. Use them to write flavorful descriptions for your players.

Example:

Markdown

> A chill wind blows through the chamber, extinguishing your torches and plunging you into darkness. From the shadows, you hear a low growl.
5. Custom D&D Callouts
This theme provides three custom-colored callouts for specific information:

> [!dnd-lore] (Blue): Used for history, lore, and plot hooks.

> [!dnd-treasure] (Gold): Used for highlighting treasure, gold, and magic items.

> [!dnd-danger] (Green): Used for traps, hazards, and regional effects.

6. Metadata / Properties
The YAML frontmatter block and the new Properties view are both styled to look like a mechanical data block, using the Scaly Sans font and small-caps for all keys.

7. Keyboard Keys
Use the <kbd> HTML tag to create small, themed "button" elements for noting down mechanical actions or keyboard shortcuts.

Example:

Press <kbd>Space</kbd> to continue.

The goblin uses its <kbd>Nimble Escape</kbd> ability.

🧩 Plugin Compatibility
This theme includes custom styling to ensure popular TTRPG plugins match the D&D aesthetic.

Dataview: Dataview tables are styled to match the theme's enhanced table style (using Scaly Sans and themed headers).

TTRPG Statblocks: The official statblock plugin is re-skinned to use Bookinsanity for headers and Alegreya/Scaly Sans for text, matching the theme's fonts.

Obsidian Leaflet: Map controls and pop-ups are styled with parchment colors and red accents.

Calendar: The calendar widget is re-skinned to use Bookinsanity for the title and Scaly Sans for the days.

Kanban: Kanban boards are styled to use parchment/dark earth tones for lanes and cards.

Timelines: Timeline cards are styled to look like bordered callout boxes, fitting the theme.
