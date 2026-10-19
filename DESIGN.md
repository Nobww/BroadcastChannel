---
version: alpha
name: BroadcastChannel Base and theme overrides
description: "The complete BroadcastChannel Base theme, its limited Bear CSS compatibility surface, and its optional Sepia, Aria, Terminal, HN News, TG Channel, ZAE, Polar, Editorial, Warm Orange, Minimal Store, Midnight, Vivid Dashboard, and Black Gold overrides."
colors:
  primary: "#3a52c7"
  base-light-background: "#fbfbfc"
  base-light-heading: "#14161b"
  base-light-text: "#3b414c"
  base-light-visited: "#6a4fbf"
  base-light-code-background: "#f2f3f6"
  base-light-code-text: "#232830"
  base-light-blockquote: "#2b303a"
  base-light-rule: "rgba(59, 65, 76, 0.12)"
  base-light-border: "rgba(59, 65, 76, 0.2)"
  base-dark-background: "#0e1116"
  base-dark-heading: "#eceff4"
  base-dark-text: "#b9c0cc"
  base-dark-link: "#9db0ff"
  base-dark-visited: "#c0a8f5"
  base-dark-code-background: "#070a0e"
  base-dark-code-text: "#d6dbe4"
  base-dark-blockquote: "#cfd5df"
  base-dark-rule: "rgba(185, 192, 204, 0.12)"
  base-dark-border: "rgba(185, 192, 204, 0.2)"
  sepia-background: "#f4f1ec"
  sepia-heading: "#333"
  sepia-text: "#181513"
  sepia-link: "#5a6570"
  sepia-visited: "#725f82"
  sepia-code-background: "#f9f9f9"
  sepia-code-text: "#24201d"
  sepia-blockquote: "#333"
  sepia-accent: "#b23b00"
  sepia-line: "rgba(0, 0, 0, 0.07)"
  sepia-link-hover: "#3f4850"
  sepia-muted: "#706862"
  sepia-surface: "#fff"
typography:
  base-body:
    fontFamily: "Verdana, sans-serif"
    fontSize: 1em
    lineHeight: 1.5
  base-main:
    fontFamily: "Verdana, sans-serif"
    fontSize: 1em
    lineHeight: 1.6
  base-heading:
    fontFamily: "Verdana, sans-serif"
    lineHeight: 1.25
  base-site-title:
    fontFamily: "Verdana, sans-serif"
    fontSize: 1.5em
    lineHeight: 1.25
    letterSpacing: -0.012em
  sepia-body:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
    fontSize: 1em
    lineHeight: 1.5
  sepia-site-title:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
    fontSize: 1.25rem
    fontWeight: 600
    lineHeight: 1.25
rounded:
  base-panel: 4px
  base-chip: 4px
  base-media: 8px
  sepia-panel: 3px
  sepia-chip: 4px
  sepia-media: 8px
  reaction-pill: 999px
spacing:
  content-width: 800px
  base-body-padding: 20px
  sepia-body-padding: 1.25rem
  base-main-padding-top: 2rem
  sepia-main-padding-top: 1.75rem
  main-padding-bottom: 1rem
  base-feed-entry-separation: 3rem
  small-breakpoint: 37.5rem
