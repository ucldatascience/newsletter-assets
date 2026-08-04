# UCL DSS newsletter images

These five files need to be reachable at a public URL for the newsletter
templates to display them. EmailOctopus doesn't host images for custom HTML
templates, so this folder does.

| File | Used by |
|---|---|
| `logo-circle.png` | Aurora, Deep Field, Dispatch |
| `hero-aurora.jpg` | Aurora |
| `hero-deepfield.jpg` | Deep Field |
| `hero-tessellate.jpg` | Tessellate |
| `rule-dispatch.jpg` | Dispatch |

Don't rename or move them — the templates reference these exact filenames.
If you regenerate the gradients with `gen_assets.py`, copy the new versions in
here and the existing URLs keep working.
