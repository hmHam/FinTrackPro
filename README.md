# TrackPro
予算管理やタスク管理をするためのスマホアプリ


図はmermaidで書く！Githubと相性が良い
```mermaid
flowchart TD
    A[Start] --> B{ログイン成功？}
    B -- はい --> C[ダッシュボードを表示]
    B -- いいえ --> D[エラーメッセージを表示]
    C --> E[ログアウト]
    D --> A
```
