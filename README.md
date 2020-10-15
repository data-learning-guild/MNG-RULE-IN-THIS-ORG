# MNG-RULE-IN-THIS-ORG
Document about repository and DLG member management rules in this organization.

本リポジトリは、data-learning-guild organization における（DLG内のプロジェクトの）リポジトリの管理ルールを記述したドキュメントをまとめます。

## QA

誤植や不備に気づいた場合、または疑問点がある場合は、**本リポジトリのISSUEにコメントを登録** してください。

---

## 新規プロジェクト立ち上げ時の全体の流れ

1. **プロジェクトの担当者が** 新規プロジェクトに対応するリポジトリ（複数可）作成を依頼 to Organization Owner
2. **プロジェクトのメンバーが** Githubアカウント情報（username or email）を教える to Organization Owner
3. **Organization Ownerが** リポジトリを作成
4. **Organization Ownerが** 新規プロジェクト参加メンバーをリポジトリのコラボレータとして招待（チームリーダーにリポジトリの管理者権限を付与）
5. （必要ならば）**Organization Ownerが** Organizationに当該プロジェクトの為のProjectBoardを作成し、プロジェクトメンバーをコラボレータとして招待（チームリーダーにProjectBoardの管理者権限を付与）

## プロジェクト運用時の手順

下記は、基本的に守っていただきたいルールです。（柔軟性を重視して）システムによる制限は現段階ではかけていません。

### 開発作業

1. Mainブランチをいつでもリリース可能な状態にしておく
2. Mainブランチに直接プッシュしない
3. Organizationで管理しているリポジトリをFork > Mainブランチから別のブランチを切る > 修正＋commit＋push > PullReq to Mainブランチ on 元のリポジトリ
4. PullReqを作成したら、コードの修正に関する議論はPulReq上で実施してください

（ブランチ命名規則等細かい部分はチーム内で話し合ってください）
（どのブランチモデルを採用するかはチーム内で話し合ってください）

### タスク管理

1. タスクなどはリポジトリのIssueに登録
2. Issue上で議論してください（議論の内容を残す＋メンバーに共有するためです）

### ドキュメント管理

1. リポジトリのWikiやソース（READMEなど）で管理してください
※一箇所に集めたほうが管理がしやすいからです


