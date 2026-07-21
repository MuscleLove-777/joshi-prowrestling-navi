# 女子プロレスナビ - リモートエージェント更新ガイド

## サイト概要
- サイト名: 女子プロレスナビ
- URL: https://musclelove-777.github.io/joshi-prowrestling-navi/
- 運営: MuscleLove
- テーマ: 女子プロレスの最新情報を毎日配信するファンサイト

## 掲載対象（ロスター）
記事対象の団体・選手リストは必ず `references/roster.md` を読んで参照すること。リストの追加・更新もそのファイルに対して行う。

## 記事テンプレート

新しい記事を作成する際は以下のテンプレートを使用すること。

### ファイル命名規則
`articles/[スラッグ].html`
- 英語のケバブケースで命名
- 例: `articles/stardom-cinderella-tournament-2026.html`

### HTML テンプレート
```html
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>[記事タイトル] | 女子プロレスナビ</title>
<meta name="description" content="[120文字以内の説明文]">
<link rel="canonical" href="https://musclelove-777.github.io/joshi-prowrestling-navi/articles/[スラッグ].html">

<meta property="og:title" content="[記事タイトル]">
<meta property="og:description" content="[説明文]">
<meta property="og:type" content="article">
<meta property="og:url" content="https://musclelove-777.github.io/joshi-prowrestling-navi/articles/[スラッグ].html">
<meta property="og:image" content="[Unsplash画像URL w=1200&h=630&fit=crop]">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@MuscleGirlLove7">

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "[記事タイトル]",
  "datePublished": "[YYYY-MM-DD]",
  "dateModified": "[YYYY-MM-DD]",
  "author": {"@type": "Organization", "name": "MuscleLove"},
  "publisher": {"@type": "Organization", "name": "女子プロレスナビ"},
  "image": "[Unsplash画像URL]"
}
</script>

<!-- 記事ページ共通スタイル（既存記事からコピー） -->
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#0d1117;--bg2:#161b22;--bg3:#21262d;--text:#e6edf3;--text2:#8b949e;--accent:#ff6b00;--accent2:#ff8c33;--radius:12px}
body{font-family:'Segoe UI','Hiragino Sans','Meiryo',sans-serif;background:var(--bg);color:var(--text);line-height:1.8}
a{color:var(--accent);text-decoration:none}a:hover{color:var(--accent2)}
.site-header{background:var(--bg2);border-bottom:1px solid var(--bg3);padding:12px 20px}
.header-inner{max-width:800px;margin:0 auto;display:flex;align-items:center;justify-content:space-between}
.logo{font-size:1.2rem;font-weight:800;color:var(--text)}.logo span{color:var(--accent)}
.back-link{font-size:.85rem;color:var(--text2)}
.article-hero{width:100%;max-height:400px;overflow:hidden}
.article-hero img{width:100%;height:400px;object-fit:cover}
.article-container{max-width:800px;margin:0 auto;padding:40px 20px}
.article-meta{display:flex;gap:12px;font-size:.85rem;color:var(--text2);margin-bottom:16px}
.article-tag{padding:2px 10px;border-radius:10px;font-weight:600;font-size:.78rem}
h1{font-size:1.8rem;font-weight:900;line-height:1.4;margin-bottom:24px}
.article-content p{margin-bottom:20px;color:var(--text);font-size:1rem}
.article-content h2{font-size:1.3rem;font-weight:700;margin:32px 0 16px;padding-left:12px;border-left:4px solid var(--accent)}
.article-content ul{margin:0 0 20px 24px;color:var(--text2)}.article-content li{margin-bottom:8px}
.article-footer{margin-top:40px;padding-top:24px;border-top:1px solid var(--bg3);text-align:center}
.article-footer a{display:inline-block;padding:10px 28px;background:var(--accent);color:#fff;border-radius:8px;font-weight:700;font-size:.9rem}
.site-footer{background:var(--bg2);border-top:1px solid var(--bg3);padding:20px;text-align:center;font-size:.8rem;color:var(--text2);margin-top:48px}
</style>
</head>
<body>
<header class="site-header">
  <div class="header-inner">
    <a href="../" class="logo"><span>&#9733;</span> 女子プロレスナビ</a>
    <a href="../" class="back-link">&larr; トップに戻る</a>
  </div>
</header>

<div class="article-hero">
  <img src="[Unsplash画像URL w=1200&h=400&fit=crop]" alt="[画像の説明]">
</div>

<article class="article-container">
  <div class="article-meta">
    <span class="article-tag">[団体名/カテゴリ]</span>
    <time datetime="[YYYY-MM-DD]">[YYYY年MM月DD日]</time>
  </div>

  <h1>[記事タイトル]</h1>

  <div class="article-content">
    <!-- 記事本文をここに -->
  </div>

  <div class="article-footer">
    <a href="../">トップページへ戻る</a>
  </div>
</article>

<!-- ML_PROMO_CARD_START -->
<section style="max-width:800px;margin:32px auto;padding:0 20px;">
  <div style="background:#111827;border:1px solid rgba(255,255,255,0.14);border-radius:10px;padding:24px;text-align:center;">
    <p style="margin:0 0 6px;color:#f0f0f5;font-weight:800;">MuscleLove 公式</p>
    <p style="margin:0 0 14px;color:#9ca3af;font-size:0.9rem;">最新情報・限定コンテンツはこちら</p>
    <div style="display:flex;flex-wrap:wrap;gap:10px;justify-content:center;">
      <a href="https://x.com/MuscleGirlLove7" target="_blank" rel="noopener" style="display:inline-block;padding:10px 18px;background:#1d9bf0;color:#fff;border-radius:6px;font-weight:800;text-decoration:none;">X @MuscleGirlLove7</a>
      <a href="https://www.patreon.com/MuscleLove" target="_blank" rel="noopener" style="display:inline-block;padding:10px 18px;background:#ff424d;color:#fff;border-radius:6px;font-weight:800;text-decoration:none;">Patreon 限定コンテンツ</a>
      <a href="https://musclelove-games.vercel.app/?utm_source=blog&amp;utm_medium=promo_card&amp;utm_campaign=joshi-prowrestling-navi" target="_blank" rel="noopener" style="display:inline-block;padding:10px 18px;background:#22c55e;color:#0b1220;border-radius:6px;font-weight:800;text-decoration:none;">🎮 無料ブラウザゲームで遊ぶ</a>
    </div>
  </div>
</section>
<!-- ML_PROMO_CARD_END -->

<footer class="site-footer">
  &copy; 2026 MuscleLove. All rights reserved. | 女子プロレスナビ
</footer>
</body>
</html>
```

