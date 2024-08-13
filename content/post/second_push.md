+++
title = 'second_push'
date = 2024-08-14T04:09:20+09:00
draft = false
summary = "The summary content"
+++

# Markdown記法 チートシート

## Code の挿入
### code block
```c
#include <stdio.h>

int main(void){
  int a=0;
  printf("%d", a);
  printf("%p", &a);

  int *b;
  b=&a;
  printf("%d", *b);
  printf("%p", b);
}
```

### code span
`#ffce44`

`` `rgb(255,0,0)` ``

``` ``rgba(0,255,0,0.4)`` ```

## Format Text
### 見出し
見にくくなっちゃうので省略

### Emphasis
*emタグ並の強調*

**strong並の強調**

### Strikethrough
~~打ち消し~~

### Details

<details><summary>サンプルコード（open属性なし）</summary>

```rb
puts 'Hello, World'
```
</details>

<details open><summary>サンプルコード（open属性あり）</summary>

```rb
puts 'Hello, World'
```
</details>

## List
### Unordered List
- これは
- 順序なしリスト
- です
### Ordered List
1. これは
2. 順序つきリスト
3. です
### Checkbox
- [x] ご飯を食べる
- [ ] 寝る
### Blockquotes
