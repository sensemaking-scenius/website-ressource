# The Sensemaking Scenius Website

The community website for [The Sensemaking Scenius](https://kpaxle.mmm.page/scenius) — a community of practice for digital builders, researchers, artists & activists who share a vision of a regenerative, intentional & meaningful internet.

**Live:** https://sensemaking-scenius.github.io/website-ressource/

## Background

The original website was built by Kristen on [mmm.page](https://mmm.page). In our [Feb 12, 2026 workshop](https://github.com/sensemaking-scenius/website-ressource/issues), the community agreed to rebuild it as an open-source project so that anyone can contribute via pull requests.

This repo is that rebuild.

## Structure

```
site/
  index.html          # Main page (narrative scroll)
  about.html           # Mission, principles, backstory
  styles.css           # All styles
  assets/images/       # GIFs, PNGs, decorations
.github/workflows/
  deploy.yml           # Auto-deploys site/ to GitHub Pages on push
```

Plain HTML/CSS — no build step required. Edit the files, push, and GitHub Pages deploys automatically.

## Contributing

1. Fork the repo
2. Make your changes in the `site/` directory
3. Open a pull request

You can also use GitHub's web editor (click the pencil icon on any file) for quick changes without cloning.

For larger changes, Claude Code or any LLM can help — just point it at the repo and describe what you want.

## Roadmap

Based on the [Feb 12, 2026 workshop](https://kpaxle.mmm.page/scenius) decisions. Issues track all planned work.

### V1 — Faithful Reproduction (current)

Migrate the existing mmm.page site into a community-editable, open-source format.

- [x] Reconstruct main page as HTML/CSS (Alexandre + Jon)
- [x] Deploy to GitHub Pages
- [x] Create about page (mission, principles, backstory)
- [ ] [CSS polish: visual comparison pass](https://github.com/sensemaking-scenius/website-ressource/issues/1)
- [ ] [Migrate to 11ty](https://github.com/sensemaking-scenius/website-ressource/issues/2)
- [ ] [Contributor guide](https://github.com/sensemaking-scenius/website-ressource/issues/8)

### V2 — Brand Upgrade

Apply the Scenius brand identity and integrate content feeds.

- [ ] [Apply Scenius brand (Spencer's design)](https://github.com/sensemaking-scenius/website-ressource/issues/3)
- [ ] [Integrate Paragraph blog](https://github.com/sensemaking-scenius/website-ressource/issues/4)

### V3 — Subpages as Needed

Add pages for specific community needs as they arise.

- [ ] [Professional subpage for funders/grants](https://github.com/sensemaking-scenius/website-ressource/issues/5)
- [ ] [Project subpages](https://github.com/sensemaking-scenius/website-ressource/issues/6)
- [ ] [Member directory](https://github.com/sensemaking-scenius/website-ressource/issues/7)

## Domain

The target domain is **scenius.space** (currently pointing at a separate Quartz site). Once V1 is polished, the domain will be moved to point at this GitHub Pages deployment.

## License

This is a community project of The Sensemaking Scenius.
