# TAG polymorph animation

Interactive animation of triacylglycerol (TAG) polymorphic transitions **α → β′ → β**, showing how the subcell lattice parameters, chain tilt and long spacing change together with the simulated XRD (SAXS/WAXS) pattern.

トリアシルグリセロール（TAG）の多形転移 **α → β′ → β** を、サブセル格子定数・鎖の傾き・長周期の変化と、XRD（SAXS/WAXS）パターンを同期させて示すインタラクティブなアニメーションです。

## Features / 機能

- 2L (chair conformation) and 3L (SOS-type, saturated/unsaturated leaflet segregation with cis-bent oleoyl chains) lamellar models
- Subcell cross-section: hexagonal H → orthorhombic O⊥ → triclinic T∥
- Simulated SAXS (00l) and WAXS short-spacing peaks (Cu Kα, 1.5406 Å)
- Play/pause and slider control, Japanese / English switch, light / dark mode

## Usage / 使い方

Open `index.html` in any modern browser. No build step or external libraries.

`index.html` をブラウザで開くだけで動きます（外部ライブラリ不要）。

## Notes / 注意

This is a schematic. Lattice parameters are interpolated continuously using PPP-like values; real transitions proceed via nucleation/growth with two-phase coexistence. The 3L long spacing is taken as 1.5 × the 2L value.

模式図です。格子定数は PPP 相当値で連続補間しています（実際の転移は二相共存で進行）。3L の長周期は 2L 値の 1.5 倍としています。

## Author

Keisuke Watanabe, Department of Chemistry, Fukuoka University
