---
name: "footsteps-pages"
description: "Source capture of the existing implementation; no new visual direction."
colors: {"launch-blue":"#1d4ed8","launch-blue-deep":"#173cb0","accent-blue":"#007aff","accent-blue-dark":"#0a84ff","mint":"#84d8aa","mint-deep":"#147a68","bg":"#f3f6fb","bg-soft":"#e8eef8","surface":"#ffffff","surface-alt":"#f8fbff","surface-border":"#dbe4f0","text":"#111827","muted":"#667085"}
---

# Design System: footsteps-pages

## Overview

This is a source capture of the incumbent implementation at `6228aa672e7aba803508b667631a342eebd9a92c`, not a redesign or a claim that the interface has been rendered or tested. Source files remain the implementation authority. Creative metaphors, qualitative branding and unverified component previews are deliberately unresolved.

The full declaration inventory, selector/variant scope, file locations and source hashes are in `.impeccable/design-source.json`. Re-capture after relevant implementation changes; do not apply an isolated declaration outside its original selector, media query or platform.

## Colors

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:9` — `:root`: `--bg: #f3f6fb`.
- `styles.css:11` — `:root`: `--surface: #ffffff`.
- `styles.css:13` — `:root`: `--surface-border: #dbe4f0`.
- `styles.css:15` — `:root`: `--muted: #667085`.
- `styles.css:35` — `body`: `color: var(--text)`.
- `styles.css:36` — `body`: `background: radial-gradient(circle at top, rgba(29, 78, 216, 0.08), transparent 35%),
    linear-gradient(180deg, #f8fbff 0%, var(--bg) 100%)`.
- `styles.css:42` — `a`: `color: var(--accent-blue)`.
- `styles.css:47` — `a:hover`: `color: var(--launch-blue)`.
- `styles.css:64` — `code`: `background: rgba(17, 24, 39, 0.06)`.
- `styles.css:87` — `.brand`: `color: inherit`.
- `styles.css:110` — `.brand-copy span`: `color: var(--muted)`.
- `styles.css:127` — `.nav a`: `background: rgba(255, 255, 255, 0.88)`.
- `styles.css:129` — `.nav a`: `color: var(--text)`.
- `styles.css:137` — `.nav a.active,
.nav a:hover`: `background: var(--launch-blue)`.
- `styles.css:139` — `.nav a.active,
.nav a:hover`: `color: #fff`.
- `styles.css:144` — `.breadcrumbs`: `color: var(--muted)`.

## Typography

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:28` — `html`: `font-size: 16px`.
- `styles.css:34` — `body`: `font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", sans-serif`.
- `styles.css:65` — `code`: `font-family: "SFMono-Regular", "Menlo", "Monaco", monospace`.
- `styles.css:66` — `code`: `font-size: 0.94em`.
- `styles.css:104` — `.brand-copy strong`: `font-size: 1.05rem`.
- `styles.css:105` — `.brand-copy strong`: `font-weight: 700`.
- `styles.css:106` — `.brand-copy strong`: `letter-spacing: -0.01em`.
- `styles.css:111` — `.brand-copy span`: `font-size: 0.92rem`.
- `styles.css:130` — `.nav a`: `font-size: 0.95rem`.
- `styles.css:131` — `.nav a`: `font-weight: 600`.
- `styles.css:145` — `.breadcrumbs`: `font-size: 0.92rem`.
- `styles.css:219` — `.eyebrow`: `font-size: 0.82rem`.
- `styles.css:220` — `.eyebrow`: `font-weight: 700`.
- `styles.css:221` — `.eyebrow`: `letter-spacing: 0.06em`.
- `styles.css:230` — `.hero h1,
.page-banner h1`: `font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", sans-serif`.
- `styles.css:231` — `.hero h1,
.page-banner h1`: `font-size: clamp(2.35rem, 4.8vw, 4.5rem)`.

