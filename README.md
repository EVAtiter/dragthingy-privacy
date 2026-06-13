# QuickQuay — Support

**QuickQuay** ──お気に入りを集める、フローティング Dock。

macOS のドックは長く愛されている。ただ、もうひとつ別の Dock があったら、と思うことはないだろうか。このアプリだけ並べた小さな Dock。あのフォルダ群だけまとめた Dock。普段は畳んでおいて、必要なときだけ呼び出す Dock。

そして、複数のモニターを使う人にとっては──「メインだけでなく、サブの画面にも同じ Dock があってくれたら」。そんな思いも、長く溜まり続けてきたはず。

そんな「もうひとつ」を、ひとつずつ形にしていったら、QuickQuay になった。

このリポジトリは QuickQuay (Mac App Store 配布版) の **サポート / 質問 / 要望 / 不具合報告** の窓口です。ソースコードやバイナリの配布は行っていません。配布は Mac App Store 経由です。

---

## 入手

- **Mac App Store**: https://apps.apple.com/app/quickquay/id6769188046

## 質問・要望・不具合報告

- 雑談・要望・使い方の質問 → **[Discussions](https://github.com/EVAtiter/quickquay-support/discussions)**
- 明確な不具合 → **[Issues](https://github.com/EVAtiter/quickquay-support/issues)**

日本語・英語どちらでも歓迎です。

---

## QuickQuay でできること

macOS のドックに並ぶ、もうひとつの自前 Dock。お気に入りのアプリ・フォルダを並べて、いつでも 1 クリックで呼び出せる。

### 🧩 自分専用の Dock を、いくつでも

- Dock は**複数作成**可能。用途別に分けて配置を保存できる
- アイテムはアプリ・フォルダ・セパレーター・スペーサーが並べられる
- 縦／横／パレット (グリッド) から配置スタイルを選択
- 誤操作防止のため、ドラッグ＆ドロップでのアイテム追加・並び替え・削除は設定ダイアログで行う

### 👻 邪魔しないための 4 つの表示モード

- **通常**: 常時表示の素直な Dock
- **シャドウ**: 名前タイルに畳んでおき、必要なときにクリックで展開
- **ファントム**: 普段は背景レベル、マウス進入で前面に
- **ゴースト**: 常時非表示、マウスが Dock 領域に入ると現れる

### 🪟 フォルダーランチャー

- アプリやフォルダを設定したアイコンをクリックすると、中身を**吹き出しで一覧表示**
- アイコン名ラベル表示、書類 (PDF・画像・ZIP 等) も含めるオプション、パレット表示、スペーサーで間隔調整
- 吹き出しの背景色・透過率も Dock 単位で設定

### 🚀 Process Dock (App内課金)

- **起動中のアプリを自動で Dock に並べて**、クリックで素早く切り替え
- ピン留めと動的アプリ表示を 1 つの Dock 内で組み合わせ可能
- 「いま開いているもの」が常に手元に出ている状態を作れる

### 🖥 マルチディスプレイ対応

- 同じ Dock を**複数のモニターに同時表示** (ミラー機能)
- 各ミラーは表示先モニターと座標だけ独立、設定はすべて本体と共有
- 「表示ディスプレイ」を指定して、Dock の行き先を固定可能

### 🎨 細かくカスタマイズ自在

- Dock ごとに背景色・透過率・アイコンサイズ・拡大効果を設定
- macOS 標準 Dock 風の「ホバーで拡大」効果も任意で有効化
- アイコン名のラベル表示 ON/OFF、フォントサイズ調整
- 設定のインポート／エクスポートで構成を共有・引き継ぎ可能

### 🪶 邪魔しない設計

- **メニューバーに常駐**、Dock アイコンは表示しない
- フルスクリーン動画再生時は自動退避、終了で復帰
- 位置固定で誤操作による Dock 移動を防止
- 常時アイドルで動作が軽い

### ✅ 安心して使える配布形態

- **Mac App Store 配布** (App Sandbox + Hardened Runtime)
- **Apple 公証済み** (警告なしで起動可能)
- **Universal バイナリ** (Apple Silicon / Intel 両対応)

---

## プライバシー

QuickQuay は **データを一切収集しません**。App Sandbox 配下で動作し、外部サーバーへの通信も行いません。詳細は [PRIVACY.md](PRIVACY.md) を参照してください。

## 動作要件

- **macOS 14.0 Sonoma 以降**
- Apple Silicon / Intel Mac 両対応

---

# QuickQuay — Support (English)

**QuickQuay** ── a floating Dock that collects your favorites.

The macOS Dock has long been loved. But haven't you ever wished for *another* Dock alongside it? A small Dock with just this one app. A Dock that bundles only those folders. A Dock that stays tucked away and appears only when you need it.

And for those using multiple monitors — "Wouldn't it be great if the same Dock lived on the sub-screen, not just the main one?" That thought, too, has been quietly accumulating.

Putting those "one more" wishes into shape, one at a time, is how QuickQuay came to be.

This repository is the **support / questions / requests / bug reports** channel for QuickQuay. Source code and binaries are not distributed here; the app is available exclusively via the Mac App Store.

## Get the app

- **Mac App Store**: https://apps.apple.com/app/quickquay/id6769188046

## Ask questions / send feedback

- General discussion, feature requests, usage questions → **[Discussions](https://github.com/EVAtiter/quickquay-support/discussions)**
- Clear-cut bugs → **[Issues](https://github.com/EVAtiter/quickquay-support/issues)**

Posts in Japanese or English are both welcome.

## What QuickQuay does

A second Dock for macOS that lives alongside the system one. Line up your favorite apps and folders, and they're always one click away.

### 🧩 Your own Docks, as many as you want

- Create **multiple Docks**, each tailored to a different purpose
- Add apps, folders, separators, and spacers as items
- Choose vertical / horizontal / palette (grid) layouts
- Add, reorder, and remove items through the Preferences dialog (to prevent accidental drag-and-drop changes)

### 👻 Four display modes that stay out of the way

- **Normal**: always-visible plain Dock
- **Shadow**: collapses to a name tile, clicks expand it when needed
- **Phantom**: stays in the background until the mouse enters its area
- **Ghost**: hidden by default, appears when the mouse touches the Dock region

### 🪟 Folder Launcher

- Configure apps and folders so a click reveals their contents in a **bubble popup**
- Optional icon labels, ability to include documents (PDF / image / ZIP, etc.), palette layout, spacers for grouping
- Bubble background color and opacity are configurable per Dock

### 🚀 Process Dock (In-App Purchase)

- **Automatically shows running apps in the Dock** for instant switching
- Combine pinned items with live running-app display in a single Dock
- Keep "what's currently open" always within reach

### 🖥 Multi-display support

- Display the same Dock on **multiple monitors simultaneously** (Mirror feature)
- Each mirror has independent display target and position; all settings stay synced with the source
- Pin a Dock to a specific monitor via the "Display Target" setting

### 🎨 Fine-grained customization

- Per-Dock background color, opacity, icon size, magnification effect
- Optional macOS Dock-style "hover to enlarge" magnification
- Icon name labels (on/off, font size adjustable)
- Import/export settings to share or migrate your configuration

### 🪶 Designed to stay out of the way

- **Lives in the menu bar**, no Dock icon
- Auto-hides during full-screen video playback, returns when finished
- Position lock prevents accidental Dock movement
- Idle by default, lightweight

### ✅ Safe distribution

- **Distributed via Mac App Store** (App Sandbox + Hardened Runtime)
- **Notarized by Apple** (launches without warnings)
- **Universal binary** (Apple Silicon / Intel)

## Privacy

QuickQuay **collects no data**. It runs inside the App Sandbox and makes no network calls. See [PRIVACY.md](PRIVACY.md) for details.

## System requirements

- **macOS 14.0 Sonoma or later**
- Apple Silicon and Intel Mac supported

---

#Mac #MacOS #Dock #ランチャー #フリーソフト #ユーティリティ #個人開発 #QuickQuay #作業効率化 #生産性向上
