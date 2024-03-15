## 1.13

> \*\*このアップデートは、Codeforces Better v1.68 - 1.74からの変更をAtCoder Betterに同期します。

- VJudgeへジャンプするボタンを追加

- コードブロックを美化する」機能を追加し、モナコエディタを使ってページ上のコードブロックを置換できるようにしました。

- Clist Ratingの様々なリクエストメソッドを改善し、データが正しく取得されない問題に対処。

- ChatGPT翻訳のプロンプトを改善し、不完全な翻訳につながる可能性のあるインジェクションエラーを修正しました。

- LaTeX Replace/Restore関連コードの改良。

- ウェブサイトのローカリゼーション手法の堅牢性を高める

- ダークモードに関連するコードを調整し、スタイルと管理の統一を容易にするために変数を使用する。

- CDNのstaticfile.orgをstaticfile.netに置き換える

- 質問一覧ページで、一部のトピックのclist評価がnot foundと表示されることがある問題を修正しました。

- 問題セットのページで、クライストスコアが異常に表示される問題を修正しました。

- コード・オンライン・テストにおける整列されていない差分比較スタイルの問題を修正。

- エラー報告後にdeepl 429が警告メッセージを正しく表示しない問題を修正。

- タイトルページのCrist RatingがNot Foundと表示されることがある問題を修正しました。

- 旧バージョンのTampermonkeyで、ロックバレー・ジャンプのメソッドがエラーを報告する問題を修正しました。

- MathJaxライブラリファイルが正しくロードされない場合に、ページがスタックしてしまう予期せぬデッドループを修正した。

- フリー・モードで翻訳すると、DeepL で翻訳中の警告メッセージが正しく表示されない問題が修正されました。

- スクリプトが正しくロードされないことがあった問題を修正

- 隣り合うLaTeX数式間の組版が崩れることがあった問題を修正

- その他の調整と改善

***

- ウェブサイトのローカライズされたデータを外部JSONとして独立させ、メンテナンスを容易にする。
- スクリプトは国際化をサポートし、crowdinプラットフォームを使用してローカリゼーションを自動化します。
- いくつかのボタンをアイコンボタンに置き換える
- 公式のapi-free、api-pro、deeplxを含むDeepL APIのサポートを追加しました。
- 残高検索を設定するためにdeeplとchatgptのサポートを追加する。
- コードスニペットと疑われる場合、自動的に翻訳されず、翻訳をクリックする前にポップアップウィンドウが表示されます。
- 翻訳サービスの対象言語を選択する機能を追加
- アバウトページの追加、アップデートチャンネルとアップデートソースの選択
- キャッシュリフレッシュ、データクリア、インポート、エクスポートを含むデバッグメンテナンスページを追加。
- カスタムオプション： 'コードエディター送信ボタン位置'を追加。
- 各ローディング機能を改善し、不要な待機関係を削除し、スクリプトのローディング時間を短縮した。
- 翻訳機能とエラーメッセージの表示を改善。
- 自動翻訳の性能向上と自動翻訳されないかもしれない問題
- オンライン走行に関するコードサンプルの改善
- 実行結果の差分を比較するメソッドが改良された codeDiff()
- ダイアログウィンドウの背景がマウスでスクロールしないように改善。
- コードエディターが右側、下、フルスクリーンに固定されている場合のスタイルを改善！
- シンプルモードにおける.html2md-panelパネルの表示を改善した。
- 設定パネルの設定ページのスタイルを改善
- acmsguru タイトルページエディタのエラーを修正する
- ウェブサイトのモバイル／デスクトップ版を切り替えた後に、課題ページのコードエディターがエラーを報告する問題を修正しました。
- getMarkdown()メソッドのバグを修正しました。
- MoYuToGoさんからのフィードバックにより、「折りたたみブロックの自動展開」をオフにした後、折りたたみブロック内の翻訳ボタンが表示されない問題を修正！
- ページリソースが完全にロードされるのを待たない」オプションは理論的に無意味なので、以前は可能だった以下の状態のチェックを外すように名前が変更されました。
- 多数のコード構造の調整
- \*\*CSSのクラス名がたくさん変更されているので、スタイラスのカスタムスタイルを使用している場合は、それを調整する必要があるかもしれません。
- その他の調整と改善

***

- caoxuanming氏のフィードバックにより、ChatGPT設定パネルが表示されない問題を修正した！
- 設定スイッチ「Mouse Scroll Lock」を追加。

***

- clistレーティングのAPIをv4に更新し、タイトルページのデータがAPI経由で取得されるように調整した！
- ChatGPT翻訳に "ストリーミング "オプションを追加しました。
- Google翻訳の結果が空であることを修正 フィードバックをくださった@shicxin氏に感謝します！
- 設定スイッチ「コードコミットの二重確認」を追加、デフォルトでオン 提案してくれた@Rikkual氏に感謝する！
- 完全なトピックセットページに小さなエリアを追加するためのボタン
- 完全なトピックセットページを右クリックして印刷するときに翻訳結果が表示されない問題を修正しました。

***

- オンライン・コード・テストやコード提出などをサポートするため、タイトルページの下部にコード・エディタを追加しました。
- スクリプトボタンを挿入して結果を翻訳すると、タイトルの説明が変更されたものとして扱われる問題を修正しました。
- ポートフォリオ・マッシュアップ管理ページの改善
- 短いテキストの自動翻訳」機能を追加（デフォルトではオフ）。
- 翻訳待機間隔の実装が改善され、待機間隔がグローバルに機能するようになりました。
- ターゲットエリアの範囲を表示」機能の改善
- ダークモードの改善、サンプル要素のホバースタイルの改善 フィードバックをくださった@SUPERLWR氏に感謝します！
- 設定パネルオプションの追加：翻訳 - テキスト内の記号をフィルタする フィードバックをくれた@Dog_Eさん、CreMicroさんに感謝します！
- Vistarinのフィードバックにより、「Show loading alerts」をオフにした後にClist Ratingが正しく表示されない問題を修正しました。
- その他の改善と修正