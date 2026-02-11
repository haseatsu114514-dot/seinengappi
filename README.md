# 生年月日逆算ツール

今の年齢と誕生日（月日）から、生年月日を逆算するシンプルなブラウザツールです。  
最大3人まで同時に計算できます。

## 機能
- 最大3人分の入力（名前は任意）
- 年齢 + 誕生日（月/日）から生年月日を推定
- 計算履歴の表示
- 履歴クリア
- `localStorage` に履歴保存（同じブラウザで残る）

## 使い方
1. `index.html` をブラウザで開く
2. 年齢と誕生日（月/日）を入力
3. `生年月日を逆算する` を押す
4. 下部の `履歴` に実行履歴が保存される

## お気に入りから使う方法（GitHub Pages）
1. GitHubのこのリポジトリで `Settings` → `Pages` を開く
2. `Build and deployment` の `Source` を `Deploy from a branch` に設定
3. `Branch` を `main` / `/ (root)` にして保存
4. 公開URL（例: `https://haseatsu114514-dot.github.io/seinengappi/`）を開く
5. ブラウザでお気に入り登録（Windows: `Ctrl + D`, Mac: `Command + D`）

## 補足
- 計算は「今日の日付」を基準にしています。
- オフラインでも、`index.html` を直接開けば利用できます。