## Layout

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:32` — `body`: `margin: 0`.
- `styles.css:57` — `img`: `max-width: 100%`.
- `styles.css:58` — `img`: `display: block`.
- `styles.css:62` — `code`: `padding: 0.1rem 0.35rem`.
- `styles.css:71` — `.page`: `margin: 0 auto`.
- `styles.css:72` — `.page`: `padding: 1rem 0 4rem`.
- `styles.css:76` — `.masthead`: `display: flex`.
- `styles.css:79` — `.masthead`: `gap: 1rem`.
- `styles.css:80` — `.masthead`: `padding: 0.75rem 0 1.5rem`.
- `styles.css:84` — `.brand`: `display: inline-flex`.
- `styles.css:86` — `.brand`: `gap: 0.9rem`.
- `styles.css:98` — `.brand-copy`: `display: flex`.
- `styles.css:99` — `.brand-copy`: `flex-direction: column`.
- `styles.css:100` — `.brand-copy`: `gap: 0.1rem`.
- `styles.css:115` — `.nav`: `display: flex`.
- `styles.css:116` — `.nav`: `flex-wrap: wrap`.

## Elevation & Depth

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:16` — `:root`: `--shadow: 0 18px 40px rgba(17, 24, 39, 0.08)`.
- `styles.css:94` — `.brand-mark`: `box-shadow: 0 10px 24px rgba(20, 122, 104, 0.18)`.
- `styles.css:132` — `.nav a`: `box-shadow: 0 4px 12px rgba(17, 24, 39, 0.04)`.
- `styles.css:170` — `.hero,
.page-banner`: `box-shadow: 0 28px 54px rgba(29, 78, 216, 0.22)`.
- `styles.css:298` — `.hero-preview`: `box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1)`.
- `styles.css:315` — `.hero-icon`: `box-shadow: 0 16px 32px rgba(0, 0, 0, 0.16)`.
- `styles.css:358` — `.panel,
.policy-card,
.support-card,
.contact-card`: `box-shadow: var(--shadow)`.

## Shapes

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:17` — `:root`: `--radius-xl: 30px`.
- `styles.css:18` — `:root`: `--radius-lg: 24px`.
- `styles.css:19` — `:root`: `--radius-md: 18px`.
- `styles.css:63` — `code`: `border-radius: 0.45rem`.
- `styles.css:93` — `.brand-mark`: `border-radius: 1rem`.
- `styles.css:126` — `.nav a`: `border-radius: 999px`.
- `styles.css:128` — `.nav a`: `border: 1px solid var(--surface-border)`.
- `styles.css:138` — `.nav a.active,
.nav a:hover`: `border-color: var(--launch-blue)`.
- `styles.css:168` — `.hero,
.page-banner`: `border-radius: var(--radius-xl)`.
- `styles.css:180` — `.hero::before,
.page-banner::before`: `border-radius: 50%`.
- `styles.css:191` — `.hero::after,
.page-banner::after`: `border-radius: 50%`.
- `styles.css:215` — `.eyebrow`: `border-radius: 999px`.
- `styles.css:217` — `.eyebrow`: `border: 1px solid rgba(255, 255, 255, 0.12)`.
- `styles.css:264` — `.button,
.button-secondary`: `border-radius: 999px`.
- `styles.css:265` — `.button,
.button-secondary`: `border: 1px solid transparent`.
- `styles.css:280` — `.button-secondary`: `border-color: rgba(255, 255, 255, 0.16)`.

## Components

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:52` — `a:focus-visible,
button:focus-visible`: `outline: 3px solid rgba(0, 122, 255, 0.3)`.
- `styles.css:53` — `a:focus-visible,
button:focus-visible`: `outline-offset: 3px`.

## Do's and Don'ts

- Preserve existing tokens, selectors, light/dark variants, locale overrides and platform semantics.
- Reuse existing component implementations and inspect their complete interaction states.
- Verify accessibility, navigation, focus, text scaling and reduced motion in the appropriate browser or native runtime before claiming a UI pass.
- Do not treat this source inventory as a rendered audit or approval for a new brand.
- Do not synthesize missing colors, scales, component previews or product claims.
