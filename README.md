# zeabur-oss-sync

Automated GitHub Actions workflow to keep all forked `zeabur-oss` repositories synced with upstream.

## Monitored Forks
- [cpsc/zeabur](https://github.com/cpsc/zeabur) <- [zeabur-oss/zeabur](https://github.com/zeabur-oss/zeabur)
- [cpsc/identity](https://github.com/cpsc/identity) <- [zeabur-oss/identity](https://github.com/zeabur-oss/identity)
- [cpsc/catalog](https://github.com/cpsc/catalog) <- [zeabur-oss/catalog](https://github.com/zeabur-oss/catalog)
- [cpsc/kubesolo](https://github.com/cpsc/kubesolo) <- [zeabur-oss/kubesolo](https://github.com/zeabur-oss/kubesolo)
- [cpsc/builder](https://github.com/cpsc/builder) <- [zeabur-oss/builder](https://github.com/zeabur-oss/builder)
- [cpsc/design-system](https://github.com/cpsc/design-system) <- [zeabur-oss/design-system](https://github.com/zeabur-oss/design-system)
- [cpsc/website](https://github.com/cpsc/website) <- [zeabur-oss/website](https://github.com/zeabur-oss/website)

## Schedule
Runs automatically every 30 minutes via GitHub Actions (`.github/workflows/sync.yml`).
Can also be triggered manually via Workflow Dispatch.
