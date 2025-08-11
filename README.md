# 🛠 The Sims 4 Translator 専用 JSON変換ツール

このツールは **The Sims 4 Translator** 用からエクスポートできるJSONファイルを、効率よく変換・編集しインポートしすぐ翻訳パッケージにできるツールです。  
**インストール不要・ブラウザだけで動作**し、翻訳作業がより簡単＆スムーズになります。

## 🌟<a href="https://nonamesims4.github.io/TheSims4Translator-JSON-/" target="_blank">ツールはこちら</a>  

---

## ✨ 主な機能

### 1. JSON ⇒ CSV変換
- TS4Tで出力したJSONファイルをCSV形式に変換  
- <a href="https://docs.google.com/spreadsheets/d/1kY-hnLaPf46MG7BWU3xcOKhk441BC0_LOjXHwEDn9cw/edit?gid=170644196#gid=170644196" target="_blank">Googleスプレッドシート</a>での一括翻訳に対応(使い方は下記)  

### 2. {M0.he}{F0.she}`のようなプレースホルダー修正→<a href="https://nonamesims4.github.io/The-Sims-4-MOD-JSON-/" target="_blank">Sims4専用JSONファイルタグ置き換えツール</a>

- `{M0.he}` や `{F0.she}` などの英語プレースホルダーを、日本語タグへ自動変換  

### 3. 翻訳済JSON ⇒ MOD用JSON変換
- Googleスプレッドシート等で翻訳した **小文字key/value形式** のJSONを  
  MODパッケージ製作用の **大文字キー形式（Locale / Entries）JSON** へ変換  
- そのままThe Sims 4 Translator にインポート可能(Sims4Studioにも対応しているかもしれません)  

---

## 📌 推奨ワークフロー

1. **JSON ⇒ CSV変換**
   - JSONファイルをアップロードし、CSVに変換
   - Googleスプレッドシートで開く

2. **Googleスプレッドシートで翻訳**
   - 下記の使い方を参照

3. **タグ正規化（必要に応じて）**
   - プレースホルダー変換をしたい場合は「タグ正規化」機能を使用

4. **翻訳済JSON ⇒ MOD用JSON変換**
   - 保存した翻訳済JSONをアップロード
   - MOD用大文字キーJSONに変換してダウンロード
   - Sims4Studio / The Sims 4 Translator にインポートしてMOD化

---

## 🌐<a href="https://docs.google.com/spreadsheets/d/1kY-hnLaPf46MG7BWU3xcOKhk441BC0_LOjXHwEDn9cw/edit?gid=170644196#gid=170644196" target="_blank">翻訳用Googleスプレッドシート</a>  

**使い方**
### Googleスプレッドシート翻訳ツールの使い方

1. Googleスプレッドシートを開き、**「ファイル」 → 「コピーを作成」** を選択します。  
   - 「Apps Script ファイルと機能もコピーしますか？」と表示されたら、そのまま **コピー** を選びます。  
2. メニューから **「ファイル」 → 「インポート」** を選択し、翻訳したいCSVファイルを読み込みます。  
3. インポート設定で **「現在のシートを置換する」** を選択します。  
4. スプレッドシート上部の **カスタムメニュー** から **「翻訳実行」** をクリックすると、翻訳が開始されます。  
5. 初めて使用する場合は **「権限の承認」** ダイアログが表示されるので、**許可** を選択してください。  
6. 翻訳が完了したら、同じカスタムメニューの **「jsonファイルをダウンロード」** をクリックして翻訳結果を保存します。  


---

## 💻 動作例・特徴
- ブラウザで動作（HTMLファイルを開くだけ）
- 「ファイル選択 → ボタンを押すだけ」のシンプル操作
- 生成されたJSONはそのままソフトにインポートするだけで簡単に翻訳パッケージに作成可能（別途Sims4StudioなどでGroupを変更してください）

---

## ❓ よくある質問（FAQ）

**Q. 翻訳したファイルをそのままMODに使っていいの？**  
A. TheSims4Translatorから出力されるJSONファイルに変換し即パッケージ化できるツールを使って翻訳パッケージとして使用できます🌐<a href="https://nonamesims4.github.io/TheSims4Translator-JSON-/" target="_blank">ツールはこちら</a> 


**Q. 大きなJSONファイルでも変換できる？**  
A. はい、UTF-8形式のJSONファイルやxmlファイルなら数千エントリでもOK！(自分が試したのは3000行)ただし、大きなファイルは処理に時間がかかる場合があります。









Special Thanks

このツールの開発にあたり、以下の皆さまに心より感謝いたします。

- 素敵なMODやCCを制作してくださっているクリエイターの皆様  
- 翻訳ソフトを開発してくださったエンジニアの皆様  
- The Sims 4 MODの日本語化方法を共有してくださった方々  
- STBL Studioという素晴らしいサイトを紹介してくださった方
- STBL Studioという素晴らしいサイトを作ってくれたFrankk様
- プレースホルダーの仕組みをわかりやすく解説してくださったブログの運営者様  
- 英語が苦手な私に丁寧に教えてくれた家族
- 技術的なヒントやコードのひな型を提案、提供してくれたAIツールたち

皆様のおかげで、このツールを完成させることができました。本当にありがとうございます！

