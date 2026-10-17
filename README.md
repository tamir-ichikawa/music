# Music — Classical MIDI & WAV Library

楽譜由来のMIDIと、そのMIDIを音源で鳴らしたWAVです。演奏家の録音ではありません。

**24作曲家・409曲／楽章＋連続再生版5本、全414組。**

- **[MIDIフォルダ](MIDI/README.md)**：作曲者別に実ファイルを保存。
- **[WAVフォルダ](WAV/README.md)**：作曲者別の曲別リンクと一括ZIP。WAV本体はReleasesに保存。
- テンポを全件点検し、32ファイルを更新。[変更記録](credits/tempo-audit.csv)。数値未指定のBPMは制作設定です。

| 作曲者 | ファイル数 | MIDI | WAV |
|---|---:|---|---|
| バッハ | 132 | [Bach](MIDI/Bach/README.md) | [Bach](WAV/Bach/README.md) |
| ベートーヴェン | 28 | [Beethoven](MIDI/Beethoven/README.md) | [Beethoven](WAV/Beethoven/README.md) |
| ビゼー | 2 | [Bizet](MIDI/Bizet/README.md) | [Bizet](WAV/Bizet/README.md) |
| ブラームス | 3 | [Brahms](MIDI/Brahms/README.md) | [Brahms](WAV/Brahms/README.md) |
| ショパン | 46 | [Chopin](MIDI/Chopin/README.md) | [Chopin](WAV/Chopin/README.md) |
| ドビュッシー | 56 | [Debussy](MIDI/Debussy/README.md) | [Debussy](WAV/Debussy/README.md) |
| ドヴォルザーク | 8 | [Dvorak](MIDI/Dvorak/README.md) | [Dvorak](WAV/Dvorak/README.md) |
| フォーレ | 2 | [Faure](MIDI/Faure/README.md) | [Faure](WAV/Faure/README.md) |
| グリーグ | 7 | [Grieg](MIDI/Grieg/README.md) | [Grieg](WAV/Grieg/README.md) |
| ヘンデル | 2 | [Handel](MIDI/Handel/README.md) | [Handel](WAV/Handel/README.md) |
| ハイドン | 8 | [Haydn](MIDI/Haydn/README.md) | [Haydn](WAV/Haydn/README.md) |
| ジョプリン | 5 | [Joplin](MIDI/Joplin/README.md) | [Joplin](WAV/Joplin/README.md) |
| リスト | 4 | [Liszt](MIDI/Liszt/README.md) | [Liszt](WAV/Liszt/README.md) |
| メンデルスゾーン | 7 | [Mendelssohn](MIDI/Mendelssohn/README.md) | [Mendelssohn](WAV/Mendelssohn/README.md) |
| モーツァルト | 23 | [Mozart](MIDI/Mozart/README.md) | [Mozart](WAV/Mozart/README.md) |
| パッヘルベル | 2 | [Pachelbel](MIDI/Pachelbel/README.md) | [Pachelbel](WAV/Pachelbel/README.md) |
| ラフマニノフ | 10 | [Rachmaninoff](MIDI/Rachmaninoff/README.md) | [Rachmaninoff](WAV/Rachmaninoff/README.md) |
| ラヴェル | 9 | [Ravel](MIDI/Ravel/README.md) | [Ravel](WAV/Ravel/README.md) |
| サティ | 6 | [Satie](MIDI/Satie/README.md) | [Satie](WAV/Satie/README.md) |
| シューベルト | 13 | [Schubert](MIDI/Schubert/README.md) | [Schubert](WAV/Schubert/README.md) |
| シューマン | 15 | [Schumann](MIDI/Schumann/README.md) | [Schumann](WAV/Schumann/README.md) |
| ヨハン・シュトラウス2世 | 2 | [Strauss_Jr](MIDI/Strauss_Jr/README.md) | [Strauss_Jr](WAV/Strauss_Jr/README.md) |
| チャイコフスキー | 7 | [Tchaikovsky](MIDI/Tchaikovsky/README.md) | [Tchaikovsky](WAV/Tchaikovsky/README.md) |
| ヴィヴァルディ | 17 | [Vivaldi](MIDI/Vivaldi/README.md) | [Vivaldi](WAV/Vivaldi/README.md) |

## ダウンロードと収録範囲

MIDIは通常のGitファイルです。WAVは合計約14GBで100MBを超える曲もあるため、無料のReleasesから配布しています。Code → Download ZIP にはMIDIと目録が入り、WAV本体は含まれません。WAVの一括ZIPは上の作曲家一覧から取得してください。

ソナタ・組曲・交響曲などは楽章や小曲単位で数えています。採用データの末尾までを収録していますが、抜粋や編曲版も含み、曲名に範囲を示しています。四季は全12楽章と連続版5本。平均律第1巻は30曲の抜粋、ラヴェル《鏡》は第1〜4曲です。

## テンポと制作

テンポの数値と音符単位、設定漏れ、主要な速度区間を点検しました。印刷譜の数値と再生値が違う場合を修正し、数値のない曲では制作上の速度を設定しました。BPMに唯一の正解がない曲もあります。[全414件の点検記録](credits/tempo-audit.csv)をご覧ください。

変更した単独曲は音符・音高・音価・強弱と楽器構成を保持し、WAVを再生成しました。連続版は修正済み楽章を再結合。細かなルバート等を新たにすべて演奏付けした版ではありません。旧リリースは履歴として残しているため、この目録のリンクを利用してください。

WAVは44.1kHz / 16bit / stereo、FluidSynthとMuseScore Generalによる合成演奏です。合唱に歌詞の発音はありません。[SHA256SUMS.txt](SHA256SUMS.txt)で照合できます。

## 利用条件

楽譜が古典でもデジタル版ごとの条件があります。MIDIとWAVのどちらも[catalog.csv](catalog.csv)の条件・出典表示を引き継いでください。

- DCML由来105本：CC BY-NC-SA 4.0（非商用・出典表示・同一条件）。
- Mutopia由来：各曲のPublic Domain、CC BY、CC BY-SA。
- PDMX / ScoreBase由来4本：採用目録のCC0 1.0。

詳細な出典、編集者、加工内容、ライセンスURLは[catalog.json](catalog.json)と[credits](credits)に記載しています。
