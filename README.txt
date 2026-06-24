BCB UPLOAD BUNDLE
=================

Two folders. They go to two different places. Don't mix them up.


1) PUBLIC-upload-to-pages-repo/
-------------------------------
Upload the CONTENTS of this folder to your GitHub repo (MarkMrQ/Bcb-plan),
via the web UI: "Add file" > "Upload files", then drag these in.

It is already laid out the way the repo should look:

    index.html            -> the plan site (your existing root, markmrq.github.io/Bcb-plan/)
    site/index.html       -> the flagship prototype (international tier version)
    sitemap/index.html    -> the POC sitemap

After upload, the live URLs are:
    markmrq.github.io/Bcb-plan/
    markmrq.github.io/Bcb-plan/site/
    markmrq.github.io/Bcb-plan/sitemap/

All three already have a noindex tag, so Google won't crawl them while they're demos.


2) PRIVATE-keep-off-github/
---------------------------
Do NOT upload this folder to the Pages repo.

Why: GitHub Pages serves every committed file by URL, even when the repo is
private. So if the bible or the commercial docs sit in the repo, they're
fetchable on a public address whether the repo is private or not.

Keep these on your laptop, or in a separate repo with Pages switched OFF.

Contents:
    bestcasinobonus-bible.md          (the master doc: strategy, commercials, compliance)
    bestcasinobonus-business-case.md
    acrum-call-notes-2026-06-22.md
    bestcasinobonus-keyword-strategy-sitemap.md
    briefs/  (the Surfer content briefs)


NOTE
----
The flagship in site/ is the version with the International / non-UK tier.
Per the 24 June call, the flagship is regulated-only and the grey tier moves
to separate domains, so that section will eventually move off this prototype.
It's fine as a demo for now.
