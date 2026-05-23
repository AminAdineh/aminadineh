# Setup Instructions

Your username is detected as **`aminadineh95`** (from the workflow link in your existing README). All asset URLs in `README.md` are already pointing there.

## 1. Create your profile repository (if not done)

GitHub turns a repo named exactly like your username into a profile README:

```
https://github.com/aminadineh95/aminadineh95
```

## 2. Drop these two files in the repo root

```
aminadineh95/
├── README.md                          ← the new creative readme
└── .github/
    └── workflows/
        └── snake.yml                  ← the GitHub Action
```

## 3. Enable workflow permissions

Go to **Repo → Settings → Actions → General → Workflow permissions**
→ select **"Read and write permissions"** → Save.

## 4. Run the action once manually

Go to the **Actions** tab → pick **"🐍 Generate Snake & 3D Profile Animations"** → click **Run workflow**.

It will create an `output` branch containing:
- `github-contribution-grid-snake.svg` (light)
- `github-contribution-grid-snake-dark.svg` (dark)
- `profile-3d-contrib/profile-night-rainbow.svg` (3D skyline)

From then on it auto-updates every 12 hours.

## 5. Visualizations included

| Feature | Source |
|---|---|
| 🐍 Snake eating contributions | [Platane/snk](https://github.com/Platane/snk) |
| 🌌 3D contribution skyline | [yoshi389111/github-profile-3d-contrib](https://github.com/yoshi389111/github-profile-3d-contrib) |
| 📊 GitHub stats / top langs | [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| 🔥 Streak stats | [DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) |
| 🏆 Trophies | [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |
| 📈 Activity graph | [Ashutosh00710/github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) |
| ⌨️ Typing SVG headline | [DenverCoder1/readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) |
| 🎨 Skill icons | [tandpfun/skill-icons](https://github.com/tandpfun/skill-icons) |
| 👁 Profile view counter | [antonkomarev/github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter) |
| 🌊 Waving header/footer | [kyechan99/capsule-render](https://github.com/kyechan99/capsule-render) |

The stats/trophies/streak images render instantly — no action needed for those.
Only the snake and 3D skyline require the workflow.
