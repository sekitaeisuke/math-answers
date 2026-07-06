# math-answers

中学2年・中学3年 数学 計算問題集（地域教育工房）の **Web解答**。

問題集PDFの各ページ・章扉のQRコードから、その単元の解答にスマホ/タブレットでアクセスできます。

- 目次: `index.html`
- 章ごとの解答: `math2/chN.html` ・ `math3/chN.html`（単元アンカー `#u1-1`）
- 公開URL（GitHub Pages）: https://sekitaeisuke.github.io/math-answers/

## 更新方法

元データは ai-system リポジトリの `data/kyozai_units/math{2,3}_*.json`（問題集PDFと同一）。
更新時は ai-system 側で再生成してこのリポジトリへコピーし直す:

```
python scripts/build_math_answers_web.py
# → output/math_answers_web/ の中身をこのリポジトリにコピーして commit & push
```