components:
  base-page:
    backgroundColor: "{colors.base-light-background}"
    textColor: "{colors.base-light-text}"
    typography: "{typography.base-body}"
    padding: "{spacing.base-body-padding}"
    width: "{spacing.content-width}"
  base-page-dark:
    backgroundColor: "{colors.base-dark-background}"
    textColor: "{colors.base-dark-text}"
  base-main:
    typography: "{typography.base-main}"
  base-heading:
    textColor: "{colors.base-light-heading}"
    typography: "{typography.base-heading}"
  base-heading-dark:
    textColor: "{colors.base-dark-heading}"
  base-site-title:
    typography: "{typography.base-site-title}"
  base-link:
    textColor: "{colors.primary}"
  base-link-visited:
    textColor: "{colors.base-light-visited}"
  base-link-dark:
    textColor: "{colors.base-dark-link}"
  base-link-visited-dark:
    textColor: "{colors.base-dark-visited}"
  base-code:
    backgroundColor: "{colors.base-light-code-background}"
    textColor: "{colors.base-light-code-text}"
  base-code-dark:
    backgroundColor: "{colors.base-dark-code-background}"
    textColor: "{colors.base-dark-code-text}"
  base-blockquote:
    textColor: "{colors.base-light-blockquote}"
  base-blockquote-dark:
    textColor: "{colors.base-dark-blockquote}"
  base-masthead:
    borderBottom: "1px solid {colors.base-light-rule}"
    paddingBottom: 1.15rem
  base-masthead-dark:
    borderBottom: "1px solid {colors.base-dark-rule}"
  base-feed-entry:
    borderBottom: "1px solid {colors.base-light-rule}"
    separation: "{spacing.base-feed-entry-separation}"
  base-footer:
    borderTop: "1px solid {colors.base-light-rule}"
  base-search:
    rounded: "{rounded.base-panel}"
    border: "1px solid {colors.base-light-border}"
  base-pagination:
    rounded: "{rounded.base-panel}"
    border: "1px solid {colors.base-light-border}"
  base-tag-chip:
    rounded: "{rounded.base-chip}"
    border: "1px solid {colors.base-light-rule}"
  base-media:
    rounded: "{rounded.base-media}"
  sepia-page:
    backgroundColor: "{colors.sepia-background}"
    textColor: "{colors.sepia-text}"
    typography: "{typography.sepia-body}"
    padding: "{spacing.sepia-body-padding}"
    width: "{spacing.content-width}"
  sepia-heading:
    textColor: "{colors.sepia-heading}"
  sepia-site-title:
    textColor: "{colors.sepia-heading}"
    typography: "{typography.sepia-site-title}"
  sepia-link:
    textColor: "{colors.sepia-link}"
  sepia-link-visited:
    textColor: "{colors.sepia-visited}"
  sepia-link-hover:
    textColor: "{colors.sepia-link-hover}"
  sepia-code:
    backgroundColor: "{colors.sepia-code-background}"
    textColor: "{colors.sepia-code-text}"
  sepia-blockquote:
    textColor: "{colors.sepia-blockquote}"
  sepia-timeline-dot:
    backgroundColor: "{colors.sepia-accent}"
  sepia-muted-text:
    textColor: "{colors.sepia-muted}"
  sepia-surface:
    backgroundColor: "{colors.sepia-surface}"
  sepia-panel:
    rounded: "{rounded.sepia-panel}"
  sepia-tag:
    rounded: "{rounded.sepia-chip}"
  sepia-media:
    rounded: "{rounded.sepia-media}"
  reaction-paid:
    rounded: "{rounded.reaction-pill}"
---

# BroadcastChannel Design System

## Overview

BroadcastChannel ships one complete default theme, **Base**. It is a single-column, content-first BroadcastChannel design with modest type, direct links, restrained controls, and no card-based application shell. Its limited Bear CSS compatibility surface reuses Bear's variable names, typography variables, `--width` content-width semantics, and selected shell hooks; the palette itself is project-owned. The feed and content DOM, routes, and product behavior remain BroadcastChannel-specific.

