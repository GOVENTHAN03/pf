# Hemalatha Omprakash — portfolio handoff

Open index.html for the portfolio or compare.html for side-by-side themes. Keep the assets folder beside both HTML files. The ZIP includes everything needed for static hosting.

## What changed
- Built the portfolio from the supplied client information, resume, certificates, and academic report.
- Preserved the requested order: Home, About, Education, Skills, Certifications, Achievements, Contact, footer. Experience and projects appear within About.
- Added dark-default and light themes using one shared layout and plum accent family, plus a saved navbar toggle.
- Added responsive navigation, consistent typography, spacing, card treatments, keyboard focus indicators, reduced-motion support, page title, and favicon.
- Rewrote supplied content for concise professional presentation, without inventing employment outcomes or skill levels.
- Added six optimized, correctly oriented certificate thumbnails and links to their original PDF pages.
- Added original resume download, NIFTY 50 project report, LinkedIn, WhatsApp, and email links.
- Added a validated contact form with a thank-you message. It prepares an email in the visitor’s email app; it does not send or store submissions on a server.
- Added a comparison page containing all sections in both themes.

## Verification
- Desktop visual review; mobile at 390px and tablet at 768px showed no horizontal content overflow.
- Mobile menu and saved theme preference checked in browser.
- All 11 local page/asset URLs returned successfully.
- Tested rendered text colors across all sections: minimum contrast 7.91:1 dark, 6.05:1 light (above WCAG AA normal-text minimum). Certificate document text is original scanned material and is not covered by theme contrast calculations.

## Content decisions
- No GitHub link: no client profile was supplied.
- Graduation year omitted because the supplied answers conflict between 2026 and 2027.
- School dates omitted because the resume’s HSC/SSLC chronology is inconsistent.
- Original resume retained unchanged; it still says seven months of experience, while the website follows the newer eight-month client information.
- No invented portrait or testimonials; the hero uses a typographic monogram.
- The contact form depends on the visitor having an email app. Direct email and WhatsApp links are provided as alternatives.

## PARALLAX integration
Integrated all 12 exact SVG paths into a full-height Hema hero, using the shared dark/light palette. Retained the client content, section order, resume/contact actions and monogram. The unrelated reference portrait was not used as a client photograph.

## Full PARALLAX hero
Replaced the introductory card composition with the full reference scene: original remote photo, 12 exact animated rings, centered HEMALATHA OMPRAKASH title, corner copy, and stacked resume/contact buttons. Theme-specific overlays preserve text readability. The photo is labeled editorial reference artwork. All remaining portfolio sections are retained. Reduced-motion preference skips ring animation.

## Light chrome and pointer shimmer
Added parallax-light.html with the original photo, exact 12 paths, white title/corner copy, original fonts, positions and entrance scripts preserved. Only panel colors changed, plus the requested pointer shimmer. Applied white/black chrome to Hema’s light hero without bleaching its photograph. Shimmer is decorative, does not intercept clicks, and is disabled for touch and reduced motion.

## Scroll, hover, and document interactions
Added subtle one-time section scroll reveals, a 4px section hover lift, and a 5px certificate-card lift. Reduced-motion and touch preferences are respected. Each certificate now has its own PDF and on-page image preview with PDF open/download controls. The resume opens in an accessible modal with PDF preview and download controls. Escape and the close button dismiss the dialog, restore focus, and release page scrolling.

## Editorial marquee integration
Replaced the PARALLAX ring hero with the supplied layered portrait and scrolling-name composition, adapted to Hemalatha. Added the supplied font stylesheet, entrance timing, cream rule, mobile drawer, and motion pause control. Kept the existing standalone HTML delivery and working document previews instead of migrating the entire portfolio to React. Converted portfolio accents to black/cream and removed pointer glow. Reference portraits are explicitly labeled editorial artwork. Retained dark/light switching for the portfolio sections.

## Rounded section pop-ups and interactive pointer
Added expandable dialogs for About, Education, Skills, Certifications, Achievements, and Contact. Section links open the same live content in dialogs; document previews and form handlers remain attached. Added rounded section/card corners, button hover/press feedback, a floating saved-theme switch, and a monochrome pointer halo with a short dissipating trail. Native cursor remains visible. Touch and reduced-motion users do not receive pointer effects. Dialogs close with Escape or their close button and restore content position and keyboard focus.

## Client portrait and Apollo-inspired hover
Replaced both editorial image layers with the exact supplied PNG, copied without retouching. The front portrait is clear and the duplicate background is styled with CSS blur/dimming. Removed the reference-artwork label. Added diagonal shine, subtle image scale, and certificate-preview captions inspired by Apollo in Codrops HoverEffectIdeas Set 2: https://github.com/codrops/HoverEffectIdeas . Keyboard focus, touch captions, reduced motion, and existing document/section dialogs are retained.

## Glow cursor and specular subgroup hover
Added a soft theme-aware cursor glow. Buttons and subsection cards, and project rows now receive a pointer-positioned reflective highlight and edge glint. Effects work in section/document pop-ups, preserve normal clicks, and are disabled for touch and reduced motion.

## Floating 3D-style portrait
Placed the supplied photo on a dimensional foreground surface with perspective, a rim, depth shadow, moving light, gentle floating motion and mouse-responsive tilt. The original photo is unchanged. This is a 2.5D photographic presentation, not reconstructed facial geometry or a rotatable person model. Pause motion stops both the marquee and portrait animation; reduced-motion disables movement.

## Cutout, stickers, typewriter name and updated reports
Added Billing experience and Tamil & English typewriting to the portfolio and a clear orange motion strip. Rebuilt the hero around the supplied transparent portrait, cream/orange paper-style stickers, and a two-line typewriter name. The name and moving text have their own unobscured areas. Added the updated 81-page NSE/NIFTY 50 report and 78-page TVS grievance report, both with modal previews and PDF downloads. Original PNG and PDF files are copied unchanged. Theme, touch, reduced-motion and pause support retained.

## Visual and mobile update
- Added an opening name reveal with a skip control and reduced-motion support.
- Added illustrated navigation, project topic graphics, and experience/skill icons.
- Rebalanced the mobile hero around the portrait with compact facts and actions.
- Added theme-aware interactive heading colors and pictorial hover effects.
- Preserved section order, document links, and existing contact actions.

## Premium portfolio refinement
- Rebuilt the page with a consistent charcoal, cream, and copper palette and editorial typography.
- Refined headlines and introduced a portrait-led hero with verified highlights.
- Added project filters, mobile contact bar, copy-email, recruiter FAQ, reading progress, and accessible document/section dialogs.
- Added readable first-page previews for the resume and both reports; retained complete PDF downloads.
- Kept all six sections, certificates, project reports, and contact information.
- Added search/share metadata and an updated favicon.

## Corporate Tax Strategy report — local update, publication pending
- Attached the original 70-page report to the existing project.
- Added matching Read project and Download PDF controls, with a first-page preview.

## Interactive illustrations — local update, publication pending
- Added seven original vector illustrations across education, skills, achievements, and contact.
- Each illustration supports hover/focus movement and a native tap-to-expand explanation.
- Theme-aware colors, responsive sizing, and reduced-motion support.

## Expanded visual library — local update, publication pending
- Added 16 illustrations across experience, the education roadmap, tool cards, the learning map, and a Tamil/English typewriting panel.
- Added three original report-cover previews and a portrait contact card.
- Added six expandable tool cards and interactive language selection.
- Retained the earlier seven interactive illustrations, section order, and project downloads.
