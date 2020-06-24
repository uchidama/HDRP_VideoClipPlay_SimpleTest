# HDRP_VideoClipPlay_SimpleTest
Unity HDRP VideoClip Playing Simple Test

[![Image from Gyazo](https://i.gyazo.com/29e2516d5bc29a6b12a451d67ee95f66.gif)](https://gyazo.com/29e2516d5bc29a6b12a451d67ee95f66)

# 作り方
1. ムービーファイル(movファイル,mp4ファイル)をAssetに追加。VideoClipとして追加される。
2. Assets -> Create -> Render Texture を選択。Render TextureをAssetに追加。
3. GameObject -> 3D Object -> Plane を選択。平面を追加して良い位置、角度に合わせる
4. PlaneにRender Textureをドラッグ＆ドロップ。
5. VideoClipをシーンに置く。
6. VideoClipのインスペクタから Render ModeをRender Textureに。Target TextureをRender Textureに設定する。
[![Image from Gyazo](https://i.gyazo.com/541946970635355adde92050cd113ea0.png)](https://gyazo.com/541946970635355adde92050cd113ea0)
7. PlaneのShaderをUnit/Textureに設定する。  
[![Image from Gyazo](https://i.gyazo.com/119cf6936b07a3ace34192d7228a3425.png)](https://gyazo.com/119cf6936b07a3ace34192d7228a3425)

# 必要要件
- Unity 2019.4.0f1 or later

# 参考
[Unity video player not working HDRP (Fixed)](https://www.youtube.com/watch?v=TvkvI2S1mp0)   

# License
[Unlicense](https://unlicense.org/)
