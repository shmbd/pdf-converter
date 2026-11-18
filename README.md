# PDF Studio — Editable PDF, EPUB & Word Converter

A **100% browser-based** converter (zero server uploads, no page limits) designed to convert:
1. **Bangladesh Gazette / Bijoy ANSI (`SutonnyMJ`) & Broken Unicode Bangla (`Nikosh`) PDFs** → Clean logical Unicode Bangla & English (by decoding TrueType `cmap` + OpenType `GSUB` tables directly in the browser).
2. **Scanned PDFs with Hidden OCR Layers** → Clean, deskewed, directly editable vector-text PDFs with automatic chapter bookmarks and OCR typo cleanup.
3. **Raw Image Scans** → In-browser English + বাংলা OCR via `Tesseract.js`.

## Outputs
- **Editable `.pdf`** (Crisp vector text, clickable chapter bookmarks, `/ActualText` Unicode Bangla copy-paste & search support)
- **Reflowable `.epub`** (Standard EPUB 3.0 with chapters, clickable Table of Contents, and HTML tables)
- **Editable `.docx`** (Microsoft Word / Google Docs format with paragraphs, headings, indents, and tables)
- **Clean `.txt`** (+ One-Click Copy All & Live In-Browser Page Editor)

---

## How to Get Your Bookmarkable GitHub Pages Link (60 Seconds)

1. Go to **[github.com/new](https://github.com/new)**:
   - **Repository name:** `pdf-converter` (or any name you like)
   - Select **Public** → Click **Create repository**.
2. Click **uploading an existing file** on the next screen:
   - Drag and drop **`index.html`**, **`README.md`**, and **`.nojekyll`** from this folder into GitHub.
   - Click **Commit changes**.
3. Activate your live link:
   - Go to your repository's **Settings** tab → **Pages** (in the left sidebar).
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Select branch **`main`** and folder **`/ (root)`**, then click **Save**.
4. Wait ~30–60 seconds and refresh that Pages screen — your permanent bookmarkable link will appear at:
   `https://<your-github-username>.github.io/pdf-converter/`

*(You can also open `index.html` directly on any PC by double-clicking it!)*
