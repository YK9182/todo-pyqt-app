# ToDoアプリ（PyQt版）

PythonとPyQt5で作成したGUIベースのタスク管理アプリケーションです。  
オブジェクト指向設計やUI構築、データのJSON保存などの学習を目的としています。

---

## 📌 実装済みの機能

- タスクの追加／表示
- タスク完了・未完了の切り替え
- タスクの削除
- 締切日順の並び替え
- タグでの絞り込み表示
- タイトルによるキーワード検索
- フィルタ適用中に「すべて表示に戻す」機能
- タスクの編集機能
- ファイル保存（JSON形式）

---

### 起動方法

```bash
pip install -r requirements.txt
python todo_PyQt.py
```
※仮想環境の使用を推奨します。

---

## 🧪 使用技術
・Python 3.13.1
・オブジェクト指向設計
・PyQt5
・JSONファイルによるタスク保存
・仮想環境（venv）による開発環境管理

---

## 📁 ディレクトリ構成
```
project/
├── task.py
├── todolist.py
├── todo_PyQt.py
├── tasks.json
├── requirements.txt
└── README.md
```

---

## 📝 ライセンス
このプロジェクトは MIT ライセンスのもとで公開されています。
