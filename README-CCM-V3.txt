CONDOLENCE CARD MESSAGES - V3  (condolencecardmessages.com)
Premium redesign + free photo upload + P0 fixes. 62 pages.

WHAT CHANGED IN V3
Fixes (the things that were wrong in V2):
- Card maker no longer opens on the old "She carried the whole house..." text.
  It opens on a real condolence message ("Thinking of you and holding you close
  in my heart.").
- Removed the heavy "CONDOLENCE CARD MESSAGES" stamp across the middle of every
  card. Attribution is now optional and empty by default (a sympathy card should
  not brand its own centre). A subtle site URL stays at the very bottom.
- Nav rebuilt: buttons no longer wrap/oversize (added no-wrap + refined sizing);
  "Sign in" is now a subtle outline button, not a big filled pill; links declutter
  on mobile. Single clean row.
- Message grid: equal-height cards with actions pinned to the bottom, so no more
  half-empty card gaps.

Premium redesign:
- Shifted the whole palette from the warm plum ("mom") tone to a calm, dignified
  sympathy scheme: dusty slate-blue accent (matches the favicon), muted eucalyptus,
  warm ivory, gentle gold. Reads premium and gender-neutral, suited to grief.

New feature - FREE PHOTO UPLOAD (the competitor paid feature, given free):
- "Add a photo" in the card maker puts a photo of the loved one or pet onto the
  card, in a soft rounded frame, message below. Fully client-side - the photo
  never leaves the device. Hallmark/Moonpig/Card Factory charge GBP 1.99-3.79 for
  photo cards; here it is free, no watermark.

STILL TO COME (next build, agreed): real folded/portrait printable card (front +
inside + A5 PDF), premium code-drawn design set (lily, feather, candle, dove,
botanical) + the pet / Rainbow Bridge set, browse-with-filters page.

DEPLOY (unchanged from V2)
- secrets.php outside public_html (ADMIN_PASSWORD, NOTIFY_EMAIL=info@...).
- Create info@condolencecardmessages.com mailbox.
- Authenticated SMTP + SPF/DKIM/DMARC (your hPanel + DNS - see V2 notes).
- Swap AdSense slot 0000000000 for real IDs. Upload all. Submit sitemap.xml.
- Asset version bumped to v=3, so a hard refresh / redeploy shows the new design.