Sixteen optional, independently implemented overrides cascade over Base without changing the content model. **Sepia** (`/themes/sepia.css`) is fixed-light warm paper; **Aria** (`/themes/aria.css`) is neutral system-sans and follows the system light/dark preference; the **Terminal** family is fixed-dark, square, and monospace, with Amber, Green, Cyan, and Magenta entry files. **HN News** (`/themes/hn-news.css`), **TG Channel** (`/themes/tg-channel.css`), and **ZAE** (`/themes/zae.css`) are fixed-light visual interpretations of a dense full-post news feed, a single-column channel message history, and a compact technical document sheet respectively. **Polar** (`/themes/polar.css`) is an original, fixed-light BroadcastChannel design with a minimal 760px single column. **Editorial** (`/themes/editorial.css`) is an original, system-following BroadcastChannel design built on a time gutter, hairline rules, and one restrained accent. The **palette set** adds five original BroadcastChannel designs: **Warm Orange** (`/themes/warm-orange.css`), fixed-light warm cream paper with a clay-orange accent; **Minimal Store** (`/themes/minimal-store.css`), fixed-light cool tool surface with a blue accent; **Midnight** (`/themes/midnight.css`), fixed-dark navy with a mint-teal accent; **Vivid Dashboard** (`/themes/vivid-dashboard.css`), fixed-light sectioned data cards with a tangerine accent; and **Black Gold** (`/themes/black-gold.css`), fixed-dark black-and-gold premium. `/themes/terminal-base.css` is imported internally by the four Terminal palettes and is not a standalone theme. See [THEMES.md](./THEMES.md) for entry points and configuration.

First-party rules, including Prism, use named cascade layers. Each optional theme is a normal unlayered stylesheet supplied through the trusted `HEADER_INJECT` path. Load only one override at a time.

### Token architecture

Base resolves color in three layers and every new style must respect them:

1. **Public surface** — the twelve Bear-compatible variables (`--background-color`, `--heading-color`, `--text-color`, `--link-color`, `--visited-color`, `--code-background-color`, `--code-color`, `--blockquote-color`, `--width`, `--font-main`, `--font-secondary`, `--font-scale`) plus project-owned roles (`--border-color`, `--rule-color`, `--surface-color`, `--muted-color`, `--link-hover-color`, `--accent-color`, `--focus-ring-color`, `--selection-background-color`, `--feed-meta-visited-color`, and the `--code-*` and `--reaction-paid-*` families). Only this layer carries literals.
2. **Derived roles** — `color-mix()` relationships from text, background, and accent. Because they are mixes rather than literals, the dark set only has to restate the eight base colors; borders, rules, surfaces, muted text, hover, and syntax tints follow automatically.
3. **Tailwind bridge** — the `@theme` block maps public variables onto `--color-*` utilities plus `--shadow-soft` and the `--radius-*` scale. `--color-code` maps to `--code-background-color`, so it means the code **background**, not code text.

Adding a literal outside layer 1, or hard-coding a hex in a component, is a defect: it will not follow `prefers-color-scheme` and will not be overridable by a theme.

## Colors

Base is a cool-neutral ink palette with a single indigo accent: a blue-cast paper, near-black cool headings, blue-grey body text, and one saturated indigo reserved for links, current-page marks, focus rings, and blockquote rails. It is not a Bear palette reproduction — the Bear surface is the variable contract, not the hue.

| Public variable           | Base light token             | Base dark token             | Sepia token             |
| ------------------------- | ---------------------------- | --------------------------- | ----------------------- |
| `--background-color`      | `base-light-background`      | `base-dark-background`      | `sepia-background`      |
| `--heading-color`         | `base-light-heading`         | `base-dark-heading`         | `sepia-heading`         |
| `--text-color`            | `base-light-text`            | `base-dark-text`            | `sepia-text`            |
| `--link-color`            | `primary`                    | `base-dark-link`            | `sepia-link`            |
| `--visited-color`         | `base-light-visited`         | `base-dark-visited`         | `sepia-visited`         |
| `--code-background-color` | `base-light-code-background` | `base-dark-code-background` | `sepia-code-background` |
| `--code-color`            | `base-light-code-text`       | `base-dark-code-text`       | `sepia-code-text`       |
| `--blockquote-color`      | `base-light-blockquote`      | `base-dark-blockquote`      | `sepia-blockquote`      |

