# 千葉エネルギー研究会｜CHIBA ENERGY RESEARCH INSTITUTE

千葉エネルギー研究会の公式サイト（静的・単一HTML構成）。系統用蓄電池 × 土地活用を軸に、千葉のエネルギーを支える企業ネットワーク。

公開URL：**https://chiba-energy-lab.github.io/**

## サイト構成（リポジトリのルート＝サイトのルート）
- `/`（`index.html`）… トップ＝研究会ハブ（加盟企業・千葉発サービス・問い合わせ）
- `/grid-battery/` … 系統用蓄電池 特設（参考価格・特設窓口 043-308-4403）
- `/chiba-land-search/` … 土地探し・用地募集 特設
- `/assets/`, `各ページ/assets/` … ロゴ・背景（実写を入れる場合は同名で差し替え）

公式LINE：https://page.line.me/943gsxcu ／ 特設窓口：043-308-4403

## 公開（GitHub Pages・組織アカウント）
本リポジトリは **`chiba-energy-lab` 組織**の **`chiba-energy-lab.github.io`** という名前で作成すること（この名前だとルート配信になります）。
1. Settings ▸ Pages ▸ Build and deployment
2. Source = **Deploy from a branch** ／ Branch = **main** ／ フォルダ = **`/ (root)`** ▸ Save
3. 1〜2分で **https://chiba-energy-lab.github.io/** に公開

## 写真の差し替え（任意）
各 `assets/` に置くと背景が実写に自動で切り替わります（無ければベクター背景）。
- `hero.jpg`／`battery.jpg`／`land.jpg`／`members.jpg`（集合写真）

## 注意（方針）
- 価格・可否・効果は断定せず「税別・参考・要確認」を併記。
- 個人情報・案件データは本リポジトリに置かない。
