# vr-crafeat

A-Frameを使用して構築された、CRAFEATの3Dスキャン食品モデルを紹介するWebXR体験です。

## デモ

**[https://code4fukui.github.io/vr-crafeat/](https://code4fukui.github.io/vr-crafeat/)**

この体験では、カニバーガーとシシ肉（イノシシ肉）の2つの高精細な3Dモデルが目の前に浮かぶように配置されます。

## 特徴

- **WebXR対応:** A-Frameを使用して構築されており、VRヘッドセットやデスクトップブラウザでの没入型表示に対応しています。
- **高精細モデル:** 2つのリアルな食品3Dモデル（`kani-burger` と `shishiniku`）を搭載しています。
- **クロスプラットフォームアセット:** モデルは `.glb`（WebXR用）および `.usdz`（iOS AR用）の両方の形式で提供されます。
- **デバイスに応じたスケーリング:** デスクトップとMeta Questヘッドセットの両方で最適に表示されるよう、モデルのスケールと位置を自動的に調整します。
- **カラーマネジメント:** A-Frameのシーンは、より高い視覚品質を得るためにカラーマネジメントが設定されています。

## 使い方

1.  対応しているWebブラウザで[デモリンク](https://code4fukui.github.io/vr-crafeat/)にアクセスします。
2.  WebXR対応デバイス（例: Meta Quest）では、「Enter VR」ボタンをクリックして没入型シーンを表示します。
3.  ローカルで実行するには、ローカルWebサーバーから `index.html` ファイルを配信してください。

## 3Dモデル

このリポジトリには以下の3Dモデルアセットが含まれています:

- `kani-burger.glb` / `kani-burger.usdz`
- `shishiniku.glb` / `shishiniku.usdz`

シーンは、A-Frameの `<a-scene>` および `<a-entity gltf-model="...">` コンポーネントを使用してレンダリングされます。

## 帰属

- 3D食品モデルは [CRAFE