Base derives the remaining roles from those eight values: `--border-color` is `20%` text into transparency, `--rule-color` is `12%` (hairlines: masthead, feed dividers, footer, chips), `--surface-color` is `4%` text into the page background, `--muted-color` is `74%` text, `--link-hover-color` is the link mixed `62%` toward the heading color, `--focus-ring-color` and `--accent-color` are the link color, and `--selection-background-color` is the link at `22%` transparency. Sepia instead sets `--accent-color`, `--border-color`, `--link-hover-color`, `--muted-color`, and `--surface-color` from its matching `sepia-*` tokens. Aria supplies neutral light and near-black dark sets. Terminal uses a fixed dark set with accent colors Amber `#eec35e`, Green `#62d884`, Cyan `#56d4e8`, or Magenta `#f087d2`; each entry also provides matching background, surface, muted, border, and visited colors. Syntax tokens derive from code, link, and visited colors; `--code-color` does not replace every Prism token category.

Every Base text role now clears WCAG AA `4.5:1` against its own page background: heading `17.5:1` light and `16.4:1` dark, body text `9.9:1` and `10.3:1`, link `6.3:1` and `9.1:1`, visited `5.8:1` and `9.2:1`. `bear-contract.test.ts` recomputes those four pairs and fails the build if a future palette edit drops below the threshold, so Base no longer carries a documented contrast exception. New project-owned colors should keep that guarantee; third-party theme authors remain responsible for the contrast of their own overrides.

Paid reactions stay on a separate warm semantic track so the one warm accent keeps its meaning. Base light uses text `#6b5000`, a `34%` text-color mix for the border, and a background made by mixing `#d5a000` at `12%` into the page background. Base dark uses text `#f3cc65`, a `50%` text-color border mix, and a `13%` text-color background mix. Sepia fixes the same role to text `#6b5000`, border `rgba(107, 80, 0, 0.34)`, and background `#f3ead0`.

Base and Aria declare `color-scheme: light dark` and follow the system preference. Editorial also follows the system preference: its light set uses warm paper `#fbfaf7` with terracotta `#b0472b`, and its dark set swaps paper for ink and raises the accent to `#e28a61`. Sepia, HN News, TG Channel, ZAE, and Polar fix `color-scheme: light`; every Terminal palette fixes `color-scheme: dark`. Polar uses a white canvas and alpha-black ink.

Two `theme-color` metas now declare `#fbfbfc` for light and `#0e1116` for dark so mobile browser chrome matches the page; the manifest keeps the light `#fbfbfc` for `theme_color` and `background_color`. CSS overrides affect the rendered page only — those metadata values do not follow a theme override or user CSS.

## Typography

Base preserves Bear's public font semantics: body copy and Tailwind's `font-sans` bridge use `--font-secondary`, while `h1`–`h6` use `--font-main`. Both variables resolve to `Verdana, sans-serif`; `--font-scale` is `1em`. The body line height is `1.5`, main content uses `1.6`, and headings use `1.25`. The redesign is deliberately chromatic and structural, not typographic: no display face is introduced and the Bear font contract is untouched.

The Base site title is `1.5em` with `-0.012em` tracking, reduced to `1.2em` at the small breakpoint. Content headings follow the restrained Tailwind scale already applied in `content/typography.css`, and post metadata is smaller than body copy. Do not enlarge feed typography into a magazine-style hierarchy.

Base is the only theme that underlines links by default, and only inside `.content`: the underline is `1px`, offset `0.18em`, and drawn at `40%` link color so dense link clusters stay quiet, snapping to `currentColor` on hover. Shell links (navigation, social, metadata, tags, pagination) stay unmarked and rely on color and state instead.

Sepia intentionally replaces both public font families with its system sans-serif stack. Its site title is `1.25rem` at weight `600`; Sepia is not a Verdana variant. Aria also uses a system sans-serif stack with a restrained editorial hierarchy. All Terminal palettes use the same Fira Code–first monospace stack (`'Fira Code', Monaco, Consolas, 'Ubuntu Mono', monospace`) for headings, controls, metadata, and body copy; Fira Code is loaded from Google Fonts when the network is available and falls back to the system mono faces otherwise. HN News keeps typography small and information-dense, TG Channel uses a familiar system-sans message hierarchy, and ZAE combines restrained editorial headings with technical monospace accents. None of these three themes bundles a font from its visual reference. Polar uses only a system sans-serif stack and bundles no fonts or assets. Editorial uses only system sans-serif and system serif stacks, gives the timestamp numerals a serif face, and makes no font requests at all. In the palette set, Warm Orange, Minimal Store, Midnight, and Vivid Dashboard use system sans-serif stacks; Black Gold sets headings in a system serif stack (Georgia first) with wide tracking and keeps body copy sans-serif. None of the five makes a font request.

