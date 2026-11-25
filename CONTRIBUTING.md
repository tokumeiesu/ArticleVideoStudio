# Contributing to ArticleVideo Studio

Thank you for your interest in ArticleVideo Studio!

ArticleVideo Studioへの関心とご協力に感謝します。

ArticleVideo Studioは、人間とAIが共通のタイムラインを使用し、GUIと自然言語によって動画を共同制作することを目指すクロスプラットフォーム動画編集プロジェクトです。

## 1. Current Project Status / 現在の開発状況

The first preview release, `v0.1.0-preview.1`, is available for Windows x64, Linux amd64, and Android ARM64.

現在、初回プレビュー版を公開しています。

The full application source code has not yet been published. Source-code contributions and pull requests will be considered after the source code and licensing terms have been prepared.

アプリケーションの完全なソースコードは現在公開準備中です。コードの変更を伴う貢献については、ソースコードとライセンスの整備後に受け付ける予定です。

## 2. Bug Reports / 不具合報告

Please report bugs through [GitHub Issues](https://github.com/tokumeiesu/ArticleVideoStudio/issues).

不具合報告には、可能な限り次の情報を含めてください。

- Application version / アプリのバージョン
- Operating system / OSとバージョン
- Device and architecture / 端末とCPUアーキテクチャ
- Steps to reproduce / 再現手順
- Expected and actual behavior / 期待した動作と実際の動作
- Screenshots or logs / スクリーンショットやログ

Do not include passwords, API keys, personal information, or private project files.

## 3. Feature Requests / 機能提案

Feature requests and improvement ideas are welcome through GitHub Issues and Discussions.

機能提案では、解決したい問題、期待する動作、対象OS、参考資料などを記載してください。

## 4. Development Principles / 開発原則

The project follows these architectural principles:

### Cross-platform consistency

Windows, Linux, macOS, and Android are intended to provide a consistent user experience.

OS-specific limitations should be handled through platform adapters rather than forcing identical internal implementations.

### Shared editing architecture

GUI operations and AI-assisted operations should use common editing commands and a shared project/timeline model.

### Centralized input handling

Keyboard shortcuts should be managed through a central Input Router.

Drag-and-drop and copy/paste operations should be coordinated through a shared Transfer Manager.

### Non-destructive editing

Editing operations should support undo/redo and preserve project data wherever possible.

### Local-first AI

Local AI integration is a central development goal. External AI services may be supported where appropriate.

### Modular workspaces

New capabilities should be introduced through modular workspaces and docks whenever practical.

## 5. Pull Requests / プルリクエスト

Once source-code contributions are enabled, contributors should:

1. Discuss significant changes in an Issue before implementation.
2. Keep changes focused and compatible with the shared architecture.
3. Avoid unnecessary platform-specific UI differences.
4. Include build or test results where possible.
5. Document new dependencies and their licenses.
6. Avoid committing AI models, credentials, signing keys, personal media, or generated files.

Pull requests may remain unavailable until the source code and project license are published.

## 6. Security / セキュリティ

Please do not publish passwords, signing keys, API tokens, or sensitive user data.

Potential security vulnerabilities should not be disclosed in public Issues before a private reporting process has been established.

## 7. Community / コミュニティ

Please communicate respectfully and constructively.

Japanese and English are both welcome.

日本語・英語のどちらでも参加できます。

Thank you for helping improve ArticleVideo Studio!
