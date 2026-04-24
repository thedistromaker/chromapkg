# chroma
A new, shell-based package manager with a DFS resolver, and a JSON database for all the packages.
## How do we host packages?
We use JSDelivr CDN to make the URLs more consistent, whilst using main for pushing new packages before pushing to a stable dated release (eg branch 24-4-2026 will be stable, dev will be rel candidate, main will be unstable).
