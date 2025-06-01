# ルールセットレシピ
スタータールールセットは、[リポジトリルール](https://docs.github.com/ja/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets) を簡単に始められるように事前に用意されています。

## ルールセットとは？

ルールセットは、リポジトリに適用される名前付きのルール一覧です。ルールセットを作成することで、リポジトリ内の特定のブランチやタグに対する操作方法を制御できます。例えば、特定のブランチへのコミット権限や、タグの削除・リネーム権限などを管理できます。例として、フィーチャーブランチに対して署名付きコミットを必須にし、リポジトリ管理者以外の強制プッシュをブロックするルールセットを設定できます。

## はじめ方
1. このリポジトリをコピーします
 - ⬆️ 上部の `< > Code` をクリック
 - [GitHub CLI](https://cli.github.com/) など好きな方法でクローン、または ZIP をダウンロードしてください。
2. 管理権限のあるリポジトリまたは組織にアクセスします。
 - ⚙️設定 > ルール > ルールセット へ移動
 - 「新しいルールセット」>「ルールセットをインポート」を選択
 - インポートしたいルールセットレシピのローカルクローンを選択
 - インポート内容を確認し、変更を保存！
 - 完了です！🎉

### 動画例
![上記手順に従って JSON ファイルからルールセットをインポートする様子のGIF。](https://github.com/github/release-assets/assets/7575792/8806fa8c-b874-4a4e-97ef-4f8c238f4d29)

# 目次
## ブランチルールセット
- [ブランチ保護のベストプラクティス](https://github.com/github/ruleset-recipes/blob/a1f8e53ec12857637e8762e689a3abc255ff2c2f/branch-rulesets/were-just-normal-repositories.json)
- [プルリクエストとコミットメッセージの規約を必須化](https://github.com/github/ruleset-recipes/blob/8cd19a8e06e6e523fffd43e4a59a554c210dcbe2/branch-rulesets/PRs%20and%20commits.json)
- [組織ルールセット: すべてを統べる一つのルール](https://github.com/github/ruleset-recipes/blob/8cd19a8e06e6e523fffd43e4a59a554c210dcbe2/branch-rulesets/org-rulesets/one-ruleset-to-rule-them-all.json)
## タグルールセット
- [タグ削除の防止](https://github.com/github/ruleset-recipes/blob/a1f8e53ec12857637e8762e689a3abc255ff2c2f/tag-rulesets/prevent-tag-delete.json)
- [組織ルールセット: すべてのタグにセマンティックバージョニングを要求し削除を防止](https://github.com/github/ruleset-recipes/blob/ac4b5ebc05219bb07de10f6094ad9ae8215bd39c/tag-rulesets/org-ruleset/tag-defaults.json)