## Layout

`--width` is the maximum content width, not the body's outer border-box width. The centered body remains `box-sizing: border-box`; its outer maximum adds twice the internal `--body-padding-inline` to `--width`, so horizontal padding does not consume the documented content width. Base is `800px + 20px + 20px`. Sepia, Aria, and Terminal keep `--body-padding-inline` synchronized with their actual horizontal body padding (`1.25rem`, `1.5rem`, and `clamp(1rem, 4vw, 2.5rem)` respectively). HN News, TG Channel, and ZAE set that token and body inline padding to zero, then place responsive spacing on their inner regions. The header, navigation, full feed, pagination, and footer remain in one column; there is no public desktop sidebar. Editorial is `760px + 24px + 24px` and also keeps one column: on wide viewports each post becomes a two-column grid whose first column is a `92px` time gutter inside the article, not page-level chrome.

Base's vertical rhythm is built from three hairline bands rather than boxes: the masthead ends in a `1px` rule (`1.15rem` below the navigation), `#main-content` runs `2rem` top and `1rem` bottom padding, feed entries separate with a `3rem` margin, `3rem` padding, and a `1px` rule, and the footer opens with a `1px` rule after `2.5rem`. Because all three rules share `--rule-color`, the page reads as one continuous document; no band gains a background, border box, or shadow.

Base uses `37.5rem` as both Tailwind's `sm` bridge and the explicit mobile `max-width` breakpoint. At that boundary the header becomes two columns, the avatar and title shrink, social links move below them, desktop search is hidden, and the accessible `<details>` mobile search appears. Sepia uses the same breakpoint for its feed and directory adjustments. Polar keeps the shell and complete feed in one centered column with a `760px` maximum content width. Editorial switches the feed to its time-gutter grid at `748px` and collapses the header, search, and entry meta at `687px`, where the timestamp becomes an inline marker above the post.

Sepia changes only the main top padding to `1.75rem`, removes the feed divider and separation, then uses a timestamp dot and narrow vertical rail. Aria uses an `820px` width, generous whitespace, a dashed square-line grid wash, dashed details, and section dividers; Terminal uses an `864px` width, compact blocks, an accent logo rail, thick accent media frames, and subtle solid feed separators. HN News keeps every full post visible while adding a compact story-title hierarchy above its metadata and content. TG Channel presents one centered column of messages with the real channel avatar repeated for each entry; it has no profile card or secondary column. ZAE reduces the shell to a compact identity header, technical toolbar, and framed document sheet. Warm Orange keeps the reading column at `800px` and wraps each entry in a soft cream card with a left accent rail on the description. Minimal Store narrows type to `0.95rem` and stacks entries as hairline tool panels at `820px`. Midnight keeps `800px` but lifts entries into translucent slate cards with a glow-ringed timeline dot. Vivid Dashboard widens to `880px` and gives each entry a white card with a `3px` tangerine top bar, uppercase tabular metadata, and a fully filled current navigation item. Black Gold narrows to `780px` with square lacquer cards, gold hairlines, serif headings, and uppercase navigation. Every theme retains the complete Telegram stream and responsive media behavior.

Cross-document CSS View Transitions are enabled with `navigation: auto`. Keep `site-title` stable for the title link and `post-{id}` stable for each post article. Motion is progressive enhancement; reduced-motion preferences collapse animation and smooth scrolling.

## Elevation & Depth

Base is flat: `--shadow-soft` is `none` and nothing casts a shadow. Depth comes from three signals only — the `--surface-color` ink wash (`4%` text into paper) for insets such as expandable blocks, search fields, and the back-to-top control; `--rule-color` hairlines for structure; and one `3px` accent rail on expandable content and blockquotes. A surface is a tint, never a card: it carries no border, radius change, or shadow that would make it float.

