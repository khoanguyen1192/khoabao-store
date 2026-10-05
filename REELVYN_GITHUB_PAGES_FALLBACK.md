# Reelvyn stable policy hosting — 2026-10-05

Source remains the existing private khoanguyen1192/khoabao-store repository.

Firebase Hosting is the studio default. The existing kb-technology-aa0a0 live site hosts Kinetiny; the available scoped Firebase artifact is preview-only and must not replace that live site. Migrating the entire portfolio/domain is outside this change.

Documented fallback: use this repository's already configured GitHub Pages deployment (main, /docs, custom domain lessbyte.app, HTTPS enforced). Publish only docs/apps/reelvyn and this record; preserve all other app files and every Firebase configuration. No new site, repository, credentials, DNS change or paid plan is required.

Stable routes: /apps/reelvyn/privacy/, /apps/reelvyn/terms/, /apps/reelvyn/support/. Content is EN/VI and explicitly describes the controlled beta, pending public production acceptance and provider permission/data-handling confirmation. The Terms link Apple Standard EULA. Stable hosting does not satisfy the separate provider or production acceptance gates.

Before publication the three stable routes returned HTTP404: source files were local/untracked and absent from deployed main. Verify public HTTP200, page identity and stylesheet after publication. Do not use the expiring Firebase preview as a canonical App Store URL.
