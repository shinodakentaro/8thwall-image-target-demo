### Videos

Place the video files that should play for each recognized image target here.

Currently expected (referenced by `src/.expanse.json` material.textureSrc):
- `target1.mp4` — plays when `target1` is recognized
- `target2.mp4` — plays when `target2` is recognized

Keep files small/compressed (H.264 mp4, short loop) since they load over the
network on mobile. If you rename or add files, update the matching
`textureSrc.asset` path in `src/.expanse.json` and the plane's `geometry`
width/height to roughly match each video's aspect ratio.
