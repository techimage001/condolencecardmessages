CONDOLENCE CARD MESSAGES - V9  (condolencecardmessages.com)
Two targeted fixes only. Everything else unchanged. Assets bumped to v=9.

1. FLOATING (STICKY) CARD PREVIEW RESTORED - desktop AND mobile.
   Cause: the anti-drift guard added in V7 used
       html,body{overflow-x:hidden}
   and overflow:hidden creates a scroll container, which silently disables
   position:sticky on every descendant. That is what killed the floating card.
   Fix: overflow-x:clip (which prevents sideways drift WITHOUT creating a scroll
   container), with an overflow-x:hidden fallback only for browsers that do not
   support clip.
   Verified: desktop preview holds at the top after a 900px scroll; mobile
   preview stays on screen; and horizontal drift is STILL zero at
   320/360/390/414px across all page types.

2. FOLDED CARD PDF NOW WORKS ON MOBILE TOO.
   Cause: mobile browsers (iOS Safari especially) block blob-URL downloads, so
   the button appeared to do nothing on a phone.
   Fix: on mobile the PDF is now handed to the native share sheet as a real PDF
   file (save to Files, print, AirDrop, send to anyone), with a new-tab fallback
   for any browser that cannot download or share. Desktop behaviour is unchanged
   (straight download). No label needed - it works on both now.

NOTHING ELSE WAS CHANGED.

DEPLOY: upload everything and hard-refresh once (v=9).
