AVALDIAN — ONE-PAGE SITE
========================

FILES
  index.html     The whole site. One file, no build step, no dependencies.
  favicon.png    Browser tab icon.
  og-image.png   The preview card shown when the link is shared on
                 WhatsApp, LinkedIn, Facebook or X. 1200 x 630.

BEFORE YOU PUBLISH — fill in 3 placeholders
  Open index.html in any text editor and search for:

  1. 234XXXXXXXXXX     appears TWICE, in the two "Start a conversation"
                       buttons. Replace with your WhatsApp number in
                       international format, no +, no spaces.
                       Example: 2348012345678

  2. hello@avaldian.com   Your real email address.
  3. @avaldian            Your real Instagram handle.

  Also search for  +234 XXX XXX XXXX  in the contact row and write the
  number the way you want people to read it.

AFTER YOU BUY A DOMAIN
  In index.html, change the og:image line to the full address, e.g.
  <meta property="og:image" content="https://avaldian.com/og-image.png">
  Social platforms need the full URL, not a relative one, to show the card.

HOW TO PUT IT ONLINE
  Netlify Drop  — netlify.com/drop — drag this whole folder onto the page.
                  Live in about 20 seconds, free, then point your domain at it.
  Cloudflare Pages / Vercel — same idea, also free.
  cPanel host   — upload all three files into public_html.

  Whichever you use, keep the three files together in the same folder.

NOTES
  The fonts (Space Grotesk, Plus Jakarta Sans) load from Google Fonts, so
  the page needs an internet connection to look right — normal for a website.
  The page follows the visitor's light or dark setting automatically. 
