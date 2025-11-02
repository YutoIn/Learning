# Memo

## 1
hrsh7th

- nvim-cmp
  + 機能
    * カラフルな補完メニュー
    * LSPの定義に存在しないテキスト(選んだときに挿入されるテキスト)を補完する機能
  + 置き換える部分の検出
    1. 正規表現でキーワード検索
    2. 
    3. ヒューリスティックな実装
  + TextEditを返さないとき
    * vscodeではvscode-intelephenseで実装
    * nvim-cmpでは
      1. keyword text is vari
      2. buffer text is $vari
      3. preview test is $variable
  + 問題
    1. The commitCharacters
    2. auto-pairsとの衝突
      - 旧キーをハイジャックして解決
      - 新vim.on_key
      - ハッキーな実装は時間とともに不要になっていく
  + FOSS Challenges
    * 個人的に必要な機能とユーザーが必要な機能のすれ違い
      - ユーザは新しい機能よりも安定した挙動を求める
      - 責任感が生まれて燃え尽き症候群
    * コミュニティ運営
      - メンテナとしてはコントリビュータを信頼できない
    * サプライチェーン攻撃
      - コミットの中にマルウェアが存在した
      - 自分が攻撃の標的になる

- スポンサーLT_vim-jpラジオ
  + 単位系としてのHHKB(35000円)
  + エンジニアの楽園vim-jpラジオ
