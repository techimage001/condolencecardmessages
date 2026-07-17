CONDOLENCE CARD MESSAGES - V2  (condolencecardmessages.com)

WHAT'S IN V2  (62 pages)
- 50 keyword-mapped message pages, 500 ORIGINAL cliche-free messages, built from
  your validated Google keywords (relationship, wording, faith, recipient,
  circumstance, format). Measured content dissimilarity: max Jaccard 0.58 (well
  under the 0.72 ceiling) - no near-duplicate pages.
- 6 theme hubs (by relationship / condolence wording / cards notes remembrance /
  religious & cultural / who you're writing to / by circumstance) + an A-Z index.
- Homepage: free-vs-paid comparison, browse-by-theme, FAQ + schema.
- Card maker (app.html): all 500 messages loaded, sticky live preview (desktop +
  mobile, verified), download with no watermark + metadata + descriptive filename,
  favourites, PWA.
- SEO on every page: unique title + description (0 duplicates), canonical,
  OG/Twitter, robots max-image-preview, JSON-LD (breadcrumbs + collection/FAQ),
  hub-and-spoke internal links (27 per page), sitemap (62 urls).
- Hardened systems: double opt-in email verification, secrets-outside-git,
  leads.php admin (verified vs pending, CSV, GDPR delete), AdSense
  (ca-pub-4138594802747479), Google-compliant slate favicon.
- QA (headless-verified): 0 broken links, 0 brand leaks, footer horizontal,
  sticky preview holds on scroll, card-maker JS valid.

EMAIL - YOU MUST DO THIS PART (I cannot; it lives in your hPanel/DNS)
The mailer code is wired for authenticated SMTP and reads creds from your secrets
file. To make verification/notification emails land in the inbox:
1. Create the mailbox info@condolencecardmessages.com in hPanel.
2. In secrets.php add the SMTP host/port/user/password for that mailbox.
3. Add these DNS records for condolencecardmessages.com:
   - SPF  (TXT): authorise Hostinger's mail servers (hPanel shows the value).
   - DKIM (TXT): enable DKIM in hPanel, publish the key it gives you.
   - DMARC(TXT): _dmarc  ->  v=DMARC1; p=none; rua=mailto:info@condolencecardmessages.com
Without SPF/DKIM/DMARC, verification links may hit spam and signups will fail.

OTHER DEPLOY STEPS
- Create secrets at domains/condolencecardmessages.com/condolencecardmessages_private/secrets.php
  from SECRETS-TEMPLATE.php (long ADMIN_PASSWORD, NOTIFY_EMAIL=info@...).
- Swap AdSense slot placeholder 0000000000 for your real slot IDs.
- Upload everything (files at repo root), then submit sitemap.xml in Search Console.
- Stagger publishing / indexing; do not expect all 62 to rank at once.

NEXT ROUNDS (toward ~200)
- Long-tail: relationship x cause x faith combinations, more "loss of a [x]" pages,
  regional/cultural variants, printable certificate/keepsake.
- Retarget card-maker motifs to condolence art (dove, candle, leaf).
- Re-run `node tools/build.js` after editing data/quotes.json to regenerate.
