# Repository Notes

- This is a static GitHub Pages site for 桃花遊記. Keep copy, route names, pricing, and signup flow consistent across `index.html`, `itinerary.html`, `spots.html`, `food.html`, `budget.html`, `register.html`, and `README.md`.
- Current public-facing signup flow uses 官方 LINE as the central channel for route info, promotions, registration, confirmation, trip details, pickup time, and notices.
- Current budget copy is NT$900–1,200 per person.
- When making changes in a branch or worktree, sync the finished change back into the main folder / `main` branch using Git before reporting completion. Merge, cherry-pick, or `format-patch` plus `git am` are all acceptable.
- After syncing, run `git status -sb` and check local HTML links/assets so stale references do not remain.
