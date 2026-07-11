# 英語の基本時制・表現のまとめ

主語を「The bird（その鳥）」に統一し、**一般動詞（escape：逃げる）**と**be動詞（is / was：いる・ある）**の文法と例文を比較する。

---

## 1. 時制の全体イメージ図
各時制がどのような意味の広がりを持っているかの全体像。

```mermaid
graph TD
    %% メインの行動・状態
    A[鳥の行動・状態] --> B(基本の時制)
    A --> C(進行形<br>〜している最中)
    A --> D(未来の表現<br>〜するつもり/だろう)

    %% 基本の時制の分岐
    B --> B1[現在形<br>いつも〜する/今〜である]
    B1 --> B1_1[一般動詞: いつも逃げる<br>The bird escapes.]
    B1 --> B1_2[be動詞: 今カゴにいる<br>The bird is in the cage.]
    
    B --> B2[過去形<br>〜した/〜だった]
    B2 --> B2_1[一般動詞: 逃げた<br>The bird escaped.]
    B2 --> B2_2[be動詞: カゴにいた<br>The bird was in the cage.]

    %% 進行形の分岐
    C --> C1[現在進行形<br>いま逃げている<br>The bird is escaping.]
    C --> C2[過去進行形<br>そのとき逃げていた<br>The bird was escaping.]

    %% 未来の表現の分岐
    D --> D1[will<br>その場で決めた未来/推量<br>The bird will escape.]
    D --> D2[be going to<br>事前の予定・兆候<br>The bird is going to escape.]
