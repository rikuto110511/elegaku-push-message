# エレガンス学院 プッシュメッセージ送信

## ブランチの構成
* master
    ```
    リリース情報を管理するブランチ
    ```
* develop
    ```
    開発用のブランチ
    masterを元に作成する
    今回はめんどくさいのでこのブランチでリリース作業を行う。
    リリース作業時にmasterブランチにマージする
    ```
* 作業ブランチ（nishiokaとか）
    ```
    実際に修正などを行うブランチ
    developを元に作成する
    修正が完了したらdevelopブランチにマージする
    ```
