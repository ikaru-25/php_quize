# php_quize
クイズゲームの開発でPHPを習得しましょう。

### echo();　関数で文字の表示

```quize.php
echo('クイズを開始します。');
```

### 変数の使用
ポイント：　変数は $ マークからスタートします。

```quize.php
$start_message = 'クイズを開始します。';
echo($start_message);
```

### readline()関数でユーザの入力を変数で取得する。
```quize.php
$q1 = readline("【第1問】サザエさんの年齢は？\n");

// 入力内容を表示してみましょう
echo($q1);
```


### if文で条件分岐
正解か不正解は条件分岐式で判定します。

```quize.php

// 正解の条件
// メッセージを表示して、点数をプラスします。
if($q1 == 24) {
    echo("正解です！\n");
    $score = $score + 30;

// 不正解の条件
// メッセージを表示します。
} else {
    echo("残念、ハズレです。。\n");
}
```