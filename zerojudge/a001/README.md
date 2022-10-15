# a001:哈囉

## 敘述

學習所有程式語言的第一個練習題 請寫一個程式，可以讀入指定的字串，並且輸出指定的字串。
比如：輸入字串 "world", 則請輸出 "hello, world"


## 說明

輸入:

輸入總共一行，內含一組文字

---

輸出:

輸出題目指定的文字。

## 範例
範例1

```
輸入:
world

---

輸出:
hello, world

```
範例2

```
輸入:
C++

---

輸出:
hello, C++

```
範例3

```
輸入:
Taiwan

---

輸出:
hello, Taiwan

```

## 程式碼
cpp

```cpp
#include<iostream>

using namespace std;

int main(){
    string text;
    cin>>text;
    cout<<"hello, "<<text<<endl;
    return 0;
}

```

py

```py
inp_text = input()
print("hello,",inp_text)

```

## 標籤
- 基本輸出輸入


## 連結
- GitHub: [cpp程式碼](https://github.com/henryleecode23/solve_record/blob/main/zerojudge/a001/main.cpp)
- GitHub: [py程式碼](https://github.com/henryleecode23/solve_record/blob/main/zerojudge/a001/main.py)


- 題目來源: [zerojudge](https://zerojudge.tw/ShowProblem?problemid=a001)

## [回首頁](https://henryleecode23.github.io/solve_record/)


最後編輯時間: 2022-10-16 01:49:07