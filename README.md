# Pocket Chaos PoC

Static production build of the Angular sandbox (`Pocket_Chaos/PoC/pocket-chaos-poc`). This repository contains only the files GitLab Pages serves.

The app is built with `<base href="/pocket-chaos-poc/">`. Publish it as a **project** site so the URL path is `/pocket-chaos-poc/` (for example `https://<namespace>.gitlab.io/pocket-chaos-poc/`). A unique domain served from `/` will not load the scripts.

`public/404.html` is a copy of `index.html` so GitLab Pages can still open the app on an unknown path.
