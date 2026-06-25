# Taha Gamal Alieldin — Portfolio

A single-page portfolio site. No build step, no dependencies — just static files you push to GitHub.

## 1. Folder structure (what goes where)

```
portfolio/
├── index.html                       ← the site (already done)
├── Taha_Gamal_Alieldin_CV.pdf       ← your CV (add this)
├── images/
│   ├── Swarm_-_Image.jpeg
│   ├── Machine_Vision_-_Image.jpeg
│   ├── Rotary_furuta_pendulum_-_image.jpeg
│   ├── Electro-Pneumatic_-_image.jpeg
│   ├── Automarion-_image.jpeg
│   └── plate-_Image.jpeg
└── reports/
    ├── Surveying_Swarm_Report.pdf
    ├── Human_Behavior_Recognition_Report.pdf
    ├── Furuta_Pendulum_Report.pdf
    ├── Humanoid_Arm_Pneumatic_Report.pdf
    ├── Industrial_Automation_Report.pdf
    └── Chassis_Plate_FEA_Report.pdf
```

## 2. Add your files

The site already references the filenames above, so just drop your files in with those exact names:

- **6 project images** → put them in `images/` using the exact names listed (these are the same filenames you already had).
- **6 reports** → save each project's PDF into `reports/` with the exact name the site expects:

  | Project | Save the PDF as |
  |---|---|
  | Autonomous Surveying Swarm | `Surveying_Swarm_Report.pdf` |
  | Human Behavior Recognition (CNN-LSTM) | `Human_Behavior_Recognition_Report.pdf` |
  | Furuta Pendulum Control | `Furuta_Pendulum_Report.pdf` |
  | Pneumatic Humanoid Arm | `Humanoid_Arm_Pneumatic_Report.pdf` |
  | Industrial Automation (Factory I/O) | `Industrial_Automation_Report.pdf` |
  | Mobile-Robot Chassis Plate (FEA) | `Chassis_Plate_FEA_Report.pdf` |

  If you don't have a report for one of them, just delete that project's `<div class="card-links"> … </div>` block in `index.html` and the "Read report" link disappears.
- **CV** → put `Taha_Gamal_Alieldin_CV.pdf` in the top folder (next to `index.html`).

If an image is missing, the site shows a neat placeholder instead of a broken icon — so it won't look broken while you fill things in.

## 3. Put it on GitHub + get the public link

You only need a browser for this.

1. Go to **github.com** → sign in (or create a free account).
2. Click **New repository**. Name it whatever you like, e.g. `portfolio`. Set it to **Public**. Click **Create repository**.
3. On the new repo page, click **uploading an existing file** (or **Add file → Upload files**).
4. Drag in **everything**: `index.html`, the `images` folder, the `reports` folder, and the CV PDF. Click **Commit changes**.
5. Go to the repo's **Settings** tab → **Pages** (left sidebar).
6. Under **Build and deployment → Source**, choose **Deploy from a branch**. Set the branch to **`main`** and the folder to **`/ (root)`**. Click **Save**.
7. Wait ~1 minute, then refresh. GitHub shows your live link at the top of that Pages screen:

   ```
   https://YOUR-USERNAME.github.io/portfolio/
   ```

   That is the link you send to recruiters.

### Tip — a cleaner link (optional)
If you name the repository exactly **`YOUR-USERNAME.github.io`**, the site publishes at
`https://YOUR-USERNAME.github.io/` (no `/portfolio` on the end). Same steps otherwise.

## 4. Updating later
To change anything, edit the file on GitHub (or re-upload) and commit. The live site updates automatically in about a minute.

## Editing the content
Everything is plain HTML in `index.html`. To tweak a project, search for its title (e.g. `Furuta`) and edit the text right there. To add a new project, copy one `<article class="card"> … </article>` block and change the image path, title, and text.