Sepia adds only shallow paper depth through four low-alpha shadow steps. Use it on the avatar, description, small navigation surfaces, reactions, pagination, and media. Aria and Terminal keep `--shadow-soft: none`; their hierarchy comes from grids, borders, surfaces, and spacing. HN News and ZAE rely primarily on flat color, rules, and typography; TG Channel may distinguish the light content surface from its cool page backdrop, but the post sequence must remain one coherent feed rather than a generic dashboard card grid. Polar is entirely flat: hierarchy uses alpha-black ink, whitespace, and solid rules, with no shadows or patterns. Editorial is flat as well: hierarchy comes from type scale, weight, a hairline rule that begins at the reading column, and the time gutter. In the palette set, Warm Orange uses one shallow warm shadow, Minimal Store one near-invisible neutral shadow, and Midnight and Black Gold deep ambient shadows on their dark canvases. Vivid Dashboard is the deliberate dashboard exception: its entries are true white data cards in a spaced grid with an accent top bar, which is the requested layout for that theme only. Do not add heavier shadows elsewhere.

## Shapes

Base uses one restrained scale: `4px` panels, `4px` chips, `8px` media. The square-to-rounded shift applies to search fields, pagination, tag chips, expandable blocks, spoiler masks, and images; avatars, back-to-top, and selected controls stay circular, and paid reactions keep the `999px` pill. A radius is a token, not a local decision — `--radius-panel`, `--radius-chip`, and `--radius-media` are bridged into Tailwind as `rounded-panel`, `rounded-chip`, and `rounded-media`.

Sepia changes the same radius bridge to `3px` panels, `4px` chips, and `8px` media. Aria uses `8px` panels, `4px` chips, and `20px` media. Terminal returns all panels, chips, media, avatars, and controls to square corners. HN News stays restrained and mostly square, TG Channel uses rounded preview-style surfaces and controls, and ZAE favors crisp editorial geometry. Editorial uses `5px` panels and media with `3px` chips, and makes pagination, back-to-top, and avatars circular. Warm Orange uses `10px` panels, `999px` chips, and `12px` media with circular avatars and pagination; Minimal Store uses `6px` panels, `6px` chips, and `8px` media with a `10px` avatar square; Midnight uses `10px` panels, pill chips, and `12px` media; Vivid Dashboard uses `16px` panels, pill chips, and `12px` media with a `12px` avatar square; Black Gold uses `2px` panels, chips, and media to keep the premium edges sharp. Pagination becomes circular in Sepia, Warm Orange, Midnight, and Vivid Dashboard, and keeps the panel radius in Minimal Store and Black Gold; timeline dots and circular controls use `50%` in CSS rather than a dimension token.

## Components

The public shell and landmarks are stable:

```text
body.home|post|page[.feed]
  > a.skip-link
  > header.site-header
      > a.avatar-link > img.channel-avatar
      > a.title > h1
      > div.social-links[role="group"]
      > div.channel-description.content (when configured)
      > nav.site-navigation
  > main#main-content
  > footer.site-footer
  > div#back-to-top-wrapper
```

Route classes are `/` and pagination routes → `home feed`, search results → `page feed`, post detail → `post`, and tags/links → `page`. The limited Bear-facing shell/CSS surface includes `body.home`, `body.post`, `body.page`, `header > a.title > h1`, `header > nav`, `main`, `footer`, `.tags`, and `pre.code`. It is not a strict Bear DOM superset. `.highlight` is accepted for inbound compatibility but is not synthesized. The normal syntax-highlighting path produces `pre.code > code.language-*`, and Prism may add nested `.token` spans; exceptional rendering paths guarantee only `pre.code`.

