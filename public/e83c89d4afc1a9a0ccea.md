---
title: システムデータが肥大化した時の解消法
tags:
  - Mac
private: false
updated_at: '2024-05-25T01:20:03+09:00'
id: e83c89d4afc1a9a0ccea
organization_url_name: null
slide: false
ignorePublish: false
---
## キャッシュの削除
`sudo rm -r /Library/Caches`
`sudo rm -r ~/Library/Caches`
`sudo rm -r /System/Library/Caches`

## バージョン管理、開発環境などの整理
`conda clean --all`
`brew cleanup`

## 参考
[お使いのMac上でシステム容量を消去する5つの方法](https://macpaw.com/ja/how-to/clear-system-storage-mac)
