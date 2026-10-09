<img src="title.png" alt="Shadowgenic VST PianoRoll">

Windows 向けの VST3 MIDI シーケンサー／ピアノロールです。DAW の中で MIDI ノートやコードを編集し、別の音源へ MIDI を送ります。プラグイン自体は音源ではありません。

**VST3 名:** `Shadowgenic VST PianoRoll`  (`ShdwgnicVSTPR.vst3`)

## インストール

インストーラを起動し、インストーラとマニュアルの言語を選んでください。
選んだ言語のマニュアルだけがインストールされ、スタートメニューにショートカットが作成されます。

- VST3: `%ProgramFiles%\Common Files\VST3\ShdwgnicVSTPR.vst3`
- マニュアル: `%ProgramFiles%\Shadowgenic\Manual`

インストール後、DAW のプラグイン一覧を再スキャンしてください。
DAW が起動中なら、インストール前に終了してください。

## マニュアル

画像を含む各言語の HTML マニュアルです。

- [日本語](Manual_JA.html)
- [English](Manual_EN.html)
- [Français](Manual_FR.html)
- [Deutsch](Manual_DE.html)
- [Italiano](Manual_IT.html)
- [Русский](Manual_RU.html)
- [Español](Manual_ES.html)
- [Català](Manual_CA.html)
- [Português](Manual_PT.html)
- [Suomi](Manual_FI.html)

## DAW で使う

1. DAW のインストゥルメントトラックに Shadowgenic VST PianoRoll を読み込みます。
2. 発音用の VST 音源を読み込み、DAW の MIDI ルーティングで PianoRoll から音源へ接続します。
3. 1 インスタンスで 16 トラックを使用できます。トラック数を増やす場合は同じ Group ID のインスタンスを追加し、出力 A〜H を割り当てます。最大 8 出力、128 トラックまで使用できます。
4. 再生と停止は DAW のトランスポートで操作します。

ホストごとに MIDI ルーティングの手順は異なります。Fender Studio Pro の設定例など、詳細はマニュアルを参照してください。

## 主な機能

- トラックビューとピアノロールでの MIDI 編集
- Smart ツールによるノートや MIDI 部品の入力・編集
- 最大 128 トラック、MIDI チャンネルごとの出力設定
- コードイベント、コード追従、キー／スケール表示
- Velocity、CC、Pitch Bend の編集
- セクション保存、プロジェクト保存、MIDI ファイル入出力

## ライセンス表示

使用ライブラリとライセンス情報は [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) を参照してください。
