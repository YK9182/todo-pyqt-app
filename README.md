# ToDoアプリ（PyQt版 / Flask版）

Pythonで作成したタスク管理アプリケーションです。  
GUI（PyQt5）とWeb（Flask）の2種類のインターフェースを実装しています。  
オブジェクト指向設計・JSONによるファイル保存・UI構築の学習を目的に開発しました。

---

## 📌 機能一覧

- タスクの追加／表示
- タスク完了・未完了の切り替え
- タスクの削除
- 締切日順での並び替え
- タグでの絞り込み表示
- タイトルでのキーワード検索
- フィルタ状態から「すべて表示」に戻す機能
- タスクの編集機能
- ファイル保存（JSON形式）

---

## 🖥 GUI版（PyQt5）

### 使用ライブラリ
- PyQt5

### 起動方法

```bash
pip install -r requirements.txt
python todo_PyQt.py

---

## 🌐 Web版（Flask）
使用ライブラリ
Flask

起動方法
pip install -r requirements.txt
python app.py
Flask版は、http://localhost:5000 でアクセス可能です。

---

## 🧪 使用技術
Python 3.13.1

オブジェクト指向設計

PyQt5（GUI）

Flask（Web）

JSONファイルによるデータ保存

仮想環境（venv）を使用

---

## 📁 ディレクトリ構成

project/
├── task.py
├── todolist.py
├── todo_PyQt.py
├── app.py
├── tasks.json
├── requirements.txt
└── README.md

---

## 🎯 今後の展望（例）
Web版のUI改善（HTML/CSSの装飾）

タグ管理機能の強化（追加・削除のUI）

タスクの並び替え（優先度順など）

---

## 📝 ライセンス
このプロジェクトはMITライセンスのもとで公開されています。
