# agentic-shorts-media

Public hosting for **Agentic Shorts** media that has been approved for Instagram.

The publish workflow in the (private) content repo copies each approved post here as
`posts/<slug>/slide_XX.jpg` and `posts/<slug>/reel.mp4`. Instagram then downloads the files from
commit-pinned `raw.githubusercontent.com` URLs (slides) or GitHub Pages (Reels, which need `video/mp4`).

Everything here is posted publicly anyway. Please don't edit by hand: files are written by the workflow.
