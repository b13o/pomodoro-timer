<img width="1273" alt="pomodoro" src="https://github.com/user-attachments/assets/c73bc7bf-f5bf-4d99-848b-cc29aa8b44a7" />

# ポモドーロタイマー

## 概要

このプロジェクトでは、ポモドーロタイマーを構築します。
25 分の作業、５分の休憩を繰り替えすタイマーを実装し、残り時間を表示します。
時間になったらチャイムが鳴る、一般的なタイマーです。

## 学習目標

さまざまな React Hooks を組み合わせた実装を学習します。

特に、useRef フックを使ったデータ管理と、useState との使い分けについて確認してください。

### 推奨技術

このプロジェクトの難易度と趣旨を踏まえて、以下の使用をお勧めします。

- vite を用いた React 環境構築
- TypeScript による型チェック
- Tailwind CSS を用いたスタイリング
- useState, useRef を用いた値の管理
- useEffect による副作用
- Web Audio API の使用
- GitHub Pages へのデプロイ

---

## 🎯 お題

- 「ユーザーストーリー」を全て満たす、アプリを構築してください。
- 必要に応じて、スクリーンショットやデモサイトの URL を、参照してください。
- なお、スタイルは、あなた自身で独自にカスタマイズすることが可能です。

### 必須機能

1. **タイマー**:
   - 25 分間の作業と、5 分間の休憩を計測できる。
   - 残り時間を、秒単位で表示する。
2. **タイマーの操作**:
   - ボタンをクリックすると、特定の操作ができるボタンを設置する
3. **チャイム**:
   - 継続している時間が０になったら、チャイムが鳴る

## ユーザーストーリー

- [ ] ユーザーがサイトにアクセスすると、タイマーが表示されている
- [ ] 現在のセッションタイプ（作業/休憩）が明確に表示される
- [ ] タイマーの残り時間がリアルタイムで表示される
- [ ] ユーザーは、タイマーを開始、一時停止、再開、リセットできる
- [ ] ユーザーは、セッションタイプ（作業/休憩）の切り替えができる
- [ ] タイマー終了時に、サウンド通知が鳴る
- [ ] タイマー終了時に、セッションモードが切り替わり、自動的にタイマーが開始する
- [ ] アプリケーションがデプロイされており、誰でもアクセス可能である。
