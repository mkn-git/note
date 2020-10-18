# 语法糖
## 变长参数 `...`
    function add(...$int){
        return array_sum($int);
    }
    echo add(1,2,3); //输出6
## 太空船运算符 `<=>`
    $a <=> $b
    $a < $b 返回 -1
    $a = $b 返回 0
    $a > $b 返回 1
## null合并运算符
    $a = $b ?? $c 相当于 isset($a) ? $a : $c