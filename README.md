# 積み木遊び / Tsumiki Play / 积木游玩

index.html 1ファイルだけで動作する、Three.js製の3D積み木遊びアプリです。
スマートフォンでも操作しやすい横長画面、サウンドOn/Off、多言語対応、ブラウザローカルへの複数セーブデータ保存に対応しています。

---

## English

A 3D building block app made with Three.js.  
Runs from a single index.html file, with landscape-oriented layout, sound On/Off, multilingual UI, and multiple local save slots.

---

## 中文

使用 Three.js 制作的 3D 积木应用。  
只需一个 index.html 文件即可运行，支持横屏画面、声音开关、多语言界面，以及浏览器本地多存档保存。

---

## 主な特徴 / Main Features / 主要功能

### 日本語

- Three.js を使用した 3D 積み木遊び
- PCとスマホで操作できる横長画面レイアウト
- サウンドのOn/Off切替
- 日本語 / English / 中文 の多言語UI
- ブラウザローカルストレージへ最大10件までの複数セーブデータ保存
- 色付きブロックの配置、削除、再配色
- プレースホルダー用のサンプル構造を初期表示

### English

- 3D building blocks using Three.js
- Landscape-oriented layout for PC and mobile
- Sound On/Off toggle
- Multilingual UI: Japanese / English / Chinese
- Up to 10 local save slots in browser storage
- Place, delete, and repaint colored blocks
- Shows a sample structure on first launch

### 中文

- 使用 Three.js 的 3D 积木
- 适合 PC 与手机的横屏界面
- 声音开启 / 关闭
- 多语言界面：日语 / 英语 / 中文
- 可在浏览器本地存储中保存最多 10 个存档
- 可放置、删除、重新上色积木
- 首次启动时显示示例结构

---

## 動作環境 / Requirements / 运行环境

### 日本語

- 最近のブラウザ:
  - Google Chrome
  - Microsoft Edge
  - Firefox
  - Safari
- インターネット接続:
  - Three.jsをCDNから読み込むため、初回表示にはネット接続が必要です。
- ローカルストレージ:
  - 設定とセーブデータはブラウザのローカルストレージに保存されます。
  - ブラウザのシークレットモード、ストレージ制限、キャッシュ削除によって保存が消えることがあります。

### English

- Modern browsers:
  - Google Chrome
  - Microsoft Edge
  - Firefox
  - Safari
- Internet connection:
  - Required to load Three.js from a CDN.
- Local storage:
  - Settings and save data are stored in browser local storage.
  - Private browsing, storage restrictions, or clearing browser data may remove saved data.

### 中文

- 现代浏览器：
  - Google Chrome
  - Microsoft Edge
  - Firefox
  - Safari
- 需要网络连接：
  - 应用会从 CDN 加载 Three.js。
- 本地存储：
  - 设置和存档保存在浏览器本地存储中。
  - 无痕模式、存储限制或清除浏览器数据可能导致存档消失。

---

## 使い方 / How to Use / 使用方法

### 日本語

1. このファイルを index.html という名前で保存します。
2. index.html をブラウザで開きます。
3. 横長画面が表示されます。
   - スマホでは横向きでの使用を推奨します。
4. 左側のカラーボタンで色を選択します。
5. 画面上部のボタンで言語とサウンドを設定します。
6. 右上のモードボタンで操作モードを選択します。
   - 置く
   - 消す
   - 色変更
7. 画面をタップまたはクリックしてブロックを操作します。
8. 「保存 / 読込」からセーブデータを保存・読込・削除できます。

### English

1. Save this project as index.html.
2. Open index.html in a browser.
3. The app opens in a landscape-oriented view.
   - On smartphones, landscape orientation is recommended.
4. Select a color from the palette on the left.
5. Change language and sound settings from the top bar.
6. Select a mode from the top-right buttons.
   - Place
   - Delete
   - Paint
7. Tap or click the scene to manipulate blocks.
8. Use Save / Load to save, load, or delete local save slots.

### 中文

1. 将本文件保存为 index.html。
2. 在浏览器中打开 index.html。
3. 应用会显示为横屏界面。
   - 手机建议横屏使用。
4. 在左侧颜色面板中选择颜色。
5. 在顶部栏中切换语言和声音。
6. 在右上角模式按钮中选择操作模式：
   - 放置
   - 删除
   - 上色
7. 点击画面来操作积木。
8. 通过“保存 / 读取”进行存档保存、读取或删除。

---

## 操作方法 / Controls / 操作方式

### PC

### 日本語

- ドラッグ: カメラ回転
- ホイール: ズーム
- 左クリック / タップ: 現在のモードを実行
- 右クリック: ブロックを消す

### English

- Drag: rotate camera
- Mouse wheel: zoom
- Left click / tap: execute current mode
- Right click: delete a block

