NORA Mobile — Instructions
==========================

What this is
- A single web page form (index.html) that opens the device's email app
- Recipient is locked to dispatch@nortrans.com
- Works on phone or laptop; on phones it can be added to the home screen once hosted

How to use
1) Open index.html in a browser
2) Fill Caller Name/Phone, Date, Time, TZ (ET is default)
3) Click "Submit to Dispatch" — your mail app opens to dispatch@nortrans.com with a prefilled body
4) Press Send to actually send
5) The page clears saved data after handoff

Hosting (optional, for phone home-screen install)
- Put these files on any HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages)
- Then on the phone: Share → Add to Home Screen (Safari/iOS) or ⋮ → Add to Home screen (Chrome/Android)

Notes
- Replies from Dispatch will appear in the sender’s email inbox
- Time Zone can be changed (ET/CT/MT/PT)
- Transport menu supports Teams—specify and Other (shows a details box)
