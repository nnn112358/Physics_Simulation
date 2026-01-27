# 2D LiDAR Robot Simulator (HTML版)

ブラウザで動作する2D LiDARロボットシミュレーター。外部依存なし、HTMLファイルを開くだけで使用可能。

## 実行方法

```bash
# ブラウザで開く
open lidar_simulator.html        # macOS
xdg-open lidar_simulator.html    # Linux
start lidar_simulator.html       # Windows
```

## 操作方法

### キーボード

| キー | 機能 |
|------|------|
| `W` / `S` | 前進 / 後退 |
| `A` / `D` | 左回転 / 右回転 |
| `Space` | 停止 |
| `R` | 位置リセット |
| `L` | LiDAR表示モード切替 |
| `M` | LiDARウィンドウモード切替 |
| `Z` | 障害物編集モード切替 |
| `Arrow Keys` | ビューのパン |
| `PgUp` / `PgDn` | ズームイン / アウト |

### マウス

| 操作 | 機能 |
|------|------|
| 左ドラッグ | ビューのパン |
| ホイール | ズーム |
| 左クリック（編集モード） | 障害物の頂点追加 |
| 右クリック（編集モード） | 最後の障害物を削除 |

## 表示モード

### メインビュー（Lキー）
0. Line+Point - レーザー線 + 点群
1. Point Only - 点群のみ（赤）
2. Color - 距離に応じた色付き点群
3. Line Only - レーザー線のみ

### LiDARウィンドウ（Mキー）
0. Polar - 極座標表示（レーダー風）
1. Cartesian - 直交座標表示
2. Graph - 角度 vs 距離グラフ

## 仕様

- LiDAR: 768点、240°スキャン、最大4m
- ロボット: 半径0.5m、加速度制限付き
- 障害物: 線分（デフォルトマップ内蔵）
