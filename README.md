# 力学シミュレーション集

ブラウザで動作するインタラクティブな力学シミュレーションのコレクションです。各シミュレーションは単一のHTMLファイルで完結しており、外部依存なしで動作します。

## 使い方

任意のHTMLファイルをダウンロードしてブラウザで開くか、GitHub Pagesで直接実行できます。

## シミュレーション一覧

### 基本振動系
- [バネ・マス・ダンパ系](spring_mass_damper.html)
- [強制振動バネ・マス・ダンパ系](forced_spring_mass_damper.html)
- [基礎加振と振動絶縁](base_excitation_isolation.html)
- [動吸振器](dynamic_vibration_absorber.html)

### 振り子系
- [回転円盤振り子](rotating_disk_pendulum.html)
- [弾性振り子](elastic_pendulum.html)
- [二重振り子（質量比）](double_pendulum_mass_ratio.html)
- [三重振り子](triple_pendulum.html)
- [サイクロイド振り子](cycloid_pendulum.html)
- [回転ばね付き振り子](pendulum_rotational_spring.html)
- [ねじりばね付き倒立振り子](inverted_pendulum_torsion_spring.html)
- [T字型複合振り子](t_shaped_compound_pendulum.html)
- [遠心調速機](centrifugal_governor.html)

### 連成振動系
- [多自由度バネ・マス系](multi_dof_spring_mass.html)
- [2質点連成振動](two_mass_coupled_oscillator.html)
- [ばね連結2質点系](two_mass_spring_coupled.html)
- [2質点ばね系（初期値問題）](two_mass_spring_initial_value.html)
- [3質点連成振動A](three_mass_coupled_oscillator_a.html)
- [3質点連成振動B](three_mass_coupled_oscillator_b.html)
- [4質点連成振動](four_mass_coupled_oscillator.html)
- [2自由度鉛直ばね・マス系](two_dof_spring_mass_vertical.html)
- [2自由度強制振動](two_dof_forced_vibration.html)
- [2自由度強制振動（減衰付き）](two_dof_forced_vibration_damped.html)
- [多要素振動系](multi_element_vibration.html)

### 梁・片持ち梁系
- [片持ち梁の曲げ振動](cantilever_bending_vibration.html)
- [ばね支持片持ち梁](spring_supported_cantilever.html)
- [2点ばねダンパ支持梁](two_point_spring_damper_beam.html)

### 衝突・接触系
- [跳ねるボール](bouncing_ball.html)
- [箱内弾性衝突](elastic_collision_in_box.html)
- [振り子衝突](pendulum_collision.html)
- [ばね・マス壁衝突](spring_mass_wall_collision.html)
- [斜面衝突と摩擦](inclined_plane_collision_friction.html)
- [接触ばね振動](contact_spring_vibration.html)

### ばね支持・複合系
- [4ばね支持質点](four_spring_supported_mass.html)
- [両側ばねダンパ](double_sided_spring_damper.html)
- [弾性ばね振り子](spring_pendulum_elastic.html)
- [ばね支持二重リンク](spring_supported_double_link.html)
- [鉛直ばねダンパ](vertical_spring_damper.html)

### 回転・転がり系
- [回転円盤クランク](rotating_disk_crank.html)
- [変速回転円盤](variable_speed_rotating_disk.html)
- [多ばね回転円盤](multi_spring_rotating_disk.html)
- [転がり円筒振動](rolling_cylinder_vibration.html)
- [円内転がり](rolling_inside_circle.html)
- [スライダ転がり円盤ばね](slider_rolling_disk_spring.html)

### 機構・リンク系
- [スライダ・クランク機構](slider_crank_mechanism.html)
- [スライダ・クランク瞬間中心軌跡](slider_crank_centrode.html)
- [2リンク機構](two_link_mechanism.html)
- [4節リンク機構](four_bar_linkage.html)
- [クランク揺動スライダ](crank_oscillating_slider.html)
- [車輪リンク連成](wheel_linkage_coupled.html)

### 滑車・ロープ系
- [滑車連結振り子](pulley_coupled_pendulum.html)
- [ばね支持滑車](pulley_spring_supported.html)
- [ロープ連結円筒・質点](rope_coupled_cylinder_mass.html)
- [ヨーヨー下降滑車](yoyo_descending_pulley.html)

### 車両・サスペンション系
- [車両サスペンション（段差）](vehicle_suspension_bump.html)
- [車両サスペンション図解](vehicle_suspension_diagram.html)
- [車両サスペンション（傾斜路）](vehicle_suspension_ramp.html)

### その他
- [放物線軌道上の質点](mass_on_parabolic_track.html)
- [半円ガイドスライダ](semicircle_guide_slider.html)
- [直方体ロッキング](rectangular_block_rocking.html)

## 特徴

- 単一HTMLファイルで完結（外部ライブラリ不要）
- インタラクティブなパラメータ調整
- リアルタイムアニメーション表示
- グラフによる時系列データ可視化
- 運動方程式の表示

## 動作環境

モダンなWebブラウザ（Chrome、Firefox、Safari、Edge等）

## ライセンス

MIT License
