# Duang777 GitHub 主页（蜡笔小新风）

本目录对应公开仓库 [`Duang777/Duang777`](https://github.com/Duang777/Duang777) 的 profile README。

## 风格

<<<<<<< HEAD
1. Create a public GitHub repository named exactly `Duang777`.
2. Add `README.md` and the `.github/workflows` folder from this directory into that repository.
3. Commit and push to the `main` branch.
4. Open the repository Actions tab and manually run these one at a time:
   - `Metrics`
   - `Contribution Snake`
   - `Profile 3D`
=======
- 配色：小新黄 `#FFD100`、短裤红 `#E63946`、天空蓝 `#87CEEB`、奶油底 `#FFF8E7`
- 文案：轻松调皮，信息仍清楚
- 版面：只保留介绍、精选项目、技能、成绩单、贡献蛇——不再堆 metrics / 3D 图
>>>>>>> a535589 (style: redo profile README in Crayon Shin-chan vibe)

## 同步到 GitHub

```bash
cd github-profile-Duang777
git add README.md SETUP.md
git commit -m "style: redo profile README in Crayon Shin-chan vibe"
git push origin main
```

## Actions（可选）

在仓库 Actions 里按需手动跑一次：

1. **Contribution Snake** — 生成 `dist/github-snake*.svg`
2. **Metrics** / **Profile 3D** — 当前 README 未引用，可停用或删 workflow

## Token

Metrics workflow 如仍启用，可在仓库 Secrets 里配置 `METRICS_TOKEN`（classic PAT，`public_repo`）。贡献蛇通常用默认 `GITHUB_TOKEN` 即可。