BroadcastChannel hooks include `body.feed`, `ol.posts-feed`, `.post-entry`, `.post-meta`, `.post-content`, `.post-reactions`, `.reaction-paid`, `p.tags.post-tags`, `.post-comments`, and Telegram widget selectors. `PostEntry` also exposes `.hn-story`, `.post-entry-avatar`, `.post-entry-author`, and `.tg-message-meta` for narrowly scoped theme treatments. Base hides all four by default in `feed.css`; overrides may reveal them without changing Base presentation. `.hn-story` wraps the real post title in an `h2` whenever one exists, while the avatar and author receive the real channel avatar and title from `PostsPage`; `.tg-message-meta` provides a message-style permalink time. `.tgme_widget_message_forwarded_from` is the stable forwarded-source hook: Base presents it as restrained supporting text without a card, background, or decoration, and optional themes may override that treatment.

Base's chrome reads as one quiet toolbar rather than a set of controls: navigation links sit at `--muted-color` and only reach `--heading-color` on hover or `aria-current="page"`, where they also gain a `2px` accent underline at `0.3em` offset; social icons follow the same muted-to-heading progression; search fields use the surface wash with a `--border-color` hairline that turns accent on `:focus-within`; pagination and tag chips are hairline-bordered at `--radius-panel` and `--radius-chip`, muted at rest, accent on hover. Every control keeps a visible `:focus-visible` ring in `--focus-ring-color`.

Feed markup is an `ol.posts-feed` of complete Telegram posts, not Bear's `ul.blog-posts` title list. HN News reveals the real story-title hook but retains the complete post beneath it. TG Channel reveals the real per-entry avatar, channel title, and message time to form one message column; these hooks do not create a profile card. Tags use `p.tags.post-tags`. There are no `/blog` or `/feed` routes, post detail keeps its page heading visually hidden, and no subscribe interface is invented. Keep navigation and utility controls restrained so they support rather than compete with the feed.

Navigation, responsive search, expandable content, spoilers, image popovers, pagination, and back-to-top behavior use HTML and CSS rather than application JavaScript. Telegram comments on post detail are the sole intentional browser-script exception.

External Telegram description and post HTML must pass through `sanitizeContentHtml` before `set:html`. `HEADER_INJECT` and `FOOTER_INJECT` are separate trusted-administrator raw HTML boundaries and must never receive untrusted content.

## Do's and Don'ts

- Do preserve the single readable column, complete Telegram content, public variables, body classes, landmarks, and stable hooks when changing styles.
- Do preserve the limited Bear CSS compatibility surface while treating the feed and content DOM as BroadcastChannel-specific.
- Do keep `--body-padding-inline` synchronized with horizontal body padding so `--width` continues to mean maximum content width.
- Do add color as a literal in layer 1 and derive the rest with `color-mix()`; the dark set should restate only the eight base colors.
- Do keep visible `:focus-visible` outlines, the skip link, semantic navigation labels, mobile touch targets, and `prefers-reduced-motion` behavior.
- Do keep article metadata and tags out of bare `header`, `footer`, or `nav` elements so broad third-party theme rules do not capture them.
- Do treat Base as the complete default and Sepia, Aria, one Terminal palette, HN News, TG Channel, ZAE, Polar, or Editorial as a single optional unlayered CSS override.
- Do preserve each theme's mode contract: Base and Aria follow the system; Sepia, HN News, TG Channel, ZAE, Polar, Warm Orange, Minimal Store, and Vivid Dashboard stay light; Terminal, Midnight, and Black Gold stay dark.
- Don't add theme state, switching JavaScript, a sidebar, invented post titles, `/blog` or `/feed` structures, or a subscribe control that the product does not provide.
- Don't reintroduce card shells, background-filled bands, or shadows to signal hierarchy in Base; use the rule and surface tokens instead.
- Don't hard-code a hex in a component or utility, and don't let a new accent role bypass `--accent-color`.
- Don't blend Sepia's paper treatment, Aria's neutral grid, Terminal's terminal geometry, HN News's dense list, TG Channel's preview surface, ZAE's technical editorial treatment, Polar's minimal flat rules, or Editorial's time gutter and hairline grid into Base or one another.
- Don't expose `terminal-base.css` as a user theme or combine multiple override stylesheets.
- Don't assume CSS themes update non-CSS metadata, and don't bypass sanitization for Telegram HTML.
