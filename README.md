# 愛澤アトラクタ キャンバス

Aizawa方程式パラメータ系（a,b,c,d,e,f）のカオスアトラクタを3D→2D投影でCanvas描画するビジュアライザ。RK4法による高精度数値積分。

## 機能
- Aizawa方程式をRK4法で数値積分しリアルタイム描画
- パラメータ a, b, c, d をスライダーで調整
- 3D投影面の切替（X-Y / X-Z / Y-Z）
- 時間刻み（dt）調整スライダー
- 描画速度調整（ステップ数/フレーム）
- 「停止/再開」・「リセット」ボタン
- 色相変化による軌跡の彩色

## 技術
- Vanilla JS + Tailwind CSS CDN
- RK4（Runge-Kutta 4次法）による微分方程式数値積分
- Off-screen Canvas による軌跡描画
- requestAnimationFrame アニメーション
