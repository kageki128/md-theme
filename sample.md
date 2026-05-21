# H1 見出し

## H2 見出し

### H3 見出し

#### H4 見出し

##### H5 見出し

###### H6 見出し

通常テキスト、**太字**、*斜体*、***太字かつ斜体***、~~取り消し線~~、`inline code`、<kbd>Command</kbd> + <kbd>K</kbd>、<mark>ハイライト</mark>、H<sub>2</sub>O、E = mc<sup>2</sup>。

改行を明示したい場合は、行末に半角スペースを 2 つ置きます。  
この行は同じ段落内の改行として表示されます。

リンク: [GitHub](https://github.com/)  
メールアドレス: <octocat@example.com>

脚注の参照です。[^note] もう 1 つの脚注も置いています。[^long-note]

[^note]: これは短い脚注です。
[^long-note]: これは少し長い脚注です。PDF 出力時に本文と脚注の文字サイズ、余白、リンクの見え方を確認できます。

![プレースホルダー画像](https://picsum.photos/seed/picsum/1920/1080)

---

> 引用文
>
> > ネストした引用
>
> - 引用内のリスト
> - 引用内の `inline code`

リスト

- 項目1
- 項目2
  - ネストした項目2-1
- 項目3

番号付きリスト

1. 項目1
2. 項目2
3. 項目3

タスク

- [x] タスク1
- [ ] タスク2

表

| 左寄せ | 中央寄せ | 右寄せ |
| :----- | :------: | -----: |
| apple  |  banana  |    120 |
| orange |  grape   |  3,400 |
| peach  |  melon   | 56,789 |

---

```js
function greet(name) {
  const message = `Hello, ${name}!`;
  console.log(message);
}

greet("Markdown PDF");
```

```diff
- color: #000000;
+ color: #24292f;
```

---

## HTML

Markdown の中に HTML を直接書けるレンダラーでは、次のような要素も表示できます。

<div class="note">
  <strong>Note:</strong> 独自クラスを使った補足ボックスです。
</div>

<div class="warning">
  <strong>Warning:</strong> 注意喚起用のボックスです。
</div>

## GitHub Alert

> [!NOTE]
> これは GitHub 形式の Note Alert です。レンダラーによっては通常の引用として表示されます。

> [!TIP]
> ちょっとしたヒントを示す Alert です。

> [!WARNING]
> 注意が必要な内容を示す Alert です。

