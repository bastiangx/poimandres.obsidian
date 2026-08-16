# Changelog

---

## [1.0.0] - 15-08-2026
### Added
#### Workspace
- Card layout: floating cards, with pad/tablet mode, active-card highlight, card gap/padding/radius/shadow controls
- Per-split surface routing (left / right / root split backgrounds, incl. transparent) in card mode
- Auto-hide for tab bar, tab title bar, bottom status bar, left ribbon, sidebar header icons & vault profile
- Custom new tab page: obsidian logo, old default, none, or custom image + restore native text buttons
#### Code
- Alternate codeblock themes: Dracula, Solarized light & dark, One Dark (via Style Settings)
- Codeblock token roles mapped to Obsidian 1.13+ semantic classes
#### Callouts & lists
- 4 Border-style callout layouts, selectable globally or per block via `> [!info style-1]`
- Callouts re-render natively through Obsidian 1.4+ `--callout-color`
- Line hover indicator in live preview: accent-colored active line, opt-in list level & codeblock line-number markers
#### Typography
- Style settings now supports Headings customisations
  - fonts, font size, weight, style & color
- Better default color selection for Headings
- 8 heading divider styles with palette selectors
- Horizontal rule style and color selectors
- inline-code now uses theme accent colors
#### UI
- Animation speed multiplier (Style Settings)
- Scrollbar high-contrast mode
- Image & checkbox border-radius sliders
- Selection color & scrollbar color customisation
- Darker backgrounds & surfaces for the main & storm variant themes
- Better contrast for in-editor divider
- Numbered lists now use accent colors
- Bettter inline-code ui contrast
- Bettter codeblock background contrast
### Changed
- Inline code now uses dedicated `--inline-code-*` variables, so alternate codeblock themes never recolor it
- Table width options: fit content / Obsidian default / custom width (`cqw`)
- Alternative task checkboxes (credit: Tokyo Night)

---

## [0.1.1] - 27-09-2025
### Added
- This changelog file.
- simple ci/cd yml for publishing
### Removed
- Assigning font families

<!--Attempts to follow [semantic versioning](https://semver.org)[keepachangelog.com](https://keepachangelog.com)-->
