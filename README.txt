Sub-24 5K app

Files:
  index.html            the app itself (this is the file you replace for updates)
  sw.js                 offline support and the "Update available" banner
  manifest.webmanifest  app name, colors and icons for installing on your phone
  icon-192.png, icon-512.png, apple-touch-icon.png   home-screen icons

To update: upload a new index.html to GitHub (Add file > Upload files > Commit changes).
Netlify republishes in about a minute. Optional: change VERSION in sw.js (v1 -> v2)
to make the "Update available" banner appear on your phone.
