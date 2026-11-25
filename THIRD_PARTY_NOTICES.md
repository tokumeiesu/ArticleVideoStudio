# Third-Party Notices / サードパーティーライセンス情報

## Overview / 概要

ArticleVideo Studio uses or may integrate third-party software components.

This document tracks third-party dependencies and their licensing requirements.

ArticleVideo Studioで使用・連携する外部ソフトウェアのライセンス情報を管理します。

**Audit status: In progress / 監査中**

The project's preferred license candidate is GPL-3.0-only. Final adoption is subject to dependency and redistribution compliance review.

## 1. Framework and Runtime / フレームワーク・ランタイム

### Avalonia UI

- Project: https://github.com/AvaloniaUI/Avalonia
- License: MIT (core open-source framework)
- Exact version: To be verified
- Distribution status: To be verified
- License notice: Pending verification

### .NET Runtime

- Project: https://github.com/dotnet/runtime
- License information: See the upstream repository and bundled notices
- Exact version: To be verified
- Distribution status: To be verified
- License notice: Pending verification

## 2. Media Processing / メディア処理

### FFmpeg

- Project: https://ffmpeg.org/
- License: LGPL or GPL depending on build configuration and linked libraries
- Exact version: To be verified
- Build configuration: To be verified
- Distribution status: To be verified
- License notice: Pending verification

## 3. Speech and AI / 音声・AI

### VOICEVOX Integration

- Project: https://voicevox.hiroshiba.jp/
- Integration method: To be verified
- Redistributed components: To be verified
- Applicable licenses and terms: To be verified

### AI Inference Engines and Models

- Engines: To be verified
- Models: To be verified
- Model-specific licenses: To be verified
- Bundled model weights: To be verified

Model licenses and usage conditions must be reviewed separately from application source-code licenses.

## 4. Additional Dependencies / その他の依存関係

The following must be inventoried:

- Direct NuGet packages
- Transitive NuGet packages
- Native libraries
- Fonts and icons
- Media assets
- Android-specific dependencies
- Windows installer components
- Linux packaging components

## 5. Platform Distribution / OS別配布

| Platform | Audit Status |
|---|---|
| Windows x64 | Pending |
| Linux amd64 | Pending |
| Android ARM64 | Pending |
| macOS | Not yet released |

## 6. Required Actions / 必要な作業

- [ ] Identify all bundled third-party components
- [ ] Record exact versions and source repositories
- [ ] Verify license identifiers and license texts
- [ ] Verify compatibility with GPL-3.0-only
- [ ] Preserve required copyright notices
- [ ] Include required license texts in distribution packages
- [ ] Verify source-code availability obligations
- [ ] Review binary redistribution conditions
- [ ] Update this document using verified audit results

## 7. Important Notice / 注意事項

This document is a preliminary audit inventory, not a complete or certified list of redistributed components.

この文書は暫定的な監査台帳であり、配布物に含まれるすべての依存ライブラリを確認したものではありません。

The inclusion of a component does not necessarily mean it is bundled with the current release.

記載されたコンポーネントが現在の配布物に同梱されているとは限りません。
