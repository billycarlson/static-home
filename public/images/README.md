# Company images

One per role, shown in the left meta column beside the dates.

| File | Role |
|---|---|
| `iherb.jpg` | iHerb |
| `kpmg.jpg` | KPMG Canada |
| `balsamiq.jpg` | Balsamiq |
| `kehe.jpg` | KeHE |
| `hcsc.jpg` | Health Care Service Corporation |
| `threadless.jpg` | Threadless / Bucketfeet |

Each `<figure>` is commented out in `index.html` so nothing 404s before the
file exists — drop the image in, uncomment that block, and fill in `alt`,
`width` and `height` (intrinsic pixel size, so the row doesn't reflow on load).

The column is a third of the grid — about 320px wide at desktop. The
box takes the image's own proportions, so any aspect ratio works as long as
all six are consistent.
