Place photos for the site in this folder using these filenames (recommended):

- `featured.jpg`        (used for the featured card on the Home page)
- `andrew-johnson.jpg`  (author page hero)
- `jenny-wilson.jpg`
- `guy-hawkins.jpg`
- `kristin-watson.jpg`
- `floyd-miles.jpg`

Guidelines:
- Use appropriate crop for each slot:
	- `featured.jpg`: wide landscape, at least 1200×600 for good quality.
	- author photos: square, min 300×300 (600×600 recommended).
- Supported formats: JPG, PNG, WebP. SVG is okay for logos but not for photographs.
- Filenames must match exactly (lowercase, dashes) to be displayed automatically.

How to add your photo:
1. Save the image you attached as `featured.jpg`.
2. Copy it into this folder: `assets/photos/featured.jpg`.
	 Example PowerShell command (from project root):

```powershell
mkdir -Force assets\photos
Copy-Item "C:\path\to\your\downloaded\photo.jpg" assets\photos\featured.jpg
```

3. Refresh the page in your browser (http://localhost:8000/index.html).

If you want, I can create a placeholder `featured.jpg` now so you see the layout immediately — or I can copy the file for you if you give the local path to the image on this machine.