### 中文

- 拖动：旋转视角
- 鼠标滚轮：缩放
- 左键点击 / 触摸：执行当前模式
- 右键点击：删除积木

### Smartphone / Tablet

### 日本語

- 1本指ドラッグ: カメラ回転
- 2本指: ズーム、画面回転
- タップ: 現在のモードを実行

### English

- One finger drag: rotate camera
- Two fingers: zoom and screen rotate
- Tap: execute current mode

### 中文

- 单指拖动：旋转视角
- 双指操作：缩放和画面旋转
- 点击：执行当前模式

---

## 操作モード / Modes / 模式

### 日本語

### 置く / Place / 放置

- 床面または既存ブロックの側面にブロックを追加します。
- 選択中の色が使われます。

### 消す / Delete / 删除

- 画面内のブロックをタップして削除します。
- PCでは右クリックでも削除できます。

### 色変更 / Paint / 上色

- 既存ブロックをタップして、選択中の色に変更します。
- 選択中の色は左側のカラーパレットから選べます。

### English

### Place

- Adds a block on the floor or adjacent to an existing block.
- Uses the currently selected color.

### Delete

- Removes a block by tapping it.
- On PC, right-click can also delete a block.

### Paint

- Changes an existing block to the currently selected color.
- Colors are selected from the palette.

### 中文

### 放置

- 在地面或已有积木相邻位置添加积木。
- 使用当前选中的颜色。

### 删除

- 点击积木进行删除。
- PC端也可以用右键删除。

### 上色

- 点击已有积木，将其改为当前选中的颜色。
- 颜色从左侧调色板中选择。

---

## セーブデータ / Save Data / 存档

### 日本語

- セーブデータはブラウザのローカルストレージに保存されます。
- 最大10件まで保存できます。
- 保存名、作成日時、更新日時、ブロック数が表示されます。
- 読み込み時、その存档に保存されていた言語設定も反映されます。

保存に使われているキー:

- 設定: tsumiki_settings_v1
- 保存スロット: tsumiki_save_slots_v1

### English

- Save data is stored in browser local storage.
- Up to 10 save slots are supported.
- Each slot shows name, creation time, update time, and block count.
- When loading a save, language settings stored with it are also applied.

Local storage keys used:

- Settings: tsumiki_settings_v1
- Save slots: tsumiki_save_slots_v1

### 中文

- 存档保存在浏览器本地存储中。
- 最多支持保存 10 个存档。
- 每个存档会显示名称、创建时间、更新时间和积木数量。
- 读取存档时，也会应用该存档中保存的语言设置。

使用的本地存储键：

- 设置：tsumiki_settings_v1
- 存档列表：tsumiki_save_slots_v1

---

## 言語対応 / Languages / 多语言

### 日本語

このアプリは以下の言語に対応しています。

- 日本語
- English
- 中文

画面右上の言語選択メニューから変更できます。  
設定言語とサウンド設定はブラウザに保存されます。

### English

This app supports the following languages:

- Japanese
- English
- Chinese

You can change the language from the language selector in the top-right area.  
Language and sound settings are saved in the browser.

### 中文

应用支持以下语言：

- 日语
- 英语
- 中文

可以通过右上角的语言选择菜单切换语言。  
语言和声音设置会保存在浏览器中。

---

## サウンド / Sound / 声音

### 日本語

- 上部の「🔊 On / 🔇 Off」でサウンドを切り替えます。
- ブロックを置く、消す、色を変える、ボタン操作などで効果音が鳴ります。
- 一部のブラウザでは、初回タップまたはクリック後に音が有効になることがあります。

### English

- Toggle sound with the top bar button.
- Sound effects play for placing, deleting, repainting, and UI actions.
- Some browsers require a first tap or click before audio starts.

### 中文

- 通过顶部栏按钮切换声音开关。
- 放置、删除、上色和按钮操作时会播放音效。
- 某些浏览器需要在首次点击后才启用声音。

---

## 画面について / About the Display / 画面说明

### 日本語

- 画面は横長16:9相当で表示されるように調整されています。
- 縦長の端末では、横画面にする案内が表示されます。
- 案内はタップで閉じることができますが、横長画面での使用を強く推奨します。

### English

- The app is designed for a landscape-oriented 16:9-style display.
- If the device is in portrait mode, a rotate-to-landscape notice may appear.
- The notice can be dismissed by tapping it, but landscape use is strongly recommended.

### 中文

- 应用按横屏16:9比例显示。
- 竖屏设备上会显示横屏提示。
- 可以点击提示关闭，但强烈建议横屏使用。

---

## ファイル構成 / File Structure / 文件结构

### 日本語

- index.html
  - アプリ本体
  - Three.jsをCDNから読み込みます。
  - 追加のnpm installやビルドは不要です。

