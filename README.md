# 文字数チェッカー

### 背景
文字数計測のためのwebサイトはあったが、ペーストボタンがあるものは見つけられなかった。
そのためペーストボタンがついたサイトを作成したいと考えた。

### 苦労した点
textarea の style に苦労した
max-width と margin ではレスポンシブに対応できなかった。
main に padding をつけて textarea に w-full をつければレスポンシブ対応できた。

https://string-length-checker.vercel.app/
