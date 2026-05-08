# mock-exam-timer-flow

模試・タイマー実行フロー は、模試セクション、制限時間、休憩、採点メモを一連の実行フローにするです。

## Closed Alpha Scope

- Rank: 33
- Tier / Score: P1 / 61
- Domain / Idea No: EducationLearning / 3
- 主な公開先: GitHub Pages / GitHub Release
- GitHub: https://github.com/Sunmax0731/mock-exam-timer-flow
- Prerelease: https://github.com/Sunmax0731/mock-exam-timer-flow/releases/tag/v0.1.0-alpha.1

## 実装概要

- `src/core`: 製品プロファイルと代表シナリオ評価
- `src/validators`: 期待結果検証
- `src/report`: 検証レポート生成
- `src/review-model`: レビューゲートと責務モデル
- `src/cli`: `samples/representative-suite.json` の自動検証

## 代表データ

`samples/representative-suite.json` は `happy-path`、`missing-required`、`warning`、`mixed-batch` を含みます。

## 検証

```powershell
cd D:\AI\EducationLearning\mock-exam-timer-flow
cmd.exe /d /s /c npm test
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` を参照してください。
