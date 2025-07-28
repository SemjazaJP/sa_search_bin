# 類音検索ツール（Sound-Alike Search）

**Author:** Semjaza D Rain (しぇみはざ)  
**GitHub:** https://github.com/SemjazaDRain/sa_search_bin

📥 [最新版をダウンロード（GitHub Releases）](https://github.com/SemjazaDRain/sa_search_bin/releases/tag/v2025.07.20.00.b-pre)

このリポジトリは、Sound-Alike Search の **実行バイナリ配布専用** です。  
ソースについては **実装があまりに汚いので別途調整中** です。

---

## 🔍 概要

日本語単語の母音系列に基づいた検索機能を提供するGUIアプリケーションです。
UniDic配布の辞書を活用し、音韻パターンによる検索が可能です。

韻を踏んで歌や文章を考えるとき、なかなか言葉が思いつかない、知らない。
なんでもいいから韻を踏んで遊びたい。
そんな状態を手助けをするツールがあったらな、という思いから作成されました。

---

## 🛠 主な機能

- UniDicのCSVからDBを自動生成
- 母音系列検索による単語探索
- GUIベースで直感的な操作
- 任意で瀬戸フォントに対応

---

## 🛠 次の予定

- [CMU Pronouncing Dictionary](http://www.speech.cs.cmu.edu/cgi-bin/cmudict)の英語-ARPABET辞書の類音検索搭載

---


## 📥 セットアップ方法

アーカイブ内に含まれる `README.md` をご覧ください。  
具体的な手順・必要なファイル・起動方法・注意事項を詳しく記載しています。

[HowTo.mdに導入手順を掲載しています](./HowTo.md)
---

## 🔗 関連リンク

- [UniDic公式サイト（辞書ダウンロード）](https://clrd.ninjal.ac.jp/unidic/)
- [瀬戸フォント配布ページ（v6.20）](https://forest.watch.impress.co.jp/library/software/setofont/download_11015.html)

---

## 🔨 ビルド方法

本ツールのWindowsバイナリは、以下の環境で PyInstaller によってビルドされています：

- Python 3.10.6
- PyInstaller 6.14.2
- DearPyGUI 2.1.0
- ビルドOS：Windows 11 Pro

> ※ PyInstaller は GPL v2 またはそれ以降のライセンスで提供されています。  
> 詳細については [PyInstaller GitHub](https://github.com/pyinstaller/pyinstaller) を参照してください。

---

## ⚖️ ライセンス情報

- 本体：MIT License（`license/sa_search/LICENSE.txt`）  
- 使用ライブラリ（DearPyGUI）：MIT License（`license/DearPyGui/LICENSE.txt`）  
- アイコン・画像素材：作者による独自ライセンス（`LICENSES.md` 参照）

> **注意**：本アプリケーションに含まれる実行バイナリは MIT ライセンス下で提供されますが、  
> アーカイブおよびモジュールに埋め込まれた独自アイコンや画像素材については単独での再配布・改変・商用利用・販売が禁止されています。

---

## 👤 作者情報

- 名前：Semjaza D Rain（しぇみはざ）  
- GitHub： https://github.com/SemjazaDRain  
- X（旧Twitter）： [@Shemi_haza](https://x.com/Shemi_haza)

---

