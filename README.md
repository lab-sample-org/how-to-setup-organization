# how-to-setup-organization


## 0.前提条件

1. Githubアカウントがある
2. 基本的なGithubの使い方はわかる

TODO:これを補助するためのドキュメントを別ファイルに書く



## 1.Organizationを作成
<img alt="GitHub_Dashboard" src="https://github.com/user-attachments/assets/5af0e658-7c91-4f5e-bdfe-a87ba9865e95" />

1. 右上のアイコン > Your organizations
2. New organization
3. Create a free organization (必要に応じて有料プランに切り替える)
4. あとは流れに沿えばOK



## 2.メンバーの権限設定

### メンバーの権限をいったんゼロにする

1. Settings > Member privileges
2. Base permissions を No permission に変更

### チームを作成する

TODO:

### レポジトリを作成して指定チームにのみ権限を与える

TODO:



## 全体でのメンバー権限設定

(レポジトリのSettingsではなくOrganizationのSettingsから)
Settings > Member privileges

title | privilege | assignment
-- | -- | --
Base permissions | _ | No permission
Repository creation | Public | ON
_ | Private | ON
Repository ofrking | Allow forking of private repo | OFF

TODO: 上記テーブルの続き



## 参考

- [公式ドキュメント: 組織とチームに関するドキュメント](https://docs.github.com/ja/organizations)
- [【CTO1年目の教科書】GitHubにするべき初期設定3ステップを徹底解説](https://zenn.dev/enterrocken/articles/f6aa0577634f8d)
- [GitHubセキュリティ Organization運用のベストプラクティス](https://zenn.dev/tmknom/books/github-organization-security/viewer/repositories)
- [【GitHub】organizationのメンバー権限のユーザがcommitできないように設定する方法](https://qiita.com/enumura1/items/0ba22f541660c7e29372)
- [Github Organizationおすすめ初期設定](https://tech.cm-group.co.jp/posts/github-organization)
