# Longevity Life Academy brand tokens (extracted 12 Oct 2026)
Sources: computed styles + :root vars of https://www.longevitylifeacademy.com/ (Playwright, Chrome), repo Longevity-Academy/julie-masterclass (index.html, assets/*.css).

## Fonts
- Display: 'Codec Pro' (var --font-display). Live site loads ONLY CodecPro-Regular.woff (400) and CodecPro-Italic.woff from fonts.cdnfonts.com/s/31902/ (no bold file exists in repos; h1 700 / h2 800 are browser-synthesized). Files copied to build/assets/.
- Body/UI: Inter 400/500/600/700/800 (Google Fonts), var --font-body.
- Accent: Instrument Serif 400 italic (Google Fonts), used on live page for italic accents.
- (Playfair Display appears in julie-premium.css; not used in ads.)
## Colors
- eTeacher blue --blue #006EFF; --blue-strong #0051CC; --blue-hover #0059D6; --blue-light #E8F1FF
- Site body bg (dark) rgb(6,14,26) = #060E1A; body text #E8EAED
- Julie page: --navy #0A2240, --navy-deep #061633, --navy-ink #040D24, --blue-2 #338BFF, --blue-3 #5EB6FF, --sky #9CC8FF, --ice #E8F1FF, --mg (gold) #F6DC8C
- Ink scale --ink #111111, --ink-3 #5A6472, --ink-4 #8892A0; surfaces #F5F7FA, #EEF1F6
- Phase accents #6FA8FF #E8A75A #5FB6B0 #3B3F91
## Logo
- Official lockup: assets/lla-logo-exact-transparent@2x.png (1314x596, light lockup for dark bg, "Longevity Life Academy by eTeacher Group"), same file used in live nav (src .../lla-logo-exact-transparent@2x.png?v=9). No SVG in repos.
## Buttons
- .btn: radius 14px, Inter 700 18px, letter-spacing .01em, padding 19px 42px
- .btn-blue: linear-gradient(180deg,#8AD2FF,#38A6FF), text #03182b, border 1px rgba(190,230,255,.9), glow shadow 0 0 16px rgba(94,182,255,.85), 0 0 46px rgba(0,150,255,.5)
- Radii: 10 / 16 / 24 / 32px
## Photo treatment
- Real Julie photography (assets/instructors/*: warm golden-hour outdoor portraits, natural light), placed on deep navy (#060E1A/#061633) with dark gradient scrims; white type over photo.
