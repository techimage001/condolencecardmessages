CONDOLENCE CARD MESSAGES - V8  (condolencecardmessages.com)
71 pages. Everything outstanding is now delivered.

NEW IN V8
1. TRUE FOLDED PRINT PDF - "Folded card PDF" button. Produces a real 2-page A4
   landscape PDF: outside sheet (back panel + your card front) and inside sheet
   (your message set in clean type), with a dashed FOLD LINE down the centre and
   CROP MARKS at every corner. Print on A4, fold in half, and you have a proper
   A5 folded sympathy card. Built entirely in-browser (no service, no upload).
2. REFINED + ORIGINAL FRAME ARTWORK - five new frames, all code-drawn and
   copyright-safe: Deco corners (stepped art-deco + fine inner keyline), Wreath
   (laurel arc), Lily corner (single lily stem), Paw prints, and Rainbow bridge
   (muted arc). All 12 frames verified to render distinctly.
3. NEW MOTIFS - Paw print, Dove, Candle, Feather (plus the existing set), all
   original vector drawings.
4. NEW QUICK DESIGNS - "Rainbow bridge (pet)", "Lily & ivory", "Wreath & dove",
   and the Pet remembrance preset now uses the paw frame.
5. PET / RAINBOW BRIDGE VERTICAL - 8 new pages, 80 new original messages:
   Rainbow Bridge Messages, Pet Sympathy Card Messages, Loss of a Dog, Loss of a
   Cat, What to Write in a Pet Sympathy Card, Pet Memorial Messages, Sorry for
   the Loss of Your Pet, Pet Loss Messages for a Child. Plus a dedicated hub:
   /pet-loss-rainbow-bridge.html, linked from the homepage and every footer.
   NOTE: all wording is ORIGINAL. The well-known Rainbow Bridge poem has a
   claimed author and is NOT reproduced anywhere on the site.

IMPORTANT FIX: CACHE-BUSTING WAS BROKEN
The generator's ASSET_V variable had drifted out of sync, so regenerated pages
kept serving ?v=3 while only a few pages advanced. That is why you kept seeing
old CSS live. It is fixed at the source: ASSET_V='8' and ALL 71 pages now
reference styles.css?v=8 and site.js?v=8. Also added the missing site.js to
privacy.html and terms.html, whose hamburger menu could not open without it.

CARRIED FROM V7
- Facebook 1200x1200, LinkedIn 1200x1200, X 1600x900; domain clears the frame.
- Zero mobile drift; outline-heart Save; no year in titles; evergreen copyright.
- WhatsApp/X share the card image via the native share sheet.

QA: 71 pages, 71 sitemap URLs, 0 broken links, 0 duplicate titles/descriptions,
0 brand leaks, 0 horizontal drift (320-430px), 12 frames + 7 motifs render
distinctly, folded PDF verified generating a valid 270KB+ PDF, content
dissimilarity max Jaccard 0.58 (ceiling 0.72), card-maker JS valid.

DEPLOY: upload everything, hard-refresh once. Sitemap now has 71 URLs - resubmit
in Search Console so the 9 new pet pages and hub get discovered.
