# Synchro LOS Parser

A simple, browser-based tool for traffic engineers to convert Synchro report `.txt` files into formatted Excel LOS summary tables — no coding required.

---

## What it does

- Accepts any Synchro text report (HCM TWSC or Signalized Timings format)
- Extracts **intersection name, node number, control type, approach, lane group, delay, and LOS** for every intersection
- Outputs a formatted `.xlsx` file with the same column structure as your LOS template
- Works entirely in the browser — no data is uploaded to any server

---

## How to use the tool

1. Open the deployed website (see GitHub Pages setup below).
2. Drop your Synchro `.txt` report onto the upload area, or click to browse.
3. Click **Generate Excel File**.
4. The Excel file downloads automatically. Open it in Excel.

---

## How to set up the GitHub repository (step-by-step)

### Step 1 — Create a GitHub account

If you don't already have one, go to [github.com](https://github.com) and sign up for a free account.

---

### Step 2 — Create a new repository

1. Once logged in, click the **+** icon in the top-right corner and choose **New repository**.
2. Fill in:
   - **Repository name:** `synchro-los-parser` (or any name you like)
   - **Description:** *(optional)* `Convert Synchro reports to Excel LOS tables`
   - **Visibility:** Public *(required for free GitHub Pages hosting)*
3. Check **"Add a README file"**.
4. Click **Create repository**.

---

### Step 3 — Upload the project files

You have two options: using the GitHub website (easiest) or using Git on your computer.

#### Option A — Upload via the GitHub website (no coding required)

1. On your new repository page, click **Add file → Upload files**.
2. Drag and drop (or browse to select) these two files:
   - `index.html`
   - `README.md`
3. At the bottom, type a commit message like `Add Synchro LOS parser`.
4. Click **Commit changes**.

#### Option B — Upload via Git command line

```bash
# Clone the empty repo (replace YOUR_USERNAME with your GitHub username)
git clone https://github.com/YOUR_USERNAME/synchro-los-parser.git
cd synchro-los-parser

# Copy index.html and README.md into this folder, then:
git add .
git commit -m "Add Synchro LOS parser"
git push origin main
```

---

### Step 4 — Enable GitHub Pages (free web hosting)

GitHub Pages turns your repository into a live website — for free.

1. In your repository, click **Settings** (the gear icon in the top navigation).
2. In the left sidebar, click **Pages**.
3. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**.
5. GitHub will display a green banner with your site URL:
   `https://YOUR_USERNAME.github.io/synchro-los-parser/`

It typically takes 1–2 minutes to go live. Refresh the page if it isn't available immediately.

---

### Step 5 — Share the link

Send the URL to anyone who needs to use the tool. They just need a web browser — no software installation required.

---

## Updating the tool

Whenever you want to update the tool (e.g., after this README is replaced with a new version of `index.html`):

1. Go to your repository on GitHub.
2. Click on `index.html`.
3. Click the **pencil (edit) icon**.
4. Paste the new content.
5. Click **Commit changes**.

The website updates automatically within a minute or two.

---

## Supported Synchro formats

| Format | Supported |
|--------|-----------|
| HCM 7th TWSC (unsignalized) | ✅ |
| Signalized Timings | ✅ |
| All peak periods (AM, PM, SAT) | ✅ |
| Synchro 6 through 12 | ✅ |

---

## Output columns

| Column | Description |
|--------|-------------|
| Synchro Node # | Intersection number from the report |
| Control | U = Unsignalized, S = Signalized |
| Intersection | Reformatted as "Major Road at Minor Road" |
| Approach | EB / WB / NB / SB / Overall |
| Lane Group | L, T, R, LT, TR, LR, LTR, Approach, or Overall |
| Existing Delay | Delay (s/veh) from the uploaded report |
| Existing LOS | Computed or extracted LOS letter |
| No-Build / Build / Build with Mitigation | Blank columns ready for you to fill in |

---

## License

MIT — free to use, modify, and share.
