# Music — Classical WAV Library

楽譜由来のMIDIから生成した、全尺の合成演奏WAVを作曲者別にまとめています。演奏家の録音ではありません。

**200本・約9時間41分・合計約5.7 GiB。44.1 kHz / 16 bit / stereo。**

| 作曲者 | WAV数 | 一覧 |
|---|---:|---|
| ドビュッシー | 56 | [Debussy](Debussy/README.md) |
| ラヴェル | 9 | [Ravel](Ravel/README.md) |
| ヴィヴァルディ | 3 | [Vivaldi](Vivaldi/README.md) |
| バッハ | 132 | [Bach](Bach/README.md) |

WAV本体は[Releases](https://github.com/tamir-ichikawa/music/releases/tag/wav-library-2026-10-15)に保存しています。各作曲者の一覧から1曲ずつダウンロードできます。通常の「Download ZIP」には目録と出典情報が入り、WAV本体は含まれません。

ドビュッシー《版画》全3曲、ヴィヴァルディ《冬》全3楽章を収録。ラヴェルの《ソナチネ》《クープランの墓》《夜のガスパール》は、それぞれ全曲を1つのWAVに収録しています。平均律第1巻は30曲の抜粋、《鏡》は第1〜4曲です。

## 利用条件

**一括で同じライセンスを付けた素材集ではありません。** 曲ごとの条件は[catalog.csv](catalog.csv)と各作曲者の一覧に記載しています。

- DCML版由来の105本：**CC BY-NC-SA 4.0（非商用・出典表示・同一条件）**。
- Mutopia版由来の91本：曲ごとにPublic Domain、CC BY-SA 3.0、CC BY-SA 4.0。
- PDMX / ScoreBase版由来の4本：採用版の配布目録にCC0 1.0と表示。内部の権利表示に矛盾が見当たらない版を採用。

元データの編集者・配布元・ライセンスURL・加工内容を[catalog.csv](catalog.csv)に記録しています。配布元の注意点とクレジットは[credits](credits)を参照してください。一般公開されている曲でも、商用利用が許可されているとは限りません。

## 制作と検査

元のデジタル譜からMuseScoreでMIDI化、または配布元の譜面由来MIDIを採用し、音源で合成しました。元データのテンポ・強弱・繰り返しを基本とした確認用演奏です。人間の演奏のようなルバート等を新たに作り込んだ版ではありません。

全200本について音声の存在・長さ・クリッピングを検査。アップロード用コピーは元のWAVとSHA-256が一致しています。[SHA256SUMS.txt](SHA256SUMS.txt)で照合できます。元譜の全小節を人手で校訂したものではありません。

音源：MuseScore General (MIT)。Frank Wen / Michael Cowgill / S. Christian Collins / Ethan Winer / Michael Schorsch。[音源ライセンス全文](credits/MuseScore-General-license.txt)

主な出典：DCMLab (Hentschel et al., 2025, https://doi.org/10.1038/s41597-025-04976-z)、Mutopia Project、PDMX (Long et al., 2025, https://doi.org/10.1109/ICASSP49660.2025.10890217) / ScoreBase。詳細は曲別の目録を参照。