### English

- index.html
  - The whole app.
  - Loads Three.js from a CDN.
  - No npm install or build step is required.

### 中文

- index.html
  - 应用本体。
  - 从 CDN 加载 Three.js。
  - 不需要 npm install 或构建步骤。

---

## トラブルシューティング / Troubleshooting / 故障排除

### 日本語

- 画面が真っ暗な場合:
  - ブラウザのJavaScript設定を有効にしてください。
  - インターネット接続を確認してください。
- 音が鳴らない場合:
  - 一度画面をタップしてください。
  - 上部のサウンドボタンが「On」になっているか確認してください。
  - 端末側の音量やマナーモードを確認してください。
- 保存できない場合:
  - ブラウザのストレージ設定を確認してください。
  - シークレットモードを使っている場合、保存が制限されることがあります。
- 多言語表示が切り替わらない場合:
  - ページを再読み込みしてください。
  - 画面右上の言語選択が反映されているか確認してください。

### English

- If the screen is blank:
  - Enable JavaScript in your browser.
  - Check your internet connection.
- If there is no sound:
  - Tap the screen once.
  - Confirm the sound toggle is set to On.
  - Check device volume and mute mode.
- If saving fails:
  - Check browser storage settings.
  - Some private browsing modes may block storage.
- If language does not change:
  - Reload the page.
  - Confirm the language selector in the top-right menu.

### 中文

- 如果画面全黑：
  - 启用浏览器 JavaScript。
  - 检查网络连接。
- 如果没有声音：
  - 先点击一次画面。
  - 确认顶部声音按钮处于“On”。
  - 检查设备音量和静音模式。
- 如果无法保存：
  - 检查浏览器存储设置。
  - 某些无痕模式可能限制保存。
- 如果语言没有切换：
  - 刷新页面。
  - 确认右上角语言选择菜单已更改。

---

## 保存データの削除方法 / How to Delete Save Data / 删除存档方法

### 日本語

- アプリ内の「保存 / 読込」から特定セーブデータを削除できます。
- すべて削除したい場合は、ブラウザのサイトデータやローカルストレージを削除してください。

### English

- You can delete specific save slots from the Save / Load menu.
- To delete everything, clear the browser storage for the site.

### 中文

- 可以通过“保存 / 读取”菜单删除指定存档。
- 如果要删除全部数据，请清除该网站的浏览器存储。

---

## 使用している主な技術 / Main Technologies / 主要技术

### 日本語

- Three.js
- JavaScript ES Modules
- OrbitControls
- Web Audio API
- Browser Local Storage

### English

- Three.js
- JavaScript ES Modules
- OrbitControls
- Web Audio API
- Browser Local Storage

### 中文

- Three.js
- JavaScript ES Modules
- OrbitControls
- Web Audio API
- Browser Local Storage

---

## カスタマイズのヒント / Customization Hints / 自定义建议

### 日本語

index.html 内の定数を変更すると、アプリの挙動を調整できます。

- MAX_BLOCKS: 一度に置ける最大ブロック数
- GRID_HALF: 床の半径
- MAX_HEIGHT: 積める最大高さ
- colorList: 使用できる色
- I18N: 言語メッセージ

### English

You can adjust app behavior by editing constants inside index.html.

- MAX_BLOCKS: maximum block count
- GRID_HALF: floor radius
- MAX_HEIGHT: maximum build height
- colorList: available colors
- I18N: language messages

### 中文

可以修改 index.html 中的常量来调整应用行为：

- MAX_BLOCKS：最大积木数量
- GRID_HALF：地面半径
- MAX_HEIGHT：最大堆叠高度
- colorList：可用颜色
- I18N：多语言文案

---

## 注意 / Notes / 注意事项

### 日本語

- このアプリは外部CDNからThree.jsを読み込みます。
- オフラインで使う場合は、Three.jsをローカルファイルとして読み込むように変更してください。
- 保存データはブラウザごとに分離されます。
- 端末を替えると、自動的にセーブデータは引き継がれません。

### English

- This app loads Three.js from an external CDN.
- For offline use, change it to load a local Three.js build.
- Save data is separated per browser.
- Save data is not automatically transferred to another device.

### 中文

- 应用会从外部 CDN 加载 Three.js。
- 如需离线使用，请改为加载本地 Three.js 文件。
- 存档数据按浏览器隔离。
- 更换设备后不会自动同步存档。

---

## ライセンス / License / 许可

### 日本語

- 本文書とアプリは、個人利用・学習用・改造利用を前提に提供されています。
- Three.jsのライセンス条件を尊重してください。

### English

- This document and app are provided for personal use, learning, and modification.
- Respect the license terms of Three.js.

### 中文

- 本文和应用适用于个人使用、学习和修改。
- 请遵守 Three.js 的许可证条款。