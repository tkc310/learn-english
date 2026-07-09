# 英語の基本時制・表現のまとめ

主語を「The bird（その鳥）」、動詞を「escape（逃げる）」に統一し、各時制の文法と例文を比較する。

---

## 1. 時制の全体イメージ図
各時制がどのような意味の広がりを持っているかの全体像。

```mermaid
graph TD
    %% メインの行動
    A[鳥の行動<br>escape] --> B(基本の時制)
    A --> C(進行形<br>〜している最中)
    A --> D(未来の表現<br>〜するつもり/だろう)

    %% 基本の時制の分岐
    B --> B1[現在形<br>いつも逃げる/習性<br>The bird escapes.]
    B --> B2[過去形<br>逃げた/過去の事実<br>The bird escaped.]

    %% 進行形の分岐
    C --> C1[現在進行形<br>いま逃げている<br>The bird is escaping.]
    C --> C2[過去進行形<br>そのとき逃げていた<br>The bird was escaping.]

    %% 未来の表現の分岐
    D --> D1[will<br>その場で決めた未来<br>The bird will escape.]
    D --> D2[be going to<br>事前の予定・兆候<br>The bird is going to escape.]
```

---

## 2. 文法・例文比較表

### 【基本の時制】現在形・過去形
現在形と過去形は、**一般動詞（escape）自体を変化**させる。否定文や疑問文では、動詞の代わりに時制や人称（単数/複数）の情報を引き受ける **does / did（助動詞）** を補う。

| 時制 | 人称変化（主語） | 肯定文 | 否定文 | 疑問文 |
| :--- | :--- | :--- | :--- | :--- |
| **現在形**<br>（現在の事実・習慣・習性） | **三人称単数**<br>(The bird) | The bird **escapes**. | The bird **does not escape**. | **Does** the bird **escape**? |
| | **複数・その他**<br>(The birds / I) | The birds **escape**. | The birds **do not escape**. | **Do** the birds **escape**? |
| **過去形**<br>（過去の事実・出来事） | **すべて共通**<br>(単数・複数同形) | The bird **escaped**. | The bird **did not escape**. | **Did** the bird **escape**? |

> [!NOTE]
> **do / does / did の文法規則**
> * **do**：現在形で、主語が三人称単数でないときに使う。動詞の「s」はそのまま。
> * **does**：現在形で、主語が三人称単数のときに使う。動詞の「s（またはes）」をdoesが吸収する。
> * **did**：過去形で、主語の人称に関わらず共通して使う。動詞の「過去の形（edなど）」をdidが吸収する。
> * **動詞の原形化**：否定文・疑問文では、does / did がすでに時制や人称の役割を果たしているため、後ろに続く `escapes` や `escaped` はすべて元の形（**escape：原形**）に戻る。

---

### 【進行形】現在進行形・過去進行形
進行形は **[ am / is / are / was / were ] ＋ [ 動詞のing形 ]** の組み合わせで作る。人称変化や否定・疑問のルールは、すべて **be動詞の規則** に従う。

| 時制 | 人称変化（主語） | 肯定文 | 否定文 | 疑問文 |
| :--- | :--- | :--- | :--- | :--- |
| **現在進行形**<br>（いま〜している） | **三人称単数**<br>(The bird) | The bird **is escaping**. | The bird **is not escaping**. | **Is** the bird **escaping**? |
| | **複数形**<br>(The birds) | The birds **are escaping**. | The birds **are not escaping**. | **Are** the birds **escaping**? |
| **過去進行形**<br>（そのとき〜していた）| **三人称単数**<br>(The bird) | The bird **was escaping**. | The bird **was not escaping**. | **Was** the bird **escaping**? |
| | **複数形**<br>(The birds) | The birds **were escaping**. | The birds **were not escaping**. | **Were** the birds **escaping**? |

> [!NOTE]
> `escaping` の形は主語が変わっても変化しない。手前の **be動詞（is/are/was/were）だけ**が変化する。

---

### 【未来の表現】will と be going to
未来の表現には主に2つのパターンがある。助動詞の **will** を使う形と、進行形に似た **be going to** を使う形である。

| 表現パターン | 人称変化（主語） | 肯定文 | 否定文 | 疑問文 |
| :--- | :--- | :--- | :--- | :--- |
| **will**<br>（〜するだろう / 意志） | **すべて共通**<br>(単数・複数同形) | The bird **will escape**. | The bird **will not escape**. | **Will** the bird **escape**? |
| **be going to**<br>（〜する予定だ / 兆候）| **三人称単数**<br>(The bird) | The bird **is going to escape**. | The bird **is not going to escape**. | **Is** the bird **going to escape**? |
| | **複数形**<br>(The birds) | The birds **are going to escape**. | The birds **are not going to escape**. | **Are** the birds **going to escape**? |

> [!NOTE]
> `will` の後ろは必ず動詞の元の形（**escape**）になる。`be going to` は進行形と同じく、先頭の **be動詞（is/are）だけ**が変化する。

---

# 否定文・疑問文の瞬間判断ルール

否定文・疑問文を作るときは、元の文の動詞の「形」を見て、使う言葉を3つにグループ分けする。

```mermaid
graph TD
    A[動詞の形を見る] --> B{どのグループ?}
    
    B -->|動詞のまま<br>s や ed がある| C[1. 一般動詞グループ<br>do / does / did]
    B -->|動詞が ing 形<br>〜している最中| D[2. 進行形グループ<br>is / are / was / were]
    B -->|未来の表現<br>will / be going to| E[3. 未来グループ<br>will / is / are]
```

---

## 瞬間判断の比較表

否定文は**「この言葉の後ろに not を置く」**、疑問文は**「この言葉を主語の前に出す」**と判断する。

| グループ（文の形） | 使う言葉 | 瞬間的な見分け方 | 例文（否定 / 疑問） |
| :--- | :--- | :--- | :--- |
| **1. 一般動詞**<br>（現在・過去） | **do / does / did** | 動詞がそのままポツンとあるとき。<br>（`escapes`, `escaped` など） | The bird **does not** escape.<br>**Does** the bird escape? |
| **2. 進行形**<br>（いま・そのとき） | **is / are / was / were** | 動詞が **ing形** になっているとき。<br>（`escaping`） | The bird **is not** escaping.<br>**Is** the bird escaping? |
| **3. 未来表現**<br>（これから〜する） | **will**<br>または<br>**is / are** | **will** が見えているか、<br>**be going to** のとき。 | The bird **will not** escape.<br>The bird **is not** going to escape. |

---

## 判断を速くする3つのポイント

1. **一般動詞は「応援団（do / does / did）」を呼ぶ**
   * 動詞（escape）だけでは否定・疑問の形になれない。そのため、代わりに do / does / did を呼び出す。
2. **進行形は「be動詞」が主役**
   * 動詞が `ing` になったら、後ろの `escaping` はそのまま動かさない。手前の **be動詞（is/are/was/were）** だけをいじる。
3. **will があれば will が最優先**
   * 英文の中に **will** があれば、do や be動詞の出番はない。will の後ろに not を置き、will を前に出す。
