# Music — Classical WAV Library

楽譜由来のMIDIから生成した合成演奏WAVを作曲者別にまとめています。演奏家の録音ではありません。

**24作曲家・409曲／楽章 ＋ 連続再生版5本（全414ファイル）。44.1 kHz / 16 bit / stereo。**

2026-10-17：**[ヴィヴァルディ「四季」全12楽章・全曲連続版](Vivaldi/README.md)**を追加し、冬の速すぎたテンポを修正しました。ローカルの楽譜・MIDI・WAVも日付別を廃止し、1つのライブラリ内で作曲者別に統合しました。

2026-10-16：ベートーヴェン、ショパン、モーツァルト、シューベルト、サティなど20作曲家・200本を追加しました。

| 作曲者 | WAV数 | 一覧 |
|---|---:|---|
| ドビュッシー | 56 | [Debussy](Debussy/README.md) |
| ラヴェル | 9 | [Ravel](Ravel/README.md) |
| ヴィヴァルディ | 17 | [Vivaldi](Vivaldi/README.md) |
| バッハ | 132 | [Bach](Bach/README.md) |
| ベートーヴェン | 28 | [Beethoven](Beethoven/README.md) |
| ビゼー | 2 | [Bizet](Bizet/README.md) |
| ブラームス | 3 | [Brahms](Brahms/README.md) |
| ショパン | 46 | [Chopin](Chopin/README.md) |
| ドヴォルザーク | 8 | [Dvorak](Dvorak/README.md) |
| フォーレ | 2 | [Faure](Faure/README.md) |
| グリーグ | 7 | [Grieg](Grieg/README.md) |
| ヘンデル | 2 | [Handel](Handel/README.md) |
| ハイドン | 8 | [Haydn](Haydn/README.md) |
| ジョプリン | 5 | [Joplin](Joplin/README.md) |
| リスト | 4 | [Liszt](Liszt/README.md) |
| メンデルスゾーン | 7 | [Mendelssohn](Mendelssohn/README.md) |
| モーツァルト | 23 | [Mozart](Mozart/README.md) |
| パッヘルベル | 2 | [Pachelbel](Pachelbel/README.md) |
| ラフマニノフ | 10 | [Rachmaninoff](Rachmaninoff/README.md) |
| サティ | 6 | [Satie](Satie/README.md) |
| シューベルト | 13 | [Schubert](Schubert/README.md) |
| シューマン | 15 | [Schumann](Schumann/README.md) |
| ヨハン・シュトラウス2世 | 2 | [Strauss_Jr](Strauss_Jr/README.md) |
| チャイコフスキー | 7 | [Tchaikovsky](Tchaikovsky/README.md) |

## ダウンロード

各作曲者の一覧で曲名を探し、「ダウンロード」を押してください。WAV本体は[Releases](https://github.com/tamir-ichikawa/music/releases)に保存しています。通常の「Download ZIP」には目録・出典情報が入り、WAV本体は含まれません。

- [四季の現行全曲版（12楽章＋連続再生版5本）](https://github.com/tamir-ichikawa/music/releases/tag/four-seasons-complete)
- [第1弾：ドビュッシー、ラヴェル、ヴィヴァルディ、バッハ（200本）](https://github.com/tamir-ichikawa/music/releases/tag/wav-library-2026-10-15)
- [第2弾：クラシック20作曲家（200本）](https://github.com/tamir-ichikawa/music/releases/tag/wav-library-2026-10-16)

ソナタ・交響曲・組曲などは楽章・小曲を1本として数えています。各採用データの末尾まで収録した音声です。作品全体の抜粋や編曲版も含み、曲名に範囲を示しています。追加分の「美しく青きドナウ」は主題のピアノ編曲です。

第1弾にはドビュッシー《版画》全3曲、ヴィヴァルディ《冬》全3楽章を収録。ラヴェル《ソナチネ》《クープランの墓》《夜のガスパール》は、それぞれ全曲を1本に収録。平均律第1巻は30曲の抜粋、《鏡》は第1〜4曲です。

## 利用条件

曲ごとに利用条件が異なります。[catalog.csv](catalog.csv)に配布元、編集者、ライセンスURL、加工内容を記録しています。

- 第1弾のDCML版由来105本：**CC BY-NC-SA 4.0（非商用・出典表示・同一条件）**。
- Mutopia版由来：曲ごとのPublic Domain、CC BY、CC BY-SA。第2弾200本と現行の四季17本はすべてMutopia由来です。
- 第1弾PDMX / ScoreBase版由来4本：採用版の配布目録にCC0 1.0と表示。内部の権利表示に矛盾が見当たらない版を採用。

再利用時は曲別の条件を確認してください。配布元の注意点とクレジットは[credits](credits)に保存しています。

## 制作と検査

デジタル楽譜からMIDI化、または配布元の譜面由来MIDIを採用し、音源で合成しました。元データのテンポ・強弱・繰り返しを基本としています。四季「冬」の現行版は四分音符70 / 38 / 72に調整しました。追加分では「月光」ほか一部の曲のテンポ、欠落していた楽器指定、トライアングルの音色番号を調整しました。合唱の音声に歌詞はありません。人間の演奏のようなルバートを新たに作り込んだ版ではありません。

現行414本について音声の存在、長さ、クリッピングを検査。アップロード用コピーは元のWAVとSHA-256が一致しています。[SHA256SUMS.txt](SHA256SUMS.txt)で照合できます。元譜の全小節を人手で校訂したものではありません。

音源：MuseScore General (MIT)。Frank Wen / Michael Cowgill / S. Christian Collins / Ethan Winer / Michael Schorsch。[音源ライセンス全文](credits/MuseScore-General-license.txt)

主な出典：Mutopia Project、DCMLab (Hentschel et al., 2025, https://doi.org/10.1038/s41597-025-04976-z)、PDMX (Long et al., 2025, https://doi.org/10.1109/ICASSP49660.2025.10890217) / ScoreBase。曲別の目録から元の楽譜ページを開けます。