### 団体タグカラー
- STARDOM: `background:rgba(229,0,79,.15);color:#e5004f`
- MARIGOLD: `background:rgba(255,215,0,.15);color:#ffd700`
- WWE: `background:rgba(0,114,206,.15);color:#0072ce`
- AEW: `background:rgba(200,166,0,.15);color:#c8a600`
- 特集: `background:rgba(255,107,0,.15);color:#ff6b00`

## Unsplash画像の使い方
記事のヒーロー画像にはUnsplashの画像を使用する。直接選手の画像は使用不可（著作権）。

### 推奨画像カテゴリ
- レスリングリング: `https://images.unsplash.com/photo-1517438476312-10d79c077509`
- アリーナ: `https://images.unsplash.com/photo-1565992441121-4367c2967103`
- スポーツアリーナ: `https://images.unsplash.com/photo-1578022761797-b8636ac1773c`
- ボクシングリング: `https://images.unsplash.com/photo-1549719386-74dfcbf7dbed`
- 格闘技: `https://images.unsplash.com/photo-1555597673-b21d5c935865`

画像URLにはサイズパラメータを付与すること:
- サムネイル: `?w=600&h=400&fit=crop`
- ヒーロー: `?w=1200&h=400&fit=crop`
- OGP: `?w=1200&h=630&fit=crop`

## 更新ルール

### 毎日の更新手順
1. **WebSearchで最新ニュースを検索**
   - 「女子プロレス 最新ニュース 今日」
   - 「STARDOM 試合結果」
   - 「MARIGOLD 試合結果」
   - 「WWE 女子 ニュース」
   - 「AEW 女子 ニュース」

2. **記事3本を生成**
   - 試合結果レポート x1
   - 選手特集/インタビューまとめ x1
   - 団体ニュース/コラム x1

3. **articles/ に保存**
   - ファイル命名: `[スラッグ].html`
   - テンプレートに従いHTMLを作成
   - Unsplash画像をヒーローに設定

4. **index.html を更新**
   - 最新記事3件をarticles-gridに表示（古い記事は下に移動）
   - 新選手がいれば選手カードを追加

5. **sitemap.xml を更新**
   - 新しい記事のURLを追加
   - lastmodを更新

6. **git commit & push**
   ```bash
   git add -A
   git commit -m "記事更新: [日付] [記事概要]"
   git push origin master
   ```

### 記事品質基準
- 1記事あたり500-1000文字
- h2見出し2-4個
- 箇条書きを適宜使用
- 団体名・選手名は正確に
- 事実に基づいた内容（推測は明記）
- SEO: タイトル60文字以内、description120文字以内
- 全記事とindex.htmlのフッター直前に MuscleLove広告カード（ML_PROMO_CARDマーカー）を必ず含める。広告カードにはX / Patreon / ゲームポータルの3導線を必ず入れる

### 注意事項
- 選手の写真は使用しない（著作権）。Unsplashのフリー画像のみ使用
- 公式発表のない情報は「報道によると」等で明記
- 誹謗中傷・差別的表現は絶対に使用しない
- 試合結果のネタバレには配慮する（記事タイトルで結果を明かさない工夫）
