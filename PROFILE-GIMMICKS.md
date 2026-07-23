# Profile gimmick shelf

Saved alternatives for the animated slot at the bottom of the profile.

Nothing in this file is linked from the root `README.md`. The current profile
continues to show only the contribution snake.

## Contribution games

| Alternative | What it does | Source |
| --- | --- | --- |
| Snake and Commits | Plays Snake across the contribution graph. Current choice. | [dahan8473/snake-and-commits](https://github.com/dahan8473/snake-and-commits) |
| Arcade Contribution Graph | Generates Pac-Man, Breakout, Galaga, Puzzle Bobble, Bomberman, or Minesweeper SVGs. | [abozanona/pacman-contribution-graph](https://github.com/abozanona/pacman-contribution-graph) |
| GitHub Breakout | Turns contribution cells into an animated Breakout board with light and dark variants. | [cyprieng/github-breakout](https://github.com/cyprieng/github-breakout) |
| Contribution Crawl | Turns the contribution graph into a small animated dungeon crawler. | [MaskiCoding/Contribution-Crawl](https://github.com/MaskiCoding/Contribution-Crawl) |
| Issue Minesweeper | Lets visitors play Minesweeper through pre-filled GitHub issues and a workflow. | [Example and implementation notes](https://dev.to/adrijshikhar/building-an-agentic-era-github-profile-readme-2ijf) |
| 3D contribution calendar | Generates a themed 3D contribution calendar once per day. | [yoshi389111/github-profile-3d-contrib](https://github.com/yoshi389111/github-profile-3d-contrib) |

## Original Koala concepts

- [Night Shift](concepts/koala-vibe-coding/koala-night-shift.svg):
  focused typing, terminal glow, coffee, and a `vibing -> vibe coded -> shipped`
  status loop.
- [Cozy Build](concepts/koala-vibe-coding/koala-cozy-build.svg):
  warm desk scene with a tiny idea-to-release loop.
- [Deploy and Chill](concepts/koala-vibe-coding/koala-deploy-and-chill.svg):
  reclining koala, laptop build progress, deploy, then chill.

These are standalone SVG prototypes. They have no network dependencies and do
not currently run in the profile workflow.

## Rotation idea

Keep exactly one stable image URL in the profile:

```text
https://raw.githubusercontent.com/Shik3i/Shik3i/output/profile-gimmick.svg
```

A daily workflow can generate several candidates, select one by day of year,
and publish the selected file as `profile-gimmick.svg`.

Suggested seven-day rotation:

1. Snake
2. Night Shift
3. Breakout
4. Cozy Build
5. Pac-Man
6. Contribution Crawl
7. Deploy and Chill

Before enabling this:

- Pin third-party actions to a release or commit.
- Keep `permissions` limited to `contents: write`.
- Generate light and dark variants where supported.
- Preserve one visual slot instead of stacking animations.
- Review each third-party workflow instead of copying its example unchanged.
