# COMC Purchase History Helper — Privacy Policy

COMC購入履歴ヘルパーのプライバシーポリシーを公開するためのリポジトリです。

- [日本語](privacy-ja.html)
- [English](privacy-en.html)
- 運営者 / Operator: Takumetal
- お問い合わせ / Contact: [X @takumetal55](https://x.com/takumetal55)（DM、返信・メンション / DM, reply or mention）

COMC公式とは無関係の補助ツールです。

This repository contains the static privacy-policy website for COMC Purchase History Helper, an unofficial Chrome extension that is not affiliated with COMC.

## Files and publication

Only these seven files belong in this repository:

- `privacy-ja.html`: Japanese policy
- `privacy-en.html`: English policy
- `index.html`: exact copy of the English policy
- `ui.css`: local stylesheet
- `.nojekyll`: serve static files without Jekyll processing
- `README.md`: this document
- `.gitignore`: ignore all files except this explicit list

Use GitHub Pages with the `main` branch and `/(root)` folder as its publishing source. No custom build workflow or package installation is required.

## Updates

Generate the website from the policy sources maintained with the extension, then copy only the five website files listed above. Keep the Japanese and English policies identical to the copies bundled with the extension.

Before publishing, review the complete file list, the diff and the commit author, and check for secrets. After publishing, check both languages, links and stylesheet over HTTPS without signing in.

GitHub Pages records visitors' IP addresses for security purposes, as described in each policy. These pages contain no scripts, analytics, embedded services or uploaded purchase records.
