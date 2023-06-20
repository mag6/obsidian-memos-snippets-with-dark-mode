# obsidian-memos-snippets-with-dark-mode
This is a simple css snippet that adjusts the appearance of [obsidian-memos](https://github.com/Quorafind/Obsidian-Memos) when used in dark mode. 

Additions, modifications and refactoring of features are welcome.

note: this is for only [obsidian-memos](https://github.com/Quorafind/Obsidian-Memos) 1.9.7 

This is a simplified adjustment to make the obsidian-memos compatible with non-default themes in dark mode, ensuring a match with the user's chosen theme.

The current features include:

1. The save buttons in the obsidian-memos' memo editor and memo comment section are set based on the user's chosen accent color.
2. The background color of the heatmap indicators, based on the number of memo posts, is set according to the accent color.
    - The hue of the accent color is shifted by 120 degrees ( like [triadic color scheme](https://www.homedit.com/colors/color-theory/triadic-color-scheme/).
    - Each level from 1 to 4 has different hues and lightness values based on the accent color. The lightness changes by 25% at each level.
3. The color scheme of the memo editor area is defined. The background color is based on the color variable `--background-primary` defined by each theme.
4. The color scheme of the area where the added memo list is displayed is defined. The background color and border color are based on the pre-defined color variables (var(--background-secondary), var(--background-modifier-border)).
5. The color scheme of the sidebar is defined. The background color is based on the color variable `--background-primary` defined by each theme.
6. The background color of the sidebar in mobile view is set. The background color is based on color variables such as `--background-primary` defined by each theme.

## for JPN

obsidian-memos をダークモードで利用する上で、デフォルトテーマ以外で利用した場合に、テーマとマッチするように簡易的に調整したものです。

機能の追加や修正、リファクタリングなどは大歓迎です。

注） [obsidian-memos](https://github.com/Quorafind/Obsidian-Memos) 1.9.7 用です。



現在の機能は以下の通りです。

1. obsidian-memos のメモエディターの保存ボタンとメモコメントセクションの保存ボタンを、ユーザーの設定したアクセントカラーに基づいて設定します。　
2. メモの投稿数に基づいたヒートマップの指標の背景色をアクセントカラーを基準に設定します。
    - アクセントカラーの色相を120度ずらしています。（対照色相配色）
    - レベル1から4までの各レベルには、アクセントカラーに基づいた異なる色相と明度があります。各レベルで明度が25%ずつ変化します。
3. めもエディタエリアの色スキームを定義します。背景色はそれぞれのテーマが定義している色変数 `--background-primary` に基づいています。

4. 追加されたメモのリストが表示されるエリアの色スキームを定義します。背景色とボーダー色は、事前に定義された色変数(var(--background-secondary), var(--background-modifier-border))に基づいています。

5. サイドバーの色スキームを定義します。背景色はそれぞれのテーマが定義している色変数 `--background-primary` に基づいています。

6. モバイルビューでのサイドバーの背景色を設定します。背景色はそれぞれのテーマが定義している色変数 `--background-primary` 等に基づいています。
