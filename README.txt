NORA Mobile – Install & Usage Guide
===================================

What this is
------------
A single web page (index.html) that collects transport details and opens the device’s email app to send them to:
  dispatch@nortrans.com  (locked recipient)

Supported browsers
------------------
- Desktop/Laptop: Chrome, Edge, Firefox, Safari, Opera
- Android phones: Chrome/Edge/Opera (Add to Home screen supported)
- iPhone/iPad: Safari (Add to Home Screen recommended)

How to use (quick)
------------------
1) Open: https://steven0525-katrina532.github.io/nora-mobile/
2) Fill Caller Name, Phone, Date, Time (TZ defaults to ET).
3) Tap **Submit to Dispatch** – your mail app opens addressed to dispatch@nortrans.com with the message pre-filled.
4) Press **Send** in your mail app. (If you close the draft, nothing is sent.)
5) A confirmation reply from Dispatch will arrive in the **inbox of the email account you sent from**.

Install to phone home screen (optional)
---------------------------------------
Android (Chrome):
  • Open the link above
  • Tap ⋮ (menu) → Add to Home screen → Add

iPhone (Safari):
  • Open the link above
  • Share icon → Add to Home Screen → Add

Local preview (no internet)
---------------------------
1) Open the folder and double-click `index.html`.
2) The page works offline; the Submit button still opens your mail app.

Files in this package
---------------------
- index.html        (the whole app)
- manifest.json     (PWA metadata)
- sw.js             (service worker for installability)
- /icons
    - icon-192.png
    - icon-512.png
    - nora-logo.png (optional: your logo source; used in header if present)

Changing the header icon/logo (optional)
----------------------------------------
1) Put your PNG at:  icons\nora-logo.png
2) Regenerate crisp icons (192/512) and push:
   - Ask the project owner for the PowerShell icon-resizer snippet (already prepared).

Updating the live site (GitHub Pages)
-------------------------------------
1) Edit files locally.
2) In PowerShell inside the project folder:
     git add .
     git commit -m "Your change"
     git push
3) Refresh the website after 30–60 seconds.

Deliverability tips (if a message ever bounces)
-----------------------------------------------
- Keep subject line as: “NORA Transport Request” (already set by the app).
- Avoid typing “TEST” in the subject.
- If a bounce references Barracuda/cudaops.com, ask the recipient admin to allowlist
  your sender (e.g., steven.hayes@noratrans.com) or your domain (noratrans.com).

Support
-------
- Phone: (855)-554-6672 (tap-to-call button in header)
- Questions about this page: reply to the sender who shared this link or contact the project owner.
