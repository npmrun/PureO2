---
title: Markdown测试
description: Markdown测试
pubDate: 2023/2/20 19:32:27
updatedDate: 2023/2/20 19:33:27
heroImage: https://api.lorem.space/image/book?w=1360&h=800
---

# 欢迎使用PureO2

## Contents

- [Contents](#contents)
- [Headings](#headings)
  - [Heading](#heading)
    - [Heading](#heading-1)
      - [Heading](#heading-2)
        - [Heading](#heading-3)
- [Paragraphs](#paragraphs)
- [Lists](#lists)
  - [Definition List (dl)](#definition-list-dl)
  - [Ordered List (ol)](#ordered-list-ol)
  - [Unordered List (ul)](#unordered-list-ul)
  - [Checkbox List (ul)](#checkbox-list-ul)
- [Table](#table)
- [Code](#code)
- [Misc](#misc)
- [YouTube Components](#youtube-components)

---

## Headings

### Heading

#### Heading

##### Heading

###### Heading

[scrollToTop](#contents)

---

## Paragraphs

**_The_** _quick_ <u>brown</u> [fox](https://www.foxnews.com/) `jumps` ~~over~~ the lazy **dog**.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

建格的何另始養離腳合兒現各談花車是都無處與費別、信善行修覺自！壓總談下市率應次司公母兒用什一線送用標地倒直作任老數年白安足個後引使名隊懷持日落異今特族？

一士我像衣買了人義，計念？

期老外並中般灣作各現初知強車我的品式企國立市它北待不型師文人注信方，各成能久，然的孩界，他事應在創灣字母寫麼，會不作散際，學節水……全當名己會天還著行多是生如內他道了家至種樣見景時一……區行水影。滿用機！野於不他北軍沒企國了安巴考治連，用然手些裡像是晚，法無走，教西單不假家這廣邊務土至行氣們個身王沒影，進的客動習外因國說，大傷生出壓統發信全一非爾證。被明快至一子的劇成，義定種刻戲立日發民！出安大是養下裡的，認放官時外的：的富你排說物展年定實兒良吃乎、陸般動後，不力在理校感……顧眼王長力老。

重多一？生光聯……動說麼了：起形市般我題臉事級。

> In solitude, where we are least alone.

私は絶対いよいよ漠然たる相当心に対してはずの他にできるならな。けっして今に養成めも何だか漠然たる仕事たないだけにしからならでをは話安んずるないですて、わざわざには聴いましたなけれた。権力を気がつきなのはどうしても先刻が毫もらしくでう。

ようやく嘉納さんに供獄とても承諾をやるでしょ習慣その主義それか攻撃にに対してお関係でたあるですと、その今は俺か釣竿頭に喜ぶば、嘉納さんののより考のそれをよくごふりと云ってあなた一団がお融和へ見えようにまあご経験にしずませば、とうとうもっとも誤解になるたでいるないのを思っですた。しかもしかしながら大首へする気もずいぶん美味と移ろたて、この言葉にもいうですてってがたにしてしまえたない。この限り時代のためその学校も私上を吹き込んんかと大森さんをしなませ、人の今日んというご講義ただですば、晩の時で長靴が始めだけの時代に前もっでいて、どうの今日が思えばそのためとあたかも足りんなとしだ事でが、ないますなて少し実職業いでし事だろたませ。

さて学校か不幸か話に教えですけれども、今中力が起るて得るですためがご講演の今に訊かたです。多年をはどうしても思うでいうんたずでと、まるで何とも繰り返しが周旋はさっそく悪いうので。

[scrollToTop](#contents)

---

## Lists

### Definition List (dl)

<dl>
    <dt>Definition List Title</dt>
    <dd>This is a definition list division.</dd>
</dl>

### Ordered List (ol)

1. List Item 1
2. List Item 2
3. List Item 3

### Unordered List (ul)

- List Item 1
- List Item 2
- List Item 3

### Checkbox List (ul)

- [ ] List Item 1 unchecked
- [x] List Item 2 checked
- [x] List Item 3 checked

## Table

| Table Header 1 | Table Header 2 | Table Header 3 |
| -------------- | -------------- | -------------- |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |

| Table Header 1 | Table Header 2 | Table Header 3 |
| :------------- | :------------: | -------------: |
| Division 1     |   Division 2   |     Division 3 |
| Division 1     |   Division 2   |     Division 3 |
| Division 1     |   Division 2   |     Division 3 |

[scrollToTop](#contents)

## Code

This is an array `[1, 2, 3]{:js}` of numbers 1 through 3.

The name of the function is `getStringLength{:.entity.name.function}`.

```ts title="examples/index.ts"
for (let x in [0]) console.log(x)
```

```js showLineNumbers
// Example JavaScript

const x = 7
function returnSeven() {
  return x
}
```

```ts {1-6}
interface IdLabel {
  id: number /* some fields */
}
interface NameLabel {
  name: string /* other fields */
}
type NameOrId<T extends number | string> = T extends number ? IdLabel : NameLabel
// This comment should not be included

// ---cut---
function createLabel<T extends number | string>(idOrName: T): NameOrId<T> {
  throw 'unimplemented'
}

let a = createLabel('typescript')
```

## Misc

<sup>Lorem</sup> <sub>ipsum</sub> <cite>dolor sit amet</cite>, <acronym title="Consectetur Adipiscing Elit">consectetur adipiscing elit</acronym>, <abbr title="Aliqua">sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</abbr>. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

リバースカードオープン、エネミーコントローラー！

ライフを 1000 払い、コマンド入力、<kbd>←</kbd> <kbd>→</kbd> <kbd>A</kbd> <kbd>B</kbd>！

このコマンドにより、全てのアニヲタを破壊する！

[scrollToTop](#contents)

## YouTube Components

<iframe width="100%" height="320px" src="https://www.youtube.com/embed/aHNWL7MBXoc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[scrollToTop](#contents)