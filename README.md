# RubyMap
mapメソッド

## 処理
Enumerableモジュールのmapメソッドを使って配列を計算して出力する。

## コード
```
numbers = [12, 34, 56, 78, 90]

result = numbers.map do |n|
    n * 3
end
p result
```

## 出力結果  
```
[36, 102, 168, 234, 270]
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
