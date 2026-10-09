<img src="title.png" alt="Shadowgenic VST PianoRoll">

This is a VST3 MIDI sequencer/piano roll for Windows. You can edit MIDI notes and chords inside your DAW and send MIDI to another instrument. The plugin itself is not a sound generator.

## Installation
Launch the installer and select the language for both the installer and the manual.
Only the manual for the selected language will be installed, and a shortcut will be added to the Start Menu.

- VST3: `%ProgramFiles%\Common Files\VST3\ShdwgnicVSTPR.vst3`
- Manual: `%ProgramFiles%\Shadowgenic\Manual`

After installation, rescan your DAW’s plugin list.
If your DAW is running, please close it before installing.

## Using in a DAW
Load Shadowgenic VST PianoRoll into an instrument track in your DAW.

Load a VST instrument for sound output, and route MIDI from the PianoRoll to the instrument using your DAW’s MIDI routing.

One instance provides 16 tracks. To increase the number of tracks, add another instance with the same Group ID and assign outputs A–H. Up to 8 outputs and 128 tracks are available.

Playback and stop are controlled from the DAW’s transport.

MIDI routing procedures differ depending on the host.
Refer to the manual for details, including examples for Fender Studio Pro.

## Main Features
MIDI editing in Track View and Piano Roll

Smart Tool for entering and editing notes and MIDI components

Up to 128 tracks with per‑channel output settings

Chord events, chord follow, key/scale display

Editing of Velocity, CC, and Pitch Bend

Section saving, project saving, MIDI file import/export

## License Information
For libraries used and license details, see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) 

////////////////////////////////////////////////////////////////////////////

Windows 向けの VST3 MIDI シーケンサー／ピアノロールです。DAW の中で MIDI ノートやコードを編集し、別の音源へ MIDI を送ります。プラグイン自体は音源ではありません。

**VST3 名:** `Shadowgenic VST PianoRoll`  (`ShdwgnicVSTPR.vst3`)

## インストール

インストーラを起動し、インストーラとマニュアルの言語を選んでください。
選んだ言語のマニュアルだけがインストールされ、スタートメニューにショートカットが作成されます。

- VST3: `%ProgramFiles%\Common Files\VST3\ShdwgnicVSTPR.vst3`
- マニュアル: `%ProgramFiles%\Shadowgenic\Manual`

インストール後、DAW のプラグイン一覧を再スキャンしてください。
DAW が起動中なら、インストール前に終了してください。

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

- 

## ライセンス表示

使用ライブラリとライセンス情報は [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) を参照してください。